<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            background: url('back.jpg') no-repeat center center fixed;
            background-size: cover;
            text-align: center;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .wish-box {
            margin-top: 20px;
            padding: 15px;
            border: 2px solid #333;
            border-radius: 10px;
            background-color: #98AFC7;
            max-width: 400px;
            opacity: 0;
            transform: perspective(500px) rotateX(20deg);
            animation: fadeInAndRotate 1s forwards;
        }

        .birthday-gif {
            margin-top: 20px;
            width: 150px;
            height: auto;
        }

        @keyframes fadeInAndRotate {
            to {
                opacity: 1;
                transform: perspective(500px) rotateX(0deg);
            }
        }
    </style>
</head>
<body>
    <img src="C:\Users\mashf\OneDrive\Desktop\Happy Birthday\mubas.jpg" alt="Happy Birthday">
    
    <div class="wish-box">
        <h2>Hello Brishti!!!</h2>
        <p>
Wishing you a very Happy Birthday! You're the most precious thing I've ever had in my life, and I'll always wish nothing but the best for you.</p>
    </div>

    <div class="wish-box">
        <h2>And</h2>
        <p>Stay safe, be happy, and cherish every moment. </p>
    </div>

    <img class="birthday-gif" src="C:\Users\mashf\OneDrive\Desktop\Happy Birthday\hm.gif" alt="Birthday Gif 1">
    <img class="birthday-gif" src="C:\Users\mashf\OneDrive\Desktop\Happy Birthday\hm2.gif" alt="Birthday Gif 2">

    <audio controls loop>
        <source src="C:\Users\mashf\OneDrive\Desktop\Happy Birthday\tumi.mp3" type="audio/mp3">
    </audio>
</body>
</html>
