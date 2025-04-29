# Ex.06 Book Front Cover Page Design
# Date:29/4/25
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
~~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: radial-gradient(circle, #ffd700, #ff8c00);
        }
        .book-cover {
            width: 350px;
            height: 500px;
            background: linear-gradient(135deg, #5a1a1a, #a52a2a);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border-radius: 15px;
            box-shadow: 10px 10px 25px rgba(0, 0, 0, 0.5);
            text-align: center;
            font-family: 'Georgia', serif;
            border: 7px solid gold;
            position: relative;
            overflow: hidden;
            padding: 20px;
        }
        .book-cover img {
            width:60%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .author-img {
            width: 15px;
            height: 15px;
            border-radius: 5px;
            border: 3px solid gold;
            margin-top: 5px;
        }
        .title {
            font-size: 30px;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.6);
        }
        .author {
            font-size: 22px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <img src="logo 1.jpg  alt="">
        <div class="title">Web Application Development</div>
        <div class="author">by PRADEEP.B</div>
        <img class="author-img" src="web ex-6.jpg" alt="" >
    </div>
</body>
</html>
~~~~
# OUTPUT:
![WhatsApp Image 2025-04-29 at 11 43 44_bf631e75](https://github.com/user-attachments/assets/d9d6ad96-14c4-4332-8047-8977e249a876)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
