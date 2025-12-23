# Ex.06 Book Front Cover Page Design
## Date:

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
    <title>The Fire of Wings – Book Cover</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #111;
            font-family: "Georgia", serif;
        }

        .cover {
            width: 420px;
            height: 620px;
            background: linear-gradient(180deg, #0e2a33, #1f4e5f);
            color: white;
            text-align: center;
            padding: 40px 30px;
            box-sizing: border-box;
        }

        .title {
            font-size: 38px;
            letter-spacing: 3px;
            margin-top: 120px;
            margin-bottom: 20px;
        }

        .subtitle {
            font-size: 18px;
            font-family: Arial, sans-serif;
            opacity: 0.9;
            margin-bottom: 180px;
        }

        .author {
            font-size: 17px;
            font-family: Arial, sans-serif;
            margin-top: 40px;
            font-weight: bold;
        }

        .qualification {
            font-size: 14px;
            font-family: Arial, sans-serif;
            margin-top: 6px;
            opacity: 0.9;
            letter-spacing: 1px;
        }

        .edition {
            font-size: 13px;
            font-family: Arial, sans-serif;
            margin-top: 20px;
            opacity: 0.8;
        }
    </style>
</head>
<body>

    <div class="cover">
        <div class="title">
            THE FIRE OF<br>WINGS
        </div>

        <div class="subtitle">
            A Journey of Dreams & Courage
        </div>

        <div class="author">
            Author: DR. SUJITHA
        </div>

        <div class="qualification">
            M.TECH, PhD
        </div>

        <div class="edition">
            First Edition · 2025
        </div>
    </div>

</body>
</html>
```

## OUTPUT:
<img width="1238" height="912" alt="527414210-bf92409b-20a8-418c-9713-c8954b5a5b27" src="https://github.com/user-attachments/assets/bf8f4aba-8a43-4537-8fd9-ea5f218efcac" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
