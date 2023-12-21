# Ex.07 Software Product Company Website
## Date:15-12-23

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:lightblue;
            color:purple;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:60%;
        }
        a{
            color:white;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
   }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: gold;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:lightblue;
        
        }
        .heading1{
            color:navy;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:black;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 .bottomdiv{
            background-color:lightblue;
            color:navy;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 72px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                VOICIFY AI
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
 </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"AI is a mirror,reflecting not only
our intellect,but our values
and fears"<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                            Username:
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            Password:
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
<input type="submit" value="LOGIN" style="background-color: navy; color:gold;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Anbu Vinotha (23013363)</p>
    </div>
</body>
<html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:lightblue;
            color:navy;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:navy;
        }
        li:hover{
            color:navy;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
 }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:lightblue;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:navy;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
 .bottomdiv{
            background-color:lightblue;
            color:navy;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 180px;

        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">VOICIFY AI</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>b
        <div class="product">
 <div class="box">
                <img src="smart assistant.jpeg">
                <h1>SMART ASSISTANT</h1>
                <p> A virtual assistant (VA) is a software agent that can perform a range of tasks or services for a user based on user input such as commands or questions, including verbal ones. Such technologies often incorporate chatbot capabilities to simulate human conversation, such as via online chat, to facilitate interaction with their users.</p>
            </div>
            <div class="box">
                <img src="self driving car.jpeg">
                <h1>SELF DRIVING CAR</h1>
                <p>Self-driving cars can predict the conduct of pedestrians and other vehicles through AI. The vehicle is equipped with predictive modeling and analytics capability to anticipate such problems and prevent them from occurring.</p>
            </div>
            <div class="box">
                <img src="manufacturing robot.jpeg">
                <h1>MANUFACTURING ROBOT</h1>
                <p>
Using AI, robots and other next-generation technologies, a lights-out factory operates on an entirely robotic workforce and is run with minimal human interaction. Manufacturers can potentially save money with lights-out factories because robotic workers don't have the same needs as their human counterparts.</p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Anbu Vinotha (23013363)</p>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
  }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:yellow;
        }
        .bottomdiv{
            background-color:teal;
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 163px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
   }
        b,p{
            color:white;
            text-align: center;
        }
    </style>3
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">VOICIFY AI</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="mypic1.jpg" class="MyPic">
                </td>
                <td>
   <img src="Christian Bale.jpeg" class="Christian Bale">
                </td>
                <td>
                    <img src="Robert Pattinson.jpeg" class="Robert Pattinson">
                </td>
                <td>
                    <img src="Andrew Russell Garfield.jpeg" class="Andrew Russell Garfield">
                </td>
                <td>
                    <img src="Heath Ledger.jpeg" class="Heath Ledger">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Anbu Vinotha</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Christian Bale</b>
                    <p>CEO,Co-Founde</p>
                </td>
                <td>
                    <b>Robert Pattinson</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Andrew Russell Garfield</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Heath Ledger</b>
 <p>Asst.Director</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Anbu Vinotha (23013363)</p>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
  }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:teal;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: yellow;
        }
  .table1{
            color:white;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: yellow;
        }
        .table2{
            color:white;
            font-size: large;
            background-color:rgb(95, 92, 92);
            border-radius: 5px;
            border-style:dotted;
            border-color: yellow;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:teal;
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 24px;

        }
 </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">VOICIFY AI</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        Asian Garderns,Door No:309,2nd-Floor,253A/108, M.T.H Road, Villivakkam,Chennai-600049. 
                    </td>
                </tr>
                <tr>
<td>
                        LANDMARK :
                    </td>
                    <td>
                        near padiflyover, next to sidco bus stop.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        voicifyai@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9443333483
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: lightskyblue; color: black;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed and Developed by Anbu Vinotha (23013363)</p>
        </div>
    </div>
</body>
</html>
```
## OUTPUT:
![Alt text](<Screenshot (23).png>)
![Alt text](<Screenshot (26).png>)
![Alt text](<Screenshot (25).png>)
![Alt text](<Screenshot (27).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
