<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #fbe3e8;
        }
        img {
            width: 300px;
            border-radius: 10px;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes {
            background-color: #ff4d6d;
            color: white;
        }
        .no {
            background-color: #ddd;
            position: absolute;
        }
    </style>
</head>
<body>
    <h1>Will you be My Hapiness?</h1>
     "Try click no XD"
    <div class="buttons">
        <button class="yes" onclick="sayYes()">Yes</button>
        <button class="no" onmouseover="moveNo()">No</button>
    </div>
    <script>
        function sayYes() {
            document.body.innerHTML = "<h1>Have a nice day Khulangoo AKA KYO.</h1>";
        }
        function moveNo() {
            let noButton = document.querySelector('.no');
            let x = Math.random() * (window.innerWidth - 100);
            let y = Math.random() * (window.innerHeight - 50);
            noButton.style.left = ${x}px;
            noButton.style.top = ${y}px;
        }
    </script>
</body>
</html>
