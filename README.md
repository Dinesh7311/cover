# Ex.06 Book Front Cover Page Design
# Date: 17.12.2024
## AIM:
To design a book front cover page using HTML and CSS.

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
 cover.html


 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Page</title>
    <link rel="stylesheet" href="cove.css">
</head>
<body>
    <div class="book-cover">
        <div class="book-photo">
            <img src="OIP.jpg" alt="Book Image">
        </div>
        <h1 class="book-title">The Art of Web Design</h1>
        <h2 class="book-subtitle">A Complete Guide to HTML and CSS</h2>
        <p class="author">by Dinesh</p>
    </div>
</body>
</html>



cove.css

/* General reset for margin and padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
    font-family: Arial, sans-serif;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.book-cover {
    background: rgba(255, 255, 255, 0.9);
    border: 2px solid #333;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    text-align: center;
    padding: 30px;
    width: 350px;
    border-radius: 10px;
}

.book-photo img {
    width: 100%;
    height: auto;
    border: 3px solid #333;
    border-radius: 5px;
}

.book-title {
    font-size: 28px;
    font-weight: bold;
    color: #333;
    margin: 20px 0 10px;
}

.book-subtitle {
    font-size: 18px;
    color: #555;
    margin-bottom: 15px;
}

.author {
    font-size: 16px;
    font-style: italic;
    color: #777;
    margin-top: 10px;
}


## OUTPUT:

![alt text](<Screenshot 2024-12-17 135358.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
