<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Η + Ε</title>
    <style>
        body {
            background: black;
            font-family: "Times New Roman", Times, serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #F527DA; /* Baby Pink */
            text-align: center;
        }
        .message {
            font-size: 2.5em;
            font-weight: bold;
            text-shadow: 0 0 20px #f4c2c2, 0 0 30px #f4c2c2;
            padding: 20px;
            animation: glow 1.5s ease-in-out infinite alternate;
        }
        .equation {
            font-size: 3.5em;
            margin-bottom: 20px;
            text-shadow: 0 0 15px #f4c2c2;
        }
        @keyframes glow {
            from {
                text-shadow: 0 0 10px #f4c2c2, 0 0 20px #f4c2c2;
            }
            to {
                text-shadow: 0 0 20px #f4c2c2, 0 0 30px #f4c2c2, 0 0 40px #f4c2c2;
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
