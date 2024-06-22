<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog com Link de Afiliado</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Pacifico&display=swap');

        body {
            margin: 0;
            padding: 0;
            font-family: 'Raleway', sans-serif;
            background-color: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            min-height: 100vh;
        }

        .video-container {
            display: flex;
            justify-content: center;
            width: 100%;
            margin: 20px 0;
        }

        .video-container iframe {
            width: 180px;
            height: 320px;
            margin: 0 10px;
            border: none;
        }

        .affiliate-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 20px;
            padding: 20px;
            border: 2px solid #4CAF50;
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.9);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }

        .affiliate-text {
            font-family: 'Pacifico', cursive;
            font-size: 2.5em;
            color: #FF5722;
            margin-bottom: 20px;
            text-shadow: 2px 2px #000;
        }

        .affiliate-button {
            font-size: 1.5em;
            color: #fff;
            background-color: #FF5722;
            border: none;
            padding: 15px 30px;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
            margin-top: 20px;
            transition: background-color 0.3s, transform 0.3s;
        }

        .affiliate-button:hover {
            background-color: #FF7043;
            transform: scale(1.05);
        }

        .affiliate-button:active {
            transform: scale(1);
        }
    </style>
    <script>
        // Função para reproduzir áudio ao carregar a página
        function playAudio() {
            var audio = new Audio('https://files.fm/u/ydkw7ug46h');
            audio.addEventListener('canplaythrough', function() {
                audio.play();
            });
        }

        // Chamada da função ao carregar a página
        window.addEventListener('DOMContentLoaded', playAudio);
    </script>
</head>
<body>
    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/4VYfycw9fMM?autoplay=1&mute=1" allow="autoplay" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/VcW9TUrmJ_4?autoplay=1&mute=1" allow="autoplay" allowfullscreen></iframe>
    </div>
    <div class="affiliate-container">
        <div class="affiliate-text">
            Baixe e ganhe 10 reais <span>💰</span> <span>🎉</span>
        </div>
        <a href="https://9f.com/r/bPpWn5S1" class="affiliate-button">
            Clique aqui para ganhar!
        </a>
    </div>
</body>
</html>
