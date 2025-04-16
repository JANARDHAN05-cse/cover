# Ex.06 Book Front Cover Page Design
## Date: 16.04.2025

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
  <title>Book Cover</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto&family=Great+Vibes&display=swap');

    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to bottom right, #1c1b2e, #3c3c5a);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Roboto', sans-serif;
    }

    .cover {
      width: 360px;
      height: 560px;
      background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80') center/cover no-repeat;
      border-radius: 16px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
      position: relative;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 40px 30px;
      color: #fff;
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6));
      backdrop-filter: blur(2px);
      z-index: 1;
      border-radius: 16px;
    }

    .content {
      position: relative;
      z-index: 2;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      height: 100%;
    }

    .title {
      font-family: 'Playfair Display', serif;
      font-size: 32px;
      text-align: center;
      line-height: 1.3;
      font-weight: bold;
      margin-top: 60px;
      text-shadow: 0 1px 3px rgba(0,0,0,0.5);
    }

    .subtitle {
      font-size: 16px;
      text-align: center;
      margin-top: 10px;
      color: #ddd;
      font-style: italic;
      opacity: 0.9;
    }

    .author {
      font-family: 'Great Vibes', cursive;
      font-size: 22px;
      text-align: right;
      bottom:50px;
      color: #ffe4c4;
      padding-right: 5px;
    }

    .border-decor {
      position: absolute;
      width: 90%;
      height: 90%;
      top: 5%;
      left: 5%;
      border: 1.5px dashed rgba(255, 255, 255, 0.2);
      border-radius: 12px;
      pointer-events: none;
      z-index: 2;
    }

    .edition {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 12px;
      background: rgba(255, 255, 255, 0.1);
      padding: 4px 8px;
      border-radius: 5px;
      font-weight: bold;
      z-index: 3;
      backdrop-filter: blur(4px);
    }

    .publisher {
      position: absolute;
      bottom: 15px;
      left: 20px;
      font-size: 11px;
      color: #aaa;
      z-index: 2;
    }

    .author-photo {
      position: absolute;
      bottom: 15px;
      left: 20px; /* Place at bottom left */
      width: 60px;
      height: 60px;
      border-radius: 50%;
      border: 2px solid #fff;
      object-fit: cover;
      z-index: 3;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
    }

  </style>
</head>
<body>
  <div class="cover">
    <div class="overlay"></div>
    <div class="edition">LIMITED EDITION</div>
    <div class="content">
      <div>
        <div class="title">Can we be<br>strangers again?</div>
        <div class="subtitle">A story of love, loss, and rediscovery</div>
      </div>
      <div class="author">P Janardhan</div>
    </div>
    <div class="border-decor"></div>
    <div class="publisher">Butterfly Publications</div>

    <!-- Replaced barcode with author's photo -->
    <img src="C:\Users\JANARDHAN\Downloads\WhatsApp Image 2025-04-06 at 18.00.25.jpeg" alt="Author Photo" class="author-photo">

  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-04-16 142428.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
