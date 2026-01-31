# Birthday-Pushkar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Pushkar!</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #fff5f8;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
            /* Floral Border using Emojis/Patterns */
            border: 30px solid transparent;
            border-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Ctext y='50' font-size='40'%3E🌸%3C/text%3E%3Ctext x='50' y='90' font-size='40'%3E🌼%3C/text%3E%3C/svg%3E") 30 round;
        }

        .container {
            text-align: center;
        }

        h1 {
            font-size: 4rem;
            color: #d81b60;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
            40% {transform: translateY(-30px) scale(1.1);}
            60% {transform: translateY(-15px);}
        }

        .subtitle {
            font-size: 1.5rem;
            color: #888;
            margin-top: 10px;
            opacity: 0;
            animation: fadeIn 3s forwards;
            animation-delay: 1s;
        }

        @keyframes fadeIn {
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Happiest Birthday Pushkar!</h1>
        <div class="subtitle">Wishing you a blooming year ahead 🌸</div>
    </div>

</body>
</html>
