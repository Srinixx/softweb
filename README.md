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
## index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOJOTECH</title>
    <style>
        *{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #0fe468;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: rgb(30, 255, 98);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:rgba(198, 215, 112, 0.805);
            height: 500px;        
            overflow: hidden;
            line-height: 30px;
        }

        h1,h2{
            text-align: center;
        }

        .image1 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
        }

        .image3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .image2  img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        footer{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman',times new roman, times new roman;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="logo.jpg" alt="logo" border="2"></a>
        </div>
        <a class ="cname"><h1>MOJOTECH</h1></a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <h1>MojoTech is a premier product development and application modernization agency.</h1>
        <h2>Integrating engineering, strategy, and design, MojoTech transforms enterprises and scales technology disruptors into leading digital businesses.</h2>
        <div class="image1">
            <img src="mojotech1.jpg" alt="image1">
        </div>
        <div class="image2">
            <img src="mojotech2.jpg" alt="image2">
        </div>
        <div class="image3">
            <img src="mojotech3.jpg" alt="image3">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 MOJOTECH. All rights reserved.</p>
    </footer>
</body>
</html>
```
## product.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOJOTECH</title>
    <style>
        *{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #4cc466;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: white;
        }

        header a.active {
        background-color: rgb(30, 255, 41);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .cname{
            padding-top: 12px;
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: rgba(186, 215, 112, 0.805);
            height: 1500px;        
            overflow: hidden;
            line-height: 30px;
        }
        
        .prod1 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 280px;
        }

        .prod2 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        .prod3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .prod4 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
        }

        .prod5 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
            left: 650px;
        }

        .prod6 img{
            padding: 50px;
            height: 300px;
            width: 500px;
            position:absolute;
            top: 740px;
            left: 1100px;
        }

        .quote{
            text-align: center;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 40px;
            color: #50c44c  ;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>MOJOTECH</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a class="active" href="product.html">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="quote">
            <h3>Software Development & Design for Innovative Companies</h3>
        </div>
        <div class="prod1">
            <img src="soft1.jpg" alt="prod3">
        </div>
        <div class="prod2">
            <img src="soft2.png" alt="prod2">
        </div>
        <div class="prod3">
            <img src="soft3.png" alt="prod1">
        </div>
        <div class="prod4">
            <img src="soft4.png" alt="prod4">
        </div>
        <div class="prod5">
            <img src="soft5.jpeg" alt="prod5">
        </div>
        <div class="prod6">
            <img src="soft6.jpg" alt="prod6">
        </div>
    </section>
    <footer>
        <p>&copy; 2023 MOJOTECH. All rights reserved.</p>
    </footer>
</body>
</html>
```
## people.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOJOTECH</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #4cc474;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color:white;
        }

        header a.active {
        background-color: rgb(30, 255, 34);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:rgba(206, 215, 112, 0.805);
            overflow: hidden;
            line-height:normal;
        }
        .person {
            text-align: center;
        }

        p{
            font-size: 20px;
        }
        .person img {
            display:grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            margin: 0 auto;
            height: 340px;
            padding-top: 40px;
        }

        .person p.name {
            font-weight: bold;
            margin-top: 10px;
            color:white;
        }

        .person p.desig {
            font-weight: bold;
            margin-top: 10px;
            color:white;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:white  ;
        }
        
        footer{
            font-size: 40px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>MOJOTECH</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a class="active" href="people.html">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>MEET THE BOARD MEMBERS</h3>
        </div>
        <div class="image">
            <div class="person">
                <img src="212221040126.jpg" alt="Prakash">
                <p class="name">PRAKASH </p>
                <p class="desig">CEO</p>
            </div>
            <div class="person">
                <img src="212221040121.jpeg" alt="Pinto ponnachan">
                <p class="name">PINTO PONNACHAN</p>
                <p class="desig">GENERAL MANAGER</p>
            </div>
            <div class="person">
                <img src="212221040178.jpg" alt="Vijay Kumar">
                <p class="name">VIJAY KUMAR</p>
                <p class="desig">HR MANAGER</p>
            </div>
            <div class="person">
                <img src="srini.jpeg" alt="Srinivash">
                <p class="name">SRINIVASH</p>
                <p class="desig">MARKETING HEAD</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 MOJOTECH. All rights reserved.</p>
    </footer>
</body>
</html>
```
## contact.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOJOTECH</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #4cc47e;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: rgb(30, 255, 64);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: rgba(179, 215, 112, 0.805);
            overflow: hidden;
            line-height:normal;
        }
        
        .contact-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
        }

        .contact-image {
            flex: 1;
            text-align: center;
        }

        .contact-image img {
            max-width: 100%;
            height: auto;
        }

        .contact-details {
            flex: 1;
            padding: 50px;
            font-size: 25px;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:white;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>MOJOTECH</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a class="active" href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>CONTACT US</h3>
        </div>
        <div class="contact-container">
            <div class="contact-image">
                <img src="contact.jpg">
            </div>
            <div class="contact-details">
                <p><strong>Email:</strong> hugh@mojotech.com</p>
                <p><strong>Phone:</strong> +1 (888) 912-1029</p>
                <p><strong>Address:</strong> New York, NY,79 Madison Ave,8th Floor,New York, NY 10016</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 MOJOTECH. All rights reserved.</p>
        </footer>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/Srinixx/softweb/assets/132982592/be43cf4f-d1d4-48a6-a877-80fb736c9a5f)
![people](https://github.com/Srinixx/softweb/assets/132982592/7344bd71-a438-4992-9be3-904c6cac775a)
![image](https://github.com/Srinixx/softweb/assets/132982592/29efb6a5-0d75-4c97-b9bd-0d9068f68377)
![image](https://github.com/Srinixx/softweb/assets/132982592/6b7a6e54-549c-4bda-b31c-e0516400010f)
![image](https://github.com/Srinixx/softweb/assets/132982592/c52db378-5f19-4d5d-a912-e8f8243d42f5)







## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
