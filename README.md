# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
    <title>Interactive Image Gallery</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>

    <div class="top-banner">Interactive Image Gallery</div>

    <div class="main-content">
        <div class="gallery-container">
            <img id="galleryImage" class="gallery-image" src="big temple.jpeg ">
            <div id="caption" class="caption">BIG TEMPLE </div>
            <div class="gallery-buttons">
                <button onclick="prevImage()">Previous</button>
                <button onclick="nextImage()">Next</button>
            </div>
        </div>
    </div>

    <div class="footer-banner">
       Desinged & Developed by Harini SK(25018849) &copy;
    </div>

    <script src="index.js"></script>
</body>
</html>

body {
    font-family: sans-serif;
    display: flex;
    flex-direction: column;
    height: 100;
    background-color: white;
}

.top-banner {
    background-color:cyan;
    text-align: center;
    padding: 15px;
    font-size: 22px;
    font-weight: bold;
}

.main-content {
    display: flex;
    justify-content: center;
    align-items: center;
}

.gallery-container {
    background: pink;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 480px;
}

.gallery-image {
    width: 100%;
    height: 260px;
    object-fit: cover;
    border-radius: 10px;
}

.caption {
    margin: 15px 0;
    font-size: 18px;
    font-weight: 500;
}

.gallery-buttons {
    display: flex;
    justify-content: center;
    gap: 10px;
}

button {
    padding: 10px 25px;
    cursor: pointer;
    border: none;
    border-radius: 5px;
    background-color: red;
    color: cyan;
    font-size: 16px;
}

.footer-banner {
    background-color: cyan;
    color: darkorange;
    text-align: center;
    padding: 10px;
    font-size: 14px;
}


## OUTPUT:
<img width="784" height="602" alt="Screenshot 2025-12-25 141430" src="https://github.com/user-attachments/assets/0f1a38ad-64e6-48a8-bd6b-be723ce63413" />
<img width="743" height="586" alt="Screenshot 2025-12-25 141452" src="https://github.com/user-attachments/assets/cdd3685f-30ea-41de-8178-399a18653b49" />
<img width="688" height="592" alt="Screenshot 2025-12-25 141508" src="https://github.com/user-attachments/assets/19fcec20-fcf1-4ee7-87c5-59e26e3b95a2" />
<img width="688" height="594" alt="Screenshot 2025-12-25 141520" src="https://github.com/user-attachments/assets/2ff86356-9073-4f32-a649-d664f2f4a679" />
<img width="703" height="586" alt="Screenshot 2025-12-25 141534" src="https://github.com/user-attachments/assets/8d9d823b-87d3-47bd-b900-5183908116f4" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
