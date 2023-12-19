# Ex.07 Software Product Company Website
## Date:

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

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(96, 153, 90, 0.75),rgba(102, 158, 93, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:  #2ba733;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background:  #2ba733;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:  #2ba733;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(31, 122, 41);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid  #2ba733;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color:  #2ba733;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid  #2ba733;
                color:  #2ba733;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid  #2ba733;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color:  #2ba733;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid  #2ba733;
                color: #2ba733;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {   

            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">GREENGROWERS</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Eco-Friendly Company </h2>
                <br>
                <p> Welcome to GREENGROWERS,This Garment Has Been Made With Organic Cotton Or Recycled Fibres.Our Motive Is To Have A Healthy And Friendly Environment To us And The Future Generations.Thanks For Helping To Protect Our Planet!</p>
              
<br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by ZAFREEN J (23012754) </center>
    </footer>
</body>
</html>

products.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(105, 153, 109, 0.75),rgba(85, 180, 90, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product {
                border: 1px;
                padding: 10px;
                color: rgb(10, 171, 42);
                background-color: #13a12f;
                border-radius: 30px;
            }
            .logo {
                color: #17c453;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(27, 164, 57, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #309d33;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color:  rgb(243, 249, 243);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(10, 85, 17);
                background-color: #075312;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 100px;
                border-radius: 70px;
            }
            .container .box-container .box h3 {
                color: #1fa131;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color:white (245, 248, 245);
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color: #97cb9a;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">GREENGROWERS</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="pic 1.jpeg" alt="">
                    <h3>Paper Bags </h3>
                    <p> Significantly less ecosystem impact than plastic bags. </p>
                </div>
                <div class="box">
                    <img src="pic 2.jpeg" alt="">
                    <h3> Cork </h3>
                    <p> Impermeable to liquids,gases and compressible. </p>
                </div>
                <div class="box">
                    <img src="pic 3.jpeg" alt="">
                    <h3> ToothBrush </h3>
                    <p> Natural,Renewable and Sustainable resources. </p>
                </div>
                <div class="box">
                    <img src="pic 4.jpeg" alt="">
                    <h3> Cups </h3>
                    <p> Compostable and biodegradable. </p>
                </div>
                <div class="box">
                    <img src="pic 5.jpeg" alt="">
                    <h3> Coconut Bowls </h3>
                    <p> Suitable for both cold and warm foods. </p>
                </div>
                <div class="box">
                    <img src="pic 6.jpeg" alt="">
                    <h3> Baskets  </h3>
                    <p> Traditionally constructed from stiff fibres. </p>
                </div>
                <div class="box">
                    <img src="pic 7.jpeg" alt="">
                    <h3> Eco Straws  </h3>
                    <p> Helps to reduce the number of microplastics. </p>
                </div>
                <div class="box">
                    <img src="pic 8.jpeg" alt="">
                    <h3> Eco Plates </h3>
                    <p> Friendly alternatives to disposable plastic. </p>
                </div>
                <div class="box">
                    <img src="pic 9.jpeg" alt="">
                    <h3> Cotton Pads</h3>
                    <p> Helpful for Medical or Cosmetic Purposes. </p>
                </div>
                <div class="box">
                    <img src="pic 10.jpeg" alt="">
                    <h3> Cloth Bag </h3>
                    <p> Cost-effective and versatile. </p>
                </div>>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by ZAFFREEN J(23012754) </center>
    </footer>
</body>
</html>

peoples.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(139, 193, 139, 0.75),rgba(134, 175, 126, 0.75)),url(background1.jpeg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: rgb(15, 135, 15);
                border-radius: 30px;
            }
            .logo {
                color: rgb(14, 159, 14);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(90, 171, 101, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: rgb(27, 147, 27);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: rgb(15, 175, 15);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: rgb(12, 135, 12);
            }
            footer {
                background-color: rgb(17, 156, 17);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">GREENGROWERS</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="pic - Copy.jpg"> </td>
                    <td> <img src="akshara1.jpeg"> </td>
                    <td> <img src="Ranir Kapur.jpeg"> </td>
                    <td> <img src="Murnal takur.jpeg"> </td>
                    <td> <img src="kalidas.jpeg"> </td>
                </tr>
                <tr align="center">
                    <th> ZAFREEN JAGIR</th>
                    <th> AKSHARA </th>
                    <th> RANBIR KAPOOR </th>
                    <th> MURUNAL TAKUR </th>
                    <th> KALIDAS </th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by ZAFREEN J (23012754) </center>
    </footer>
</body>
</html>

contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(121, 185, 128, 0.75),rgba(130, 181, 129, 0.75)),url(background1.jpeg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-contact {
                border: 1px;
                padding: 10px;
                color: rgb(9, 78, 9) ;
                background-color: #239e23;
                border-radius: 30px;
            }
            .logo {
                color: #12ba36;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(8, 85, 8) ;
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(7, 67, 7) ;
            } 
            ::placeholder {
                color: rgb(15, 101, 15) ;
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(9, 94, 8) ;
                border-radius: 10px;
                background: #099828;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(7, 83, 10) ;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(12, 99, 12) ;
                background-color: #1ab352;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(7, 111, 7) ;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid #20b310;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(7, 85, 20);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid  rgb(16, 108, 16) ;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(10, 110, 22) ;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color:  rgb(12, 110, 12) ;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid  green ;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color:  green ;
                border-radius: 30px;
                background: #0eba1d;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color:  rgb(248, 250, 248) ;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color:  rgb(9, 77, 9) ;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #f4f6f4;
                font-size: 20px;
            }
            footer {
                background-color: #0d9d1b;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">GREENGROWERS</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : No.10,kaidamillath Street,chetpet road,Thiruvannamalai </p>
                <p> <span>Email</span> : zafreen9944@gmail.com </p>
                <p> <span>Phone</span> : 9944262672 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by ZAFREEN J(23012754) </center>
    </footer>
</body>
</html>

```

## OUTPUT:
![Screenshot (42)](https://github.com/ZafreenJagir/softweb/assets/144870573/4561b1fc-3703-4357-9a31-df42e2d0c019)
![Screenshot (43)](https://github.com/ZafreenJagir/softweb/assets/144870573/9b426d5f-6805-4437-a7b1-9a9d6fe6d192)
![Screenshot (44)](https://github.com/ZafreenJagir/softweb/assets/144870573/a58092dd-c519-4641-a3e5-024e9ceeede8)
![Screenshot (45)](https://github.com/ZafreenJagir/softweb/assets/144870573/f63d8507-1236-402a-98e1-8c5f9d79a220)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
