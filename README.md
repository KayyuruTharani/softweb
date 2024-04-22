# Ex.07 Software Product Company Website
## Date:23-04-2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

# web.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myfirstwebsite</title>
    <style>
        h1 {
            color: black;
            font-size: 45px;
            
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: rgb(197, 233, 234);
            margin: 0;
           
}
        

        .navbar ul {
            list-style-type: none;
            background-color: rgb(45, 162, 240);

        }

        .navbar a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: lightblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: black;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 55px;
            background-color: white;
            margin-left: 10px;
            
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: white;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: black;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(43, 144, 226);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: silver;
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color:hotpink;
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: pink;
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color:rgba(0, 0, 0, 0.781);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color: hotpink;
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(133, 155, 155);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .t{
            text-align: center;
            font-size: larger;
        }
        .d{
            margin-left: 10px;
            color: blue;
        }

    </style>
</head>

<body>
    <header>
        <h2>START CODING</h2>
    </header>
    <nav class="navbar" >

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="index.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1 align="top">
        <div class="first">Learn to Code
            </div>
        <div class="second">With the world's largest Coding language learning website<br></div>
    
    </h1>
    <div class="d">
        <p> &nbsp;"Good websites are like crystal clear lakes-they allow users to see straight 
        to the bottom and navigate effortlessly."</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <img src="google.jpeg" width="25px">
                <img src="facebook.jpeg" width="25px">
                <img src="micro.jpeg" width="25px"
                
            </div>
            
        </form>
    </div>
    <footer class="t">
        Designed and Developed by KAYYURU THARANI &copy; 2024
    </footer>

</body>

