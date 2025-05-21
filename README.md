# Ex.06 Book Front Cover Page Design
## Date:21/05/2025

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
  <title>Responsive Web Design Book</title>
  <style>
    body {
      margin: 0;
      background: #222;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: white;
    }

    .book-cover {
      width: 400px;
      padding: 30px 25px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
      border-radius: 8px;

      background-image: url('wall-wallpaper-concrete-colored-painted-textured-concept.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-blend-mode: overlay;
    }

    .expert-insight {
      font-size: 12px;
      color: #ccc;
      text-transform: uppercase;
      border-top: 2px solid orange;
      padding-top: 8px;
    }

    .title {
      font-size: 30px;
      font-weight: bold;
      margin-top: 20px;
      line-height: 1.2;
    }

    .subtitle {
      font-size: 14px;
      margin-top: 15px;
      color: #ddd;
    }

    .edition {
      font-weight: bold;
      color: orange;
      margin-top: 25px;
      font-size: 16px;
    }

    .bottom-bar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-top: 2px solid orange;
      padding-top: 15px;
      margin-top: 30px;
    }

    .author {
      font-weight: bold;
      font-size: 18px;
    }

    .profile-img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      border: 2px solid white;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="expert-insight">Expert Insight</div>
      <div class="title">
        Responsive Web<br>
        Design with<br>
        HTML5 and CSS
      </div>
      <div class="subtitle">
        Develop future-proof responsive websites<br>
        using the latest HTML5 and CSS techniques
      </div>
      <div class="edition">Third Edition</div>
    </div>

    <div class="bottom-bar">
      <div class="author">Hemanth Kumar</div>
      <img src="img.jpg" alt="Author photo" class="profile-img" />
    </div>
  </div>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot (370).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
