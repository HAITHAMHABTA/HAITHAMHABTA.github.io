<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haitham's Minecraft Channel////This website is under construction not all capabilities are available for now....</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000; /* Set the background color to black */
            color: #fff; /* Set text color to white */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        h1 {
            font-size: 36px;
            margin: 0;
        }
        p {
            font-size: 18px;
            margin: 20px 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #000; /* Set the background color of the content box to black */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .subscribe-button {
            display: block;
            text-align: center;
            background-color: #f00;
            color: #fff;
            padding: 10px 20px;
            margin: 20px auto;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            font-size: 20px;
        }
        .subscribe-button:hover {
            background-color: #d00;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Haitham's Minecraft Channel</h1>
    </header>
    <div class="container">
        <h2>About Haitham's Channel</h2>
        <p>Haitham is a passionate Minecraft player and content creator who delivers top-quality Minecraft videos. His channel is dedicated to exploring the vast world of Minecraft, sharing tips and tricks, and creating amazing adventures.</p>
        
        <h2>Why Subscribe?</h2>
        <p>If you're a Minecraft enthusiast or just love watching entertaining gaming content, Haitham's channel is perfect for you. Here's why you should subscribe:</p>
        <ul>
            <li>Engaging and informative Minecraft tutorials.</li>
            <li>Exciting Minecraft adventures and Let's Play series.</li>
            <li>Regularly updated content to keep you entertained.</li>
            <li>Join a vibrant community of Minecraft fans.</li>
        </ul>

        <a href="https://www.youtube.com/channel/UC4O7uCsdpSucq3rAmtgJj9g" class="subscribe-button" target="_blank">Subscribe Now</a>
        
        <!-- Add the first MP3 audio file that loops -->
        <audio id="audioPlayer1" controls loop>
            <source src="Maher_Zain_Mawlaya_Official_Lyric_Video.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <!-- Play Button for the first audio -->
        <button id="playButton1">Play</button>

        <!-- JavaScript to play audio when the button is clicked -->
        <script>
            const audio1 = document.getElementById('audioPlayer1');
            const playButton1 = document.getElementById('playButton1');

            playButton1.addEventListener('click', () => {
                if (audio1.paused) {
                    audio1.play();
                    playButton1.textContent = 'Pause';
                } else {
                    audio1.pause();
                    playButton1.textContent = 'Play';
                        <!-- Add the first MP3 audio file that loops -->
        <audio id="audioPlayer1" controls loop>
            <source src="Maher Zain | ماهر زين - يا نبي سلام عليك | Official Music Video.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <!-- Play Button for the first audio -->
        <button id="playButton1">Play</button>

        <!-- JavaScript to play audio when the button is clicked -->
        <script>
            const audio1 = document.getElementById('audioPlayer1');
            const playButton1 = document.getElementById('playButton1');

            playButton1.addEventListener('click', () => {
                if (audio1.paused) {
                    audio1.play();
                    playButton1.textContent = 'Pause';
                } else {
                    audio1.pause();
                    playButton1.textContent = 'Play';
                }
            });
        </script>
    </div>
</body>
</html>

