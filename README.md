# Ex.05 Book Cover Page Design
## Date:24.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
Book.html
<html>
<head> 
    <title>About the Book</title>
    <link rel="stylesheet"  href="style.css" >
       
</head>
<body>

<div class="card">
    <h2>About the Book</h2>

    <p class="book-text">
        I am a student who is interested in learning new things, especially in technology and programming. 
        I enjoy improving my skills and exploring creative ideas.
    </p>

    <div class="quote">
        
        "I am a motivated student with a keen interest in computers and Python programming. 
        I like solving problems and learning new concepts."
    </div>

    <div class="author-box">
        <img src="image.v.jpeg" alt="author">
        <div class="author-text">
            <strong>E.Vamsi Krishna</strong><br>
            I am passionate about technology and artificial intelligence, 
            and I enjoy learning programming to build useful and innovative solutions.
        </div>
    </div>

    <div class="footer">
        <span>SEC Publishers<br>Printed in India</span>
        <span>Price: 499</span>
    </div>
</div>
</body>
</html>

style.css

body {
            font-family: Arial, sans-serif;
            background: rgb(243, 240, 240);
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .card {
            width: 420px;
            background: linear-gradient(to bottom, rgb(239, 145, 13));
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(14, 13, 13, 0.15);
        }

        h2 {
            color: rgb(12, 12, 12);
            margin-bottom: 10px;
        }

        .book-text {
            font-size: 14px;
            line-height: 1.6;
            color: rgb(14, 14, 14);
        }

        .highlight {
            color: rgb(6, 98, 144);
            font-weight: bold;
        }

        .quote {
            margin-top: 15px;
            padding: 10px;
            background: rgb(240, 240, 237);
            font-style: italic;
            font-size: 13px;
        }

        .author-box {
            display: flex;
            align-items: center;
            background: rgb(12, 223, 202);
            margin-top: 20px;
            padding: 10px;
            border-radius: 6px;
        }

        .author-box img {
            width: 60px;
            height: 70px;
            border-radius: 50%;
            margin-right: 10px;
        }

        .author-text {
            font-size: 13px;
        }

        .author-text strong {
            color: rgb(157, 157, 8);
        }

        .footer {
            margin-top: 20px;
            background: rgb(236, 5, 5);
            color: rgb(247, 243, 243);
            padding: 10px;
            border-radius: 6px;
            display: flex;
            justify-content: space-between;
            font-size: 12px;
        }
    
```

## OUTPUT:
![alt text](<1 src.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
