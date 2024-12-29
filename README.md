<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EI J KHALATO BON</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            margin-top: 20%;
        }
        .color-change {
            font-size: 2em;
            animation: colorchange 2s infinite;
        }
        @keyframes colorchange {
            0% {color: red;}
            25% {color: blue;}
            50% {color: green;}
            75% {color: orange;}
            100% {color: purple;}
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 1em;
        }
        img {
            display: none;
            margin-top: 20px;
            width: 300px;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="color-change">EI J KHALATO BON</div>
    <div class="color-change">I LOVE YOU</div>
    <button onclick="showImage()">yes</button>
    <button id="noButton" onclick="moveButton()">no</button>
    <img id="popupImage" src="https://jumu22.github.io/koly-/yourimage.jpg" alt="Popup Image">

    <script>
        function showImage() {
            var img = document.getElementById('popupImage');
            img.style.display = 'block';
        }

        function moveButton() {
            var button = document.getElementById('noButton');
            var x = Math.floor(Math.random() * window.innerWidth);
            var y = Math.floor(Math.random() * window.innerHeight);
            button.style.position = 'absolute';
            button.style.left = x + 'px';
            button.style.top = y + 'px';
        }
    </script>
</body>
</html>
