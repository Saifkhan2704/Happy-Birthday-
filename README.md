# Happy-Birthday-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Mantasha!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Happy Birthday, Mantasha! 🎉</h1>
        <p>Wishing you a day filled with love, joy, and endless happiness.</p>
        <div class="cake"></div>
        <div class="gift"></div>
        <p class="poem">
            A day so bright, a heart so pure,<br>
            Your kindness and grace will always endure.<br>
            May your dreams take flight and reach the sky,<br>
            With love and joy that never says goodbye.<br>
        </p>
    </div>
    <script src="script.js"></script>
</body>
</html>


body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(to right, #fbc2eb, #a6c1ee);
    text-align: center;
    color: #333;
    margin: 0;
    padding: 0;
}

.container {
    padding: 50px;
}

h1 {
    font-size: 36px;
    color: #fff;
    text-shadow: 2px 2px 4px #000;
}

p {
    font-size: 18px;
}

.cake, .gift {
    width: 100px;
    height: 100px;
    margin: 20px auto;
    background-size: cover;
}

.cake {
    background-image: url('https://i.imgur.com/dyB7eTB.png'); /* Cake Image */
}

.gift {
    background-image: url('https://i.imgur.com/FhQwCV2.png'); /* Gift Image */
}

@keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
}

.cake, .gift {
    animation: bounce 1s infinite;
}
