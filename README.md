<!DOCTYPE html>
<html>
<head>
    <title>Audio Player</title>

    <!-- Internal CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;

            /* Background Image */
            background: url("images/background.jpg");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        h1 {
            color: white;
        }

        /* Control Panel Styling */
        #cp {
            width: 600px;
            margin: 100px auto;
            text-align: center;
        }

        /* Button Styling */
        button {
            background-color: #3498db; /* change this color if you want */
            padding: 10px;
            margin: 5px;
            font-size: 18px;
            width: 100px;
            border: none; /* removes border */
            cursor: pointer;
            color: white;
        }

        /* Message Bar */
        #message {
            margin-top: 15px;
            font-weight: bold;
            color: #ffcc00; /* change to any color you like */
        }
    </style>

    <!-- jQuery -->
    <script src="https://code.jquery.com/jquery.min.js"></script>

    <!-- Your JavaScript file -->
    <script src="app.js"></script>
</head>
<body>

    <h1>My Audio Player</h1>

    <!-- Audio Element -->
    <audio id="audioPlayer" src="music.mp3"></audio>

    <!-- Control Panel -->
    <div id="cp">
        <button id="playBtn">Play</button>
        <button id="pauseBtn">Pause</button>
        <button id="stopBtn">Stop</button>
        <button id="volUpBtn">Volume +</button>
        <button id="volDownBtn">Volume -</button>

        <!-- Message Bar -->
        <p id="message">Waiting</p>
    </div>

</body>
</html>
