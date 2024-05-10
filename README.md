# Ex.07 Software Product Company Website
## Date: 10-5-24

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
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:rgb(212, 65, 89);
            color:white;
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
            padding:20px;
            text-align: center;
        }
        
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: rgb(214, 152, 152);
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:rgb(135, 113, 133);
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:rgb(212, 65, 89);
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 850px;
        }
        .box{
            text-align: center;
        }
        .bottomdiv{
            background-color:rgb(212, 65, 89);
            color:white;
            text-align: center;
            position:fixed;
            bottom:0;
            width:100%;

        }
        table{
            margin-left: 300px;
        }
    </style>
</head>
<body background="bgp1.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                ByteCraft Innovations
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="Search">
    </div>
        <div><pre class="heading2"><b>
"Advanced Software Made Simple"<b></pre></div>
    <br>
    <br>
    <br>
    <br>
    <div><pre class="heading2"><b>
        "Crafting Code, Shaping Solutions"<b></pre></div>
        <div class="edge">
            <div class="box">
                <div class="login">
                    <form>
                        <h3>Login Here</h3>
                        <input type="text" placeholder="Username or Email"><br><br>
                        <input type="password" placeholder="Password"><br><br><br>
                        <button>Login</button>
                        <h5> Don't have an account?</h5><br>
                        <div class="Signup"><b><a href="" >Sign up here</a> </b> </div>   
                        
            
                </div>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Developed by Beatrice Thomas </p>
    </div>
</body>
<html>

person.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(212, 65, 89);
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
            color: rgb(190, 92, 109);
        }
        .bottomdiv{
            background-color:rgb(212, 65, 89);
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
            text-align:center;
            
        }
        b,p{
            color:purple;
            text-align: center;
        }
    </style>
</head>
<body background="bgp1.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1"> ByteCraft Innovations </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PEOPLE</h1>
        <table class="person">
            <tr>
                <td>
                    <img class="small border" src="mypic1.jpg" width="500px">
                </td>
                <td>
                    <img  class="small border" src="pic1.png"  width="500px">
                </td>
                <td>
                    <img class="small border" src="pic2.png"  width="500px">
                </td>
                <td>
                    <img class="small border" src="pic3.png" width="500px">
                </td>
                <td>
                    <img class="small border" src="pic4.png" width="500px">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Beatrice</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b> Rapunn</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b> Belle </b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b> Moana</b>
                    <p>CEO Director</p>
                </td>
                <td>
                    <b> Elsa</b>
                    <p>Asst.Director</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
        <p> Developed by  Beatrice </p>
    </div>
</body>
</html>

contactus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ContactUs</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(212, 65, 89);
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
            background-color:rgb(165, 93, 105);
            cursor:pointer;
        }
        a{
            color:white;
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
            color:rgb(131, 49, 131);
        }
        .table1{
            color:rgb(197, 48, 48);
            font-size: large;
            
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:rgb(197, 48, 48);
        }
        .table2{
            color:white;
            font-size: large;
            background-color:rgb(50, 119, 159);
            border-radius: 5px;
            border-style:dotted;
            border-color: white;
            margin-left:300px;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:rgb(212, 65, 89);
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="bgp1.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1"> ByteCraft Innovations </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
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
                       No-8, Rosefarm Street,Tharamani,Chennai-600143
                    </td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        Near Germanus Hotel
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        byteccraftinnovations@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9789557640
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
                            <input type="name" placeholder="Enter Name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <div style="text-align:center;">
                            <input type="submit" style="background-color: rgb(200, 222, 236); color: black;" >
                            </div>
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Developed by Beatrice <p>
        </div>
    </div>
</body>
</html>


product.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(212, 65, 89);
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
            color:white;
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
            border-color:rgb(143, 44, 95);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color: rgb(245, 133, 152);
            cursor:pointer;
        }
        a{
            color:white;
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
            color:rgb(209, 45, 45);
        }
        .bottomdiv{
            background-color:rgb(212, 65, 89);
            color:white;
            text-align: center;
            position:fixed;
            bottom:0;
            width:100%;
        }
    </style>
</head>
<body background="bgp1.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1"> ByteCraft Innovations </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
                <img src="adobe.png" width="150px">
                <h1>Adobe Creative Cloud Suite</h1>
                <p>Photoshop, Illustrator & More.</p>
            </div>
            <div class="box">
                <img src="maple.png" width="260px">
                <h1>Maple</h1>
                <p>Statistical Package</p>
                </div>
            <div class="box">
                <img src="sas.png" width="245px">
                <h1>SAS</h1>
                <p>Statistical Analysis System.</p>
                </div>
            <div class="box">
                <img src="matlab.png" width="180px">
                <h1>Matlab</h1>
                <p>Coding Software</p>
                </div>
            <div class="box">
                <img src="pycharm.png" width="120px">
                <h1>Jetbrains Pycharm</h1>
                <p>Computer Programming</p>
                </div>
            <div class="box">
                <img src="ofc.png" width="360px">
                <h1>Microsoft Office Suite</h1>
                <p>Word, Powerpoint, Excel & More.</p>
                </div>
        </div>
    </div>
    <div class="bottomdiv">
        <p> Developed by Beatrice</p>
    </div>
</body>
</html>
```

## OUTPUT:

![home](https://github.com/Beatricethomas/softweb/assets/140035214/61c4f073-3f17-4f57-9989-278d8e43ad55)

![people](https://github.com/Beatricethomas/softweb/assets/140035214/4c9005ce-e446-473e-980c-414150a6981f)

![pro](https://github.com/Beatricethomas/softweb/assets/140035214/4d7c8fb6-9527-4660-873f-e5d907b30816)

![contact](https://github.com/Beatricethomas/softweb/assets/140035214/58b7676d-f0a9-4b40-b9f1-b8ef39837a53)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
