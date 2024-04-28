# Ex.07 Software Product Company Website
## Date:28.04.2024

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
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100%;
                background-image: url("bb ai.jpg");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#f775db;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            ::placeholder {
                color: black;
            }
            form button {
                border: 2px solid#f775db;
                outline: none;
                padding: 5px 20px;
                color: black;
                border-radius: 10px;
                background:#f775db;
                cursor: pointer;
            }
            form button:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid #f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #f775db;
                border-radius: 30px;
                background-color:black;
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            
            .people {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .product:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 

            .contact {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: white;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text h4 {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color:#f775db;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">BLACKBOX AI</h1>
            <ul>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/home.html" class="home" id="bg-"home"> Home </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Products </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/people.html" class="people"> Creators </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us</a></li></button>
            </ul>
            
        </div>
        <div class="content">
            <div class="text">
                <h2> BLACKBOX AI</h2>
                <br>
                <p><h4><b>Hello from BLACKBOX AI! Welcome to our coding platform.We're thrilled to have you here.At BLACKBOX AI, we're committed to providing a vibrant community and top-notch resources for all your coding needs.Whether you're a beginner or an experienced coder, there's something here for everyone.Feel free to explore our tutorials, join coding challenges, and connect with fellow enthusiasts.Together, let's unlock the power of code and build amazing things!</b></h4> </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by AADITHYA R (212223240001) </center>
    </footer>
</body>
</html>

product.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("bb ai.jpg");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#f775db;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            ::placeholder {
                color: black;
            }

            .home {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .people {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid #f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #f775db;
                border-radius: 30px;
                background-color:black;
                text-decoration: none;
                
            }
            .product:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .contact {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 80px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid gray;
                padding: 50px 30px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:white;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: red;
                font-size: 15px;
                line-height: 1.5;
            }
            footer {
                background-color:#f775db;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">BLACKBOX AI</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> Creators </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us </a></li></button>
            </ul>
            
        </div>
        <div class="container">
            <div class="box-container">
              
                
                <div class="box">
                    <h3> Fusion Time </h3>
                    <p> Plot high-performance time-series visualizations. </p>
                </div>
                <div class="box">
                    <h3> Yellowfin BI and Analytics </h3>
                    <p> Powerful and flexible embedded analytics platform. </p>
                </div>
                <div class="box">
                    <h3> WebFlow Pro Studio </h3>
                    <p> Rapid low-code app creation. </p>
                </div>
                <div class="box">
                    <h3> DevInspect Test Kit </h3>
                    <p> Automated testing and debugging. </p>
                </div>
                <div class="box">
                    <h3> Fusion Grid </h3>
                    <p> Rocket fuel for data intensive applications with integrated charting. </p>
                </div>
                <div class="box">
                    <h3> SiteSphere CMS </h3>
                    <p> Streamlined web content management. </p>
                </div>
                <div class="box">
                    <h3> FusionCharts Suite XT </h3>
                    <p> Platform for data-driven maps. </p>
                </div>
                <div class="box">
                    <h3> CodeBoost Accelerator </h3>
                    <p> Optimized code efficiency tools. </p>
                </div>
                <div class="box">
                    <h3> WebScale Pro Manager </h3>
                    <p> Seamless high-traffic handling. </p>
                </div>
                <div class="box">
                    <h3> DevSphere IDE Suite </h3>
                    <p> Integrated tools for developers. </p>
                </div>
                <div class="box">
                    <h3> Fusion Export </h3>
                    <p> Export full Dashboards as PDFs for use in reports and emails. </p>
                </div>

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AADITHYA R (212223240001) </center>
    </footer>
</body>
</html>


people.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("bb ai.jpg");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#f775db;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            gray;
            } 
            ::placeholder {
                color: black;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .people {
                margin: -5px -5px;
                border: 2px solid #f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #f775db;
                border-radius: 30px;
                background-color:black;
                text-decoration: none;
                
            }
            .people:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
                
            }
            .product:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .contact {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: gray;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid gray;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color:#f775db;
            }
            footer {
                background-color:#f775db;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">BLACKBOX AI</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> Creators </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us </a></li></button>
            </ul>
            
        </div>
        <div class="image">
            <table cellspacing="100"> 
                <tr align="center">
                    <td> <img src="AADITHYA IMG.jpg"> </td>
                    <td> <img src="midhun.jpg.png"> </td>
                    <td> <img src="rohith prem.jpg"> </td>
                    <td> <img src="vikash.jpg.png"> </td>
                    <td> <img src="Kim jong un.jpg.png"> </td>
                </tr>
                <tr align="center">
                    <th> Aadithya R</th>
                    <th> Midhun Somu S</th>
                    <th> Rohith Prem S </th>
                    <th> Vikaash K S </th>
                    <th> Kim Jong Un</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> Senior Developer</td>
                    <td> Director </td>
                    <td> Designer</td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AADITHYA R (212223240001) </center>
    </footer>
</body>
</html>

contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("bb ai.jpg");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#f775db;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            ::placeholder {
                color: white;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .people {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid#f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: black;
                border-radius: 30px;
                background-color:#f775db;
                text-decoration: none;
                
            }
            .product:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .contact {
                margin: -5px -5px;
                border: 2px solid #f775db;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #f775db;
                border-radius: 30px;
                background-color:black;
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
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
                border: 3px solid #f775db;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 400px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid#f775db;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 450px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 30px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid #f775db;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 22px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 10px 43px;
                position: relative;
                top: 30px;
                font-size: 22px;
                left: 0px;
                border: 1px solid #f775db;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: black;
                border-radius: 30px;
                background:#f775db;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-1 form button:hover {
                border: 2px solid#f775db;
                color:#f775db;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                font-size: large;
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color:#f775db;
                font-size: 20px;
            }
            footer {
                background-image:#f775db;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">BLACKBOX AI</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> Creators </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us  </a></li></button>
            </ul>
            
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1>  Contact Us </h1>
                        <input type="text" placeholder="Enter Your Name">
                        <br>
                        <input type="email" placeholder="Enter Your Email">
                        <br>
                        <textarea rows="0" cols="20" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit" align="center"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : No.14/175,Venkateshwara Nagar ,Pozhichalur,Chennai-600074 </p>
                <p> <span>Email</span> : aadithya.ramku@gmail.com </p>
                <p> <span>Phone</span> : 9342562668 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AADITHYA R(212223240001) </center>
    </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (41).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
