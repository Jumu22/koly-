<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ei j vabi asslamu alikum </title>
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
    </style>
</head>
<body>
    <div class="color-change">VABI ASSALAMUALAIKUM</div>
    <div class="color-change">I LOVE YOU</div>
    <button onclick="redirectToLink()">yes</button>
    <button id="noButton" onclick="moveButton()">no</button>

    <script>
        function redirectToLink() {
            window.location.href = "https://ibb.co.com/VqVD1yf";
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
