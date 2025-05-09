# Ex.06 Book Front Cover Page Design
## Date:09-05-2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 300px;
      height: 450px;
      background: linear-gradient(to bottom right, #2c3e50, #34495e);
      color: white;
      padding: 30px 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border-radius: 10px;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-top: 30px;
    }

    .subtitle {
      font-size: 18px;
      text-align: center;
      margin-top: 10px;
      font-style: italic;
    }

    .author {
      font-size: 16px;
      text-align: center;
      margin-bottom: 30px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="title">The Lost Chronicles of saveetha</div>
    <div class="subtitle">chennai</div>
    <div class="author">hemanth yadav</div>
  </div>
</body>
</html>
~~~

## OUTPUT:
![Screenshot 2025-05-09 140216](https://github.com/user-attachments/assets/72757ac2-3fe8-4b82-b4ee-fe0a69b6e9b7)
![Screenshot 2025-05-09 140141](https://github.com/user-attachments/assets/bf119096-cd1f-4cd3-ac74-25e04fed95b1)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
