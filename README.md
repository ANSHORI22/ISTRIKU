<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun Fatikhatun Nikmah!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s ease-in;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        h1 {
            color: #4caf50;
            animation: slideIn 2s ease-out;
        }

        @keyframes slideIn {
            0% { transform: translateY(-50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        .message {
            background-color: #fbff00;
            color: #4caf50;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            font-size: 20px;
            font-weight: bold;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .highlight {
            color: #ff5722;
            font-size: 24px;
            font-weight: 600;
        }

        .footer {
            margin-top: 30px;
            font-size: 16px;
            color: #555;
            animation: fadeIn 3s ease-out 1s forwards;
        }

        .image {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
        }

        /* Styling tombol play */
        .audio-controls {
            margin-top: 20px;
            padding: 10px;
            font-size: 18px;
            background-color: #4caf50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .audio-controls:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <!-- Foto -->
    <img src="istriku.jpg" width="200px" alt="Fatikhatun Nikmah" class="image">

    <h1>Selamat Ulang Tahun Istriku, Fatikhatun Nikmah!</h1>
    <div class="message">
        Semoga di usia ke-25 tahun ini, kamu semakin bahagia, sukses, dan sehat selalu. <br>
        Hari ini adalah hari istimewa, <span class="highlight">21 Desember 2024</span>! <br>
        Terima kasih telah menjadi bagian terindah dalam hidupku. <br>
        Aku akan selalu mendukungmu dan mencintaimu. Semoga kita bisa terus tumbuh bersama, dalam suka maupun duka.
    </div>

    <!-- Tombol Play/Pause Pindah ke Bawah -->
    <button class="audio-controls" onclick="toggleAudio()">Play/Pause</button>

    <!-- Audio Player -->
    <audio id="audio" preload="auto">
        <source src="lagu.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <div class="footer">
        <p>&copy; 2024 - Suamimu yang selalu mencintaimu 💖</p>
    </div>

    <script>
        function toggleAudio() {
            var audio = document.getElementById('audio');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }
    </script>
</body>
</html>

# ISTRIKU
WEB
