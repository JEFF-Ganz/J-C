<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piringan Musik - JEFRIN & CINDY</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #0a192f; /* Warna biru kehitaman */
            font-family: Arial, sans-serif;
            color: white;
            overflow: hidden;
        }

        .container {
            position: relative;
            text-align: center;
            width: 100%;
            max-width: 500px;
            padding: 20px;
        }

        .table {
            position: relative;
            width: 400px;
            height: 400px;
            background: #2c3e50; /* Warna meja */
            border-radius: 10px;
            box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
            margin: 0 auto;
            overflow: hidden;
        }

        .table::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.05));
            animation: table-shine 3s infinite alternate;
        }

        @keyframes table-shine {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(100%);
            }
        }

        .vinyl {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 350px;
            height: 350px;
            background: url('IMG-20241114-WA0026.jpg') no-repeat center center;
            background-size: cover;
            border-radius: 50%;
            border: 10px solid #fff;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.7);
            animation: spin 8s linear infinite;
        }

        @keyframes spin {
            0% {
                transform: translate(-50%, -50%) rotate(0deg);
            }
            100% {
                transform: translate(-50%, -50%) rotate(360deg);
            }
        }

        h1, h2 {
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            font-size: 2.5em;
            margin: 0;
            animation: glow 2s infinite alternate;
            white-space: nowrap;
            background: linear-gradient(45deg, #ffffff, #ffd700); /* Gradient putih ke emas */
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        h1 {
            top: -100px;
        }

        h2 {
            bottom: -100px;
        }

        @keyframes glow {
            0% {
                text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #ff00de, 0 0 40px #ff00de, 0 0 50px #ff00de, 0 0 60px #ff00de, 0 0 70px #ff00de;
            }
            100% {
                text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6, 0 0 80px #ff4da6;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>JEFRIN & CINDY</h1>
        <div class="table">
            <div class="vinyl"></div>
        </div>
        <h2>FOREVER</h2>
        <br>
        <audio controls>
       <source src="Old Love - Yuji ⧸ Putri Dahlia (Official Lyrics Video).mp3"type="audio/mpeg";
        </audio>
    </div>
</body>
</html
