<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignement</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="banner">
        <div class="navbar">
            <h1>MY PORTFOLIO</h1>
          
            <ul>
                <li><a href='#'>Home</a></li>
                <li><a href='#'>About</a></li>
                <li><a href='#'>Contact</a></li>
                <li><a href='#'>Education</a></li>
            </ul>
        </div>
        <div class="content">
            <h1><img src="images/dp.jpg" alt="image" width="13%" height="150vh"></h1>
            <h2>Hello, I'm Sarthak Tiwari </h2>
            <h3>Student</h3>
        </div>    
</body>
</html>

<!---
wigglwiggle/wigglwiggle is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
CSS:
*{
    margin:0;
    padding: 0;
    font-family: sans-serif;
    }
    
    
    .banner{
        width: 100%;
        height: 240vh;
        background-image: linear-gradient(rgba(0, 0, 0, 0.867),rgba(0, 0, 0, 0)),url(images/logo_transparent.png);
        background-size: cover;
        background-position: center;

    }
    .navbar{
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;

    }
    
    
    .navbar ul li{
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
    }
    .navbar ul li a{
        text-decoration: none;
        color: #fff;
        text-transform: uppercase;
    }
    .navbar ul li::after{
        content: '';
        height: 3px;
        width: 0%;
        background: #009688;
        position: absolute;
        left: 0;
        bottom: -10px;
        transition: 0.3s;

    }
    .navbar ul li:hover::after{
        width: 100%;

    }
    .content{
        width: 100%;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        text-align: center;
        color: white;
        font: bold;
    }
    img{
        border-radius: 50%;
        border-style: double;
        border-color: black;
    }
    .content h1{
        margin-top: 80px;


    }
    .content h2{
        margin: 20px auto;
        font-weight: 100;
        line-height: 25px;
        font-size: xx-large;
        font: bolder;
    }
    .content h3{
        margin: 30px auto;
        font-weight: 100;
        line-height: 25px;
        font:bold;
        font-size: medium;
    }
   
    
    
   
        

