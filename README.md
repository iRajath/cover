# Ex.06 Book Front Cover Page Design
## Date: 02.12.2024

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

`benfrain.html`
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Web Design Book Cover</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #3b3b3b;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }

      .cover {
        width: 29vw;
        height: 79vh;
        background-color: #232323;
        border: white;
        padding: 20px;
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }

      .cover .header {
        font-size: 14px;
        color: orange;
        font-weight: bold;
        z-index: 1;
        margin-bottom: 5px;
      }

      .cover .title {
        font-size: 28px;
        margin-top: 10px;
        font-weight: bold;
        line-height: 1.2;
        z-index: 1;
      }

      .master {
        display: flex;
        flex-wrap: wrap;
        flex: content;
      }

      .cover .subtitle {
        font-size: 16px;
        margin-top: 15px;
        line-height: 1.5;
        z-index: 1;
      }

      .about {
        background-color: #232323;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 5px;
      }

      .wave {
        height: 100px;
        background: linear-gradient(45deg, transparent 50%, #c0c0c0 50%),
          linear-gradient(135deg, transparent 50%, #ffffff 50%);
        background-size: 100px 100px;
        transform: rotate(-45deg);
        opacity: 0.5;
        z-index: 0;
        margin-top: 35%;
        margin-bottom: 12%;
      }

      .bottom-section {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: auto;
        margin-bottom: -5px;
      }

      .cover .edition {
        color: orange;
        font-weight: bold;
        font-size: 18px;
      }

      .cover .author {
        font-size: 20px;
        font-weight: bold;
      }

      .cover .publisher {
        font-style: italic;
        font-size: 18px;
        color: white;
        font-weight: bold;
      }

      .author-photo {
        width: 60px;
        height: 60px;
        border-radius: 50%;
        background: orange url("./Untitled9_20241202180853.png") top/cover
          no-repeat;
        margin-left: auto;
        margin-bottom: 5px;
      }

      .ruler {
        background-color: orange;
        height: 1px;
        width: 50%;
        margin-left: -20px;
      }

      .rulerL {
        background-color: orange;
        height: 1px;
        width: 29vw;
        margin-left: -20px;
        margin-right: 0px;
      }
    </style>
  </head>

  <body>
    <div class="cover">
      <div class="header">EXPERT INSIGHT</div>
      <div class="ruler"></div>
      <div class="title">Responsive Web Design with <br />HTML5 and CSS</div>
      <div class="subtitle">
        Develop future-proof responsive websites<br />
        using the latest HTML5 and CSS techniques
      </div>
      <div class="wave"></div>
      <div class="bottom-section">
        <div class="edition">Fourth Edition</div>
        <br />
        <div class="author-photo"></div>
      </div>
      <div class="rulerL"></div>
      <div class="about">
        <div class="author">S Rajath</div>
        <div class="publisher">Stark Industries</div>
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

![Screenshot 2024-12-02 183026](https://github.com/user-attachments/assets/463a9275-3b58-43b1-be12-b29e510eb2cf)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