</html>
```
# index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myfirstwebsite</title>
    <style>
        h1 {
            color: black;
            font-size: 45px;
          
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: rgb(197, 233, 234);
            margin: 0;
           
}
        

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 255, 255);

        }

        .navbar a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: lightblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: black;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 55px;
            background-color: white;
            margin-left: 10px;
            
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: white;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: black;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(43, 144, 226);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: silver;
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color:hotpink;
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: pink;
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color:rgba(0, 0, 0, 0.781);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color: hotpink;
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(133, 155, 155);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .t{
            text-align: center;
            font-size: larger;
        }
        .d{
            margin-left: 10px;
            color: blue;
        }

    </style>
</head>

<body>
    <header>
        <h2>START CODING</h2>
    </header>
    <nav class="navbar" >

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="index.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1 align="top">
        <div class="first">Learn to Code
            </div>
        <div class="second">With the world's largest Coding language learning website<br></div>
    </h1>
    <div class="d">
        <p> &nbsp;"Good websites are like crystal clear lakes-they allow users to see straight 
        to the bottom and navigate effortlessly."</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <img src="google.jpeg" width="25px">
                <img src="facebook.jpeg" width="25px">
                <img src="micro.jpeg" width="25px"
                
            </div>
            
        </form>
    </div>
    <footer class="t">
        Designed and Developed by KAYYURU THARANI &copy; 2024
    </footer>

</body>
</html>
```
# products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
       
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(197, 233, 234);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:whitesmoke;
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{
        background-color:black;
        height:30px;
        bottom: 0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .contain{
                position: absolute;
                top:12%;
                width:130px;
                height:750px;
                margin-left: 90px;
               margin-top: 30px;
                background-color:ghostwhite;
                font-size: larger;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                
                
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 18px;
                    padding-left: 10px;
                    padding:5px 20px 0px 15px ;
                    
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
                .m{
                    text-align: center;
                    font-size: large;
                }

    </style>
</head>
<body>
    <header>
        <h2>START CODING</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="Contact.html">Contact</a></li>
        <li><a href="jsg.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="index.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="webpic.jpeg" height="200px" width="200px">
                            <p><b>WEB DESIGN<br>&nbsp;&nbsp;AND&nbsp;DEVELOPMENT</b><br>
                                
                               
                
                        </p></td>
                        <td><img src="javascript.jpeg" height="200px" width="200px"><br>
                            <p><b>JAVASCRIPT&nbsp;</b><br>
                                
                                
                        </p></td>
                        <td><img src="python.jpeg" height="200px" width="200px"><br>
                            <p><b>PHYTHON <br>
                        
                        </p></td>
                        <td><img src="java.jpeg" height="200px" width="200px"><br>
                            <p><b>JAVA</b><br>
                               
                                
                        </p></td>
                        <td><img src="c++.jpeg" height="200px" width="200px"><br>
                            <p><b>C/C++</b><br>
                                
                                
                        </p></td>  
                    </tr>
                    <tr>
                        
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer class="m">
                Designed and Developed by KAYYURU THARANI &copy; 2024
                </footer>
               
</body>
</html>
```
# people.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 30px;
       
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(197, 233, 234);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color: white;        
        }
        .navbar a{
         color:rgb(0, 0, 0);
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: hotpink;
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:190px;
           height:190px;
           margin:10px
        }
        .border{
        border-width:2px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 70px;
            
        }
        .text{
            position:absolute;
            top:55%;
            margin-left:35px;
            font-size:20px;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
            font-size:20px;
        }
        .class{
            text-align: center;
            font-size: larger;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>START CODING</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="index.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="pic.jpg" width="500px">
            <img class="small border" src="madhu.jpg" width="500px" >
            <img class="small border" src="swathi.jpg" width="500px">
            <img class="small border" src="joshi.jpg" width="500px" >
            <img class="small border" src="mamatha.jpg" width="500px" >
            
        </div>
        <div class ="text">
            <table cellpadding="65">
                <tr class="head">
                    <th>THARANI</th>
                    <th>MADHURYA</th>
                    <th>SWATHI</th>
                    <th>JOSHITHA</th>
                    <th>MAMATHA</th>
                    
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="75">
                <tr>
                    <td>CEO</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO<br>Co-Founder</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CTO<br>Co-Founder</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CTO<br>Co-Founder</td>
                    <td>Director</td>
                    
                </tr>
            </table>
        </div>
      
            <footer class="class">
                Designed and Developed by KAYYURU THARANI &copy; 2024
                </footer>
               
</body>
</html>
```
# contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 40px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(197, 233, 234);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:rgb(244, 21, 210);
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height: 30px;
        bottom: 0;
        width: 100%;
        color: white;
        position: absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color:  black;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: wheat;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 5px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:black;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.2%;
            font-size: 20px;
            background-color: rgba(0, 0, 0, 0.781);
            padding:70px 250px 95px 147px ;
            margin-left: 840px;
            color: white;
            border: 4px;
            border-color: beige;
            border-style: solid;
        }
        .coform form{
            background-color:rgba(0, 0, 0, 0.781) ;
            color: aliceblue;
            top:44.3%;
            margin-left: 20px;
            padding:0px 282px 50px 0px;
            border: 4px;
            border-color: aliceblue;
            border-style: solid;
        }
        .u{
            text-align: center;
            font-size: larger;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>START CODING</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="index.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                
                <div class="coform">
                    <form>
                      <h3>&nbsp;Contact Us</h3>
                      <input type="text" placeholder="Your Name"><br><br>
                      <input type="text" placeholder="Your Email"><br><br>
                      <textarea rows="12" cols="66" >Your Message
                      </textarea><br>
                      <button id="submit">Submit</button>
                    </form>
                </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br0>
            <b>Address: </b>west street,manubolu,gudur,nellore dist,andhra pradesh-524405<br><br>
            <b>Email: </b>kayyurutharani@gmail.com<br><br>
            <b>Phone: </b>98456328223
        </div>
       
    </div>
                <footer class="u">
                    Designed and Developed by KAYYURU THARANI &copy; 2024
                    </footer>
                   
    </body>
    </html>
```

## OUTPUT:
![alt text](<Screenshot (403).png>)

![alt text](<Screenshot (404).png>)

![alt text](<Screenshot (405).png>)

![alt text](<Screenshot (406).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
