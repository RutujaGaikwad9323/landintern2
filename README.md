
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
            box-sizing: border-box;
            font-family: 'Anton', sans-serif;
        }
        .container{
            width: 100%;
            min-height: 100vh;
            background-image: url(bag.webp);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
        }
        .row{
            width: 100%;
            padding: 0px 80px;

        }
        .navbar{
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 0px;
            color: black;
            position: relative;
            z-index: 1;
        }
        .navbar ul{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 10px;
            color:white;
        }
        .navbar ul li{
            list-style: none;
        }
        .navbar ul li a{
            color:white;
            padding: 10px 18px;
            border-radius: 5px;
            font-family: sans-serif;
            font-size: 16px;
            text-decoration: none;
        }
        .navbar ul li a:hover{
            background-color: #5d885d;
            color: black;
         }
         .navbar h1{
            color:black;
            font-size: 35px;
            font-weight: 500;
            text-transform: uppercase;
            margin-top: 10px;
         }
         .content{
            width: 100%;
            min-height: 100vh;
            position: absolute;
            top: 0;
            left: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
         }
         .content h1{
            font-size: 45px;
            color:white ;
            font-weight: 400;
         }
         .content h2{
            font-size: 35px;
            color: aqua;
         }
         .content p{
            font-size: 17px;
            color:whitesmoke;
            font-family: 'Courier New', Courier, monospace;
         }
        .h2 a img{
            margin-bottom: 0px;
            padding-bottom: 0.5px;
         }
         
    </style>
</head>
<body>
    <div class="container">
        <div class="row">
        <nav class="navbar">
          <h1>Logo
            <a href="https://google.com"><img src="https://affiliateconnexion.com/wp-content/uploads/2020/04/crowd1-logo.png" height="100"></a>
          </h1>
          <h2 align="left">
            <a href="https://google.com"><img src="https://webstockreview.net/images/diploma-clipart-high-school-6.png" height="200"></a>
          </h2>
          <ul>
            <li><a href=""><b>Interncrowd</b></a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Courses</a></li>
            <li><a href="">Services</a></li>
            <li><a href="">About us</a></li>
            </ul>
        </nav>
        </div>
        <br>
        <br>                Interncrowd
           </h1>           <br>
            <br>
            <h2 align="center">
            Web Development
            <br><p>
       We offer,Web Development intership for practical experience<br>
       of real world and an basic to advance introduction to <br>
       creating web-based projects.
            </p>
            
        </h2>
            <br>
            <footer>
                <input type="submit" value="Apply now"> 
            </footer>
        </div>
    </div>
</body>
</html>

