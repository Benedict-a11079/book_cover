# Ex.06 Book Front Cover Page Design
# Date:01.12.2025
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
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>What Happens After the Sun Dies</title>
<style>
body{
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#000;
    font-family:Arial, Helvetica, sans-serif;
}
.cover{
    width:420px;
    height:600px;
    background:linear-gradient(180deg,#020024,#090979,#000);
    color:white;
    padding:40px;
    box-sizing:border-box;
    border:2px solid #444;
}
.line{
    width:60px;
    height:4px;
    background:#f9c74f;
    margin-bottom:20px;
}
h1{
    font-size:30px;
    line-height:1.3;
}
h2{
    font-size:14px;
    color:#ccc;
    margin-top:15px;
}
.footer{
    position:absolute;
    bottom:40px;
    font-size:14px;
    color:#f9c74f;
}
</style>
</head>
<body>

<div class="cover">
    <div class="line"></div>
    <h1>WHAT HAPPENS<br>AFTER THE SUN DIES</h1>
    <h2>The Final Fate of Our Solar System</h2>

    <div class="footer">By Benedict</div>
</div>

</body>
</html>

# OUTPUT:
<img width="972" height="849" alt="Screenshot 2025-12-27 222817" src="https://github.com/user-attachments/assets/f4f135ac-27a4-4db0-9abf-5b58a13936b2" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
