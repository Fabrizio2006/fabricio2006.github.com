<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Día de la Mujer</title>
    <style>
        body {
            background-color: #ffcccb; /* Color de fondo rosa */
            background-image: radial-gradient(circle, white 20%, transparent 20%), radial-gradient(circle, white 20%, transparent 20%);
            background-size: 50px 50px; /* Tamaño del patrón de corazones */
            background-position: 0 0, 25px 25px; /* Posicionamiento del patrón */
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            overflow: hidden;
            position: relative;
            color: white; /* Cambia el color del texto para que sea visible sobre el fondo */
        }
        .heart {
            font-size: 100px;
            color: red;
            animation: rotateY 4s linear infinite; /* Rotación vertical */
            margin: 20px 0;
        }
        .message {
            font-size: 24px;
            margin: 20px 0;
            animation: fadeIn 2s;
            font-style: italic; /* Texto en cursiva */
            color: black; /* Color del texto en negro */
        }
        .flowers {
            font-size: 50px;
            color: pink;
            animation: float 3s infinite;
        }
        .rose {
            position: absolute;
            font-size: 30px;
            animation: float 4s infinite;
        }
        .falling-heart {
            position: absolute;
            font-size: 20px;
            animation: fall 3s linear infinite;
        }
        .letter {
            background-color: rgba(255, 255, 255, 0.8); /* Fondo blanco con opacidad */
            border-radius: 15px; /* Bordes redondeados */
            padding: 20px;
            margin: 0 auto;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            color: black; /* Color del texto de la carta */
        }
        @keyframes rotateY {
            0% {
                transform: rotateY(0deg);
            }
            100% {
                transform: rotateY(360deg);
            }
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        @keyframes float {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
            100% {
                transform: translateY(0);
            }
        }
        @keyframes fall {
            0% {
                top: -10%;
                opacity: 1;
            }
            100% {
                top: 100%;
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <div class="heart">❤️</div>
    <div class="message">Feliz Día  para todas esas mujeres que nos dan ese empujocito</div>
    
    <div class="letter">
        <p>A todas las mujeres:</p>
        <p>Gracias por ser ustedes. Sus sonrisas, sus lágrimas, sus abrazos… todo. Su fuerza, su ternura, su valentía me inspiran. Gracias por ser madres, hermanas, amigas, por ser humanas, maravillosas, simplemente… perfectas.</p>
    </div>

    <div class="flowers">🌸🌸🌸🌸🌸🌸🌸</div>

    <div class="rose" style="top: 10%; left: 10%;">🌹</div>
    <div class="rose" style="top: 20%; left: 30%;">🌹</div>
    <div class="rose" style="top: 30%; left: 50%;">🌹</div>
    <div class="rose" style="top: 40%; left: 70%;">🌹</div>
    <div class="rose" style="top: 50%; left: 90%;">🌹</div>

    <!-- Lluvia de corazones en toda la pantalla -->
    <div class="falling-heart" style="left: 5%; animation-delay: 0s;">❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️</div>
    <div class="
