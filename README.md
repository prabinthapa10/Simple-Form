# Simple-Form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-image: url("img/man.jpg");
            margin: 0;
            padding: 0;
            color: white;
        }

        .left {
            /* border: 2px solid red;s */
            display: inline-block;
            position: absolute;
            top: 0;
            left: 30px;
            margin: 20px 10px;
            padding: 10px;
        }

        .left img {
            width: 45px;
            filter: invert(100%);
        }

        .left div {
            text-align: center;
            padding: 0px;
        }

        .mid {
            display: block;
            /* border: 2px solid green; */
            width: 700px;
            margin: 20px auto;

        }

        .right {
            /* border: 2px solid purple; */
            display: inline-block;
            position: absolute;
            top: 0;
            right: 20px;
            margin: 25px 10px;
        }

        .btn {
            font-family: 'Roboto', sans-serif;
            background-color: black;
            color: white;
            padding: 3px 10px;
            margin: 6px 3px;
            /* border: 2px solid gray; */
            border-radius: 10px;
            cursor: pointer;

        }

        .btn:hover {
            color: black;
            background-color: rgb(170, 168, 168);
        }

      

        .navbar li {
            display: inline-block;
        }

        .navbar li a {
            color: white;
            text-decoration: none;
            padding: 25px;
            margin: 10px;
            font-size: 18px;
        }

        .navbar li a:hover {
            color: rgb(139, 70, 230);
            text-decoration: underline;

        }

        .container {
            height: 400px;
            border: 3px solid white;
            width: 530px;
            margin: 115px;
            padding: 40px;
            border-radius: 20px;
        }
        .container h3{
            text-align: center;
        }
        .form-group{
           
        }
        .form-group input{
            display: block;
    width: 350px;
    text-align: center;
    margin: 8px auto;
    padding: 2px;
    border-radius: 10px;
        }
        .container button {
        display: block;
        width: 66%;
        margin: 20px auto;
        border-radius: 4px;
    }
    </style>
</head>

<body>
    <header>
        <!-- for logo -->
        <div class="left">
            <img src="/Project1/img/logo.png" alt="">
            <div>Fitness</div>
        </div>
        <!-- for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>
        <!-- for buttons -->
        <div class="right">
            <button class="btn">Call Us now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h3>Join the best gym of Damauli </h3>
        <form action="nobackend.php">
            <div class="form-group">
               <input type="text" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your email address">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your locality">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your contact no.">
            </div>
            <div class="">
                <button>Submit</button>
            </div>
        </form>
    </div>
</body>

</html>
