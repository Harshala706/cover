# Ex.06 Book Front Cover Page Design
## Date: 05-04-2025

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
  <title>The Art of Being Alone</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Georgia', serif;
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 768px;
      height: 1152px;
      background-image: url('book_cover.png'); 
      background-size: cover;
      background-position: center;
      position: relative;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    }

    .overlay {
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.3); 
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 60px 40px;
      color: white;
    }

    .text-content {
      text-align: center;
      margin-top: 120px;
    }

    .title {
      font-size: 64px;
      font-weight: bold;
      line-height: 1.2;
      margin: 0;
    }

    .subtitle {
      font-size: 28px;
      margin-top: 20px;
      font-style: italic;
    }

    .author {
      font-size: 24px;
      text-align: center;
      margin-bottom: 60px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay">
      <div class="text-content">
        <div class="title">The Art of<br>Being Alone</div>
        <div class="subtitle">Finding Peace in Solitude</div>
      </div>
      <div class="author">by B. Harshala Reddy</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![Front Page](https://github.com/user-attachments/assets/4028d8c8-a561-4123-9c1b-700dd8dd26b0)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
