<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>World's Trash Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fffbcc;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        h1 {
            color: #ff6347;
            font-size: 3em;
        }
        p {
            font-size: 1.5em;
            color: #333;
        }
        .funny-button {
            background-color: #4caf50;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
        }
        .funny-button:hover {
            background-color: #45a049;
            transform: scale(1.1);
        }
        .hidden-message {
            display: none;
            font-size: 2em;
            margin-top: 20px;
            color: #ff4500;
        }
        #initial-image {
            display: none; 
        }
        #hidden-image {
            margin-top: 20px; 
        }
    </style>
    <script>
        function showMessage() {
            const message = document.getElementById("hidden-message");
            const hiddenImage = document.getElementById("hidden-image");
            const initialImage = document.getElementById("initial-image");
            if (message) message.style.display = "block";
            if (hiddenImage) hiddenImage.style.display = "none";
            if (initialImage) initialImage.style.display = "block";
        }
    </script>
</head>
<body>
    <h1>Welcome to the Nuts Website Ever!</h1>
    <p>Why did the nuts join a band? Because it had the dicks!</p>
    <button class="funny-button" onclick="showMessage()">Click me for a surprise!</button>
    <p id="hidden-message" class="hidden-message">Боовдуулсан! 🐔🎉</p>

    <img id="initial-image" src="middle.jpg" alt="Hidden Image" width="300" height="426">
    <img id="hidden-image" src="aphoto.webp" alt="Hi, my name is Enkhuush" width="300" height="426">

    <footer>
        <p>© 2025 Suck bitches. No bitches in the making of this website.</p>
    </footer>
</body>
</html>
