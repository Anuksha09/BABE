<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFEBEE;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }

        /* Container for the birthday greeting */
        .container {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            padding: 30px;
            width: 80%;
            max-width: 600px;
        }

        /* Title styles */
        h1 {
            font-size: 48px;
            color: #FF4081;
            margin: 0;
            padding-bottom: 20px;
        }

        /* Subtitle styles */
        h2 {
            font-size: 24px;
            color: #555;
            margin-top: 0;
        }

        /* Balloon animation */
        .balloon {
            width: 80px;
            height: 120px;
            border-radius: 50%;
            background-color: #FF4081;
            position: absolute;
            animation: float 3s ease-in-out infinite;
        }

        .balloon:nth-child(1) {
            left: 20%;
            animation-duration: 3s;
            animation-delay: 0s;
        }

        .balloon:nth-child(2) {
            left: 40%;
            background-color: #FF5722;
            animation-duration: 2.5s;
            animation-delay: 1s;
        }

        .balloon:nth-child(3) {
            left: 60%;
            background-color: #9C27B0;
            animation-duration: 4s;
            animation-delay: 0.5s;
        }

        .balloon:nth-child(4) {
            left: 80%;
            background-color: #3F51B5;
            animation-duration: 3.5s;
            animation-delay: 1.5s;
        }

        @keyframes float {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-30px);
            }
            100% {
                transform: translateY(0);
            }
        }

        /* Cake image */
        .cake {
            background: url('https://via.placeholder.com/200x200/FFEBEE/000000?text=Birthday+Cake') no-repeat center center;
            background-size: contain;
            width: 200px;
            height: 200px;
            margin: 20px auto;
        }

        /* Button for more fun */
        .btn {
            background-color: #FF4081;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 18px;
            text-transform: uppercase;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #FF1D5C;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Happy Birthday Kashuuu!!</h1>
        <h2>Wishing you a day filled with joy, laughter, and lots of cake!
            may you get all the love... Stay healthy and Stay safe...!!
            GOD BLESS ^_^ 
        </h2>
        
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        
        <div class="cake"></div><pre>
CLICK BELOW...!!
        </pre>
        <button><a href="HBD2.html">Make a Wish!</a></button>
    </div>

</body>
</html>

