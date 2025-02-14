<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day Card</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
        }
        .card {
            width: 300px;
            height: 400px;
            background: white;
            border-radius: 20px;
            box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .heart {
            color: red;
            font-size: 50px;
            margin-top: 20px;
            animation: pulse 1s infinite alternate;
        }
        @keyframes pulse {
            from { transform: scale(1); }
            to { transform: scale(1.2); }
        }
        .message {
            padding: 20px;
            font-size: 18px;
            color: #555;
        }
        .footer {
            position: absolute;
            bottom: 20px;
            width: 100%;
            font-weight: bold;
            color: #e60000;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="heart">❤️</div>
        <div class="message">
            <h2>Happy Valentine's Day!</h2>
            <p>You make my world brighter and my heart fuller. Thank you for being you!</p>
        </div>
        <div class="footer">With Love 💕</div>
    </div>
</body>
</html>
