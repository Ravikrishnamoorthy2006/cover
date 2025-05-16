# Ex.06 Book Front Cover Page Design
## Date: 16.05.2025

Name : Ravikrishnamoorthy D

Register No : 212224040271

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

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Front Page</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Georgia', serif;
    }

    .front-page {
      background-image: url('cronaldo.jpg'); 
      background-size: cover;
      background-position: center;
      height: 100%;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    .book-title {
      font-size: 3em;
      font-weight: bold;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px #000;
    }

    .subtitle {
      font-size: 1.5em;
      font-style: italic;
      margin-bottom: 30px;
      text-shadow: 1px 1px 3px #000;
    }

    .author-image {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.6);
    }

    .author-name {
      font-size: 1.5em;
      font-weight: 500;
      text-shadow: 1px 1px 3px #000;
      color: white;
      font-family: Arial, Helvetica, sans-serif;
      padding-left: 500px;
    
  </style>
</head>
<body>
  <div class="front-page">
    <img src="icon.jpeg" alt="Author Image" class="author-image"> 
    <div class="book-title">Legacy of 7</div><br>
    <div class="subtitle">From Madeira Streets to Football Immortality</div>
    <div class="author-name">By - Ravikrishnamoorthy D</div> 
    
  </div>
</body>
</html>
```

## OUTPUT:

![Screenshot (283)](https://github.com/user-attachments/assets/af8c27f4-7e08-464e-a64b-03364e5cff9a)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
