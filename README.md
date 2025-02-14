<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Memory Lane</title>
    <style>
        body {
            background-color: #ffb3e6;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 48px;
        }
        p {
            font-size: 28px;
        }
        .button-container {
            margin-top: 20px;
        }
        .btn {
            display: inline-block;
            padding: 15px 40px;
            font-size: 24px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            margin: 20px;
            border-radius: 10px;
        }
        .yes {
            background-color: green;
            color: white;
        }
        .no {
            background-color: red;
            color: white;
        }
        .yes:hover {
            background-color: darkgreen;
        }
        .no:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>

    <h1>Happy Valentine's Day!</h1>
    <p>Do you want to go down memory lane?</p>

    <div class="button-container">
        <button class="btn yes" onclick="goToYes()">Yes</button>
        <button class="btn no" onclick="goToNo()">No</button>
    </div>

    <script>
        function goToYes() {
            alert("Let's take a trip down memory lane! 💕");
        }

        function goToNo() {
            alert("Maybe another time! 😢");
        }
    </script>

</body>
</html>
