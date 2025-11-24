<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Η + Ε</title>
    <style>
        /* Force Times New Roman throughout */
        :root {
            --tnr: "Times New Roman", Times, serif;
        }
{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html, body {
            height: 100%;
            font-family: var(--tnr);
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        body {
            background: black;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #D344DB;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 100%;
            width: 100%;
            font-family: var(--tnr);
        }
        .equation {
            font-size: clamp(2.5em, 8vw, 4em);
            font-weight: bold;
            margin-bottom: 20px;
            text-shadow: 0 0 15px #D344DB;
            line-height: 1.2;
            font-family: var(--tnr);
        }
        .message {
            font-size: clamp(1.5em, 6vw, 2.5em);
            font-weight: bold;
            text-shadow: 0 0 20px #D344DB, 0 0 30px #D344DB;
            padding: 15px;
            animation: glow 1.5s ease-in-out infinite alternate;
            line-height: 1.4;
            font-family: var(--tnr);
            -webkit-font-smoothing: antialiased;
        }
        @keyframes glow {
            from {
                text-shadow: 0 0 10px #D344DB, 0 0 20px #D344DB;
            }
            to {
                text-shadow: 0 0 20px #D344DB, 0 0 30px #D344DB, 0 0 40px #D344DB;
            }
        }
        /* Mobile optimization */
        @media (max-width: 480px) {
            .equation {
                margin-bottom: 15px;
            }
            .message {
                padding: 10px;
            }
        }
        /* Prevent zoom on iOS */
        @media (max-width: 768px) {
            body {
                touch-action: manipulation;
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
