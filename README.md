# Ex.06 Book Front Cover Page Design
## Date: 09-11-2025

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
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Horror Movie Poster</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: black;
            font-family: 'Creepster', cursive;
        }

        .poster {
            width: 650px;
            height: 750px;
            border: 2px solid red;
            background-color: black;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            background-image: url("new house.jpg");
            box-shadow: 0 0 30px red;
        }

        .title {
            font-size: 45px;
            font-weight: bold;
            font-family: 'Creepster', cursive;
            color: red;
            text-shadow: 2px 2px 10px black;
            margin-bottom: 60px;
            text-transform: uppercase;
        }

        .subtitle {
            font-size: 30px;
            color: #ff4444;
            font-family: 'Nosifer', cursive;
            text-shadow: 2px 2px 8px black;
            margin-bottom: 40px;
        }

        .bottom-text {
            margin-top: auto;
            font-family: 'Nosifer', cursive;
            font-size: 25px;
            color: #ff0000;
            text-shadow: 2px 2px 5px black;
        }

        @import url('https://fonts.googleapis.com/css2?family=Creepster&family=Nosifer&display=swap');
    </style>
</head>
<body>
    <div class="poster">
        <div class="title">The Whispering Shadows</div>
        <div class="subtitle">A Tale of Fear and Blood</div>
        <div class="bottom-text">Written By: LOKESH</div>
        
    </div>
</body>
</html>

```

## OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9a6b4855-8248-4d84-8758-f985e0cd0262" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
