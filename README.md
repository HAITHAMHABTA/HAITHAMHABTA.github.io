<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haitham's Minecraft Channel</title>
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
        <audio id="audioPlayer1" controls loop autoplay>
            <source src="Maher Zain - Mawlaya | Official Lyric Video | ماهر زين - مولاي.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <!-- Play/Pause Button for the first audio -->
        <button id="playPauseButton1">Pause</button>

        <!-- Add the second MP3 audio file that loops -->
        <audio id="audioPlayer2" controls loop autoplay>
            <source src="your-second-audio-file.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <!-- Play/Pause Button for the second audio -->
        <button id="playPauseButton2">Pause</button>

        <script>
            // Function to play or pause audio for the first audio
            function toggleAudio1() {
                const audio1 = document.getElementById('audioPlayer1');
                const playPauseButton1 = document.getElementById('playPauseButton1');
                if (audio1.paused) {
                    audio1.play();
                    playPauseButton1.textContent = 'Pause';
                } else {
                    audio1.pause();
                    playPauseButton1.textContent = 'Play';
                }
            }

            // Function to play or pause audio for the second audio
            function toggleAudio2() {
                const audio2 = document.getElementById('audioPlayer2');
                const playPauseButton2 = document.getElementById('playPauseButton2');
                if (audio2.paused) {
                    audio2.play();
                    playPauseButton2.textContent = 'Pause';
                } else {
                    audio2.pause();
                    playPauseButton2.textContent = 'Play';
                }
            }

            // Add click event listeners to the buttons
            document.getElementById('playPauseButton1').addEventListener('click', toggleAudio1);
            document.getElementById('playPauseButton2').addEventListener('click', toggleAudio2);
        </script>
    </div>
</body>
</html>
