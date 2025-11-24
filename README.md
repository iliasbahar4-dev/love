# love
<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message</title>
    <style>
        body {
            background: black;
            font-family: "Times New Roman", Times, serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #ff69b4;
            text-align: center;
        }
        .message {
            font-size: 2.5em;
            font-weight: bold;
            text-shadow: 0 0 20px #ff69b4, 0 0 30px #ff69b4;
            padding: 20px;
            animation: glow 1.5s ease-in-out infinite alternate;
        }
        .equation {
            font-size: 3.5em;
            margin-bottom: 20px;
            text-shadow: 0 0 15px #ff69b4;
        }
        @keyframes glow {
            from {
                text-shadow: 0 0 10px #ff69b4, 0 0 20px #ff69b4;
            }
            to {
                text-shadow: 0 0 20px #ff69b4, 0 0 30px #ff69b4, 0 0 40px #ff69b4;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="equation">Η + Ε =</div>
        <div class="message">ΛΟΒ ΦΟΡ ΕΒΕΡ ΕΝΤ ΕΒΕΡ<br>ΕΝΤ ΕΒΕΡ<br>ΕΝΤ ΕΒΕΡ</div>
    </div>
</body>
</html>
