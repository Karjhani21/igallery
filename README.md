# Ex.08 Design of Interactive Image Gallery
## Date:17/05/2025

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
image.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHASES OF MOON</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 style="text-align: center; margin-top: 20px;">PHASES OF MOON</h1>
    <h3 style="text-align: center; margin-top: 20px;">KARJHANI PRIYANKA S B(21224040150)</h3>
    <div class="gallery">
        <a target="_blank" href="new moon.png">
            <img src="new moon.png" alt="NEW MOON" width="330">
        </a>
        <div class="discription">NEW MOON</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="waxing crecent.webp">
            <img src="waxing crecent.webp" alt="WAXING CRESCENT" width="330">
        </a>
        <div class="discription">WAXING CRESCENT</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="first quarter.jpg">
            <img src="first quarter.jpg" alt="FIRST QUARTER" width="200">
        </a>
        <div class="discription">FIRST QUARTER</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="waxing gibbous.jpg">
            <img src="waxing gibbous.jpg" alt="WAXING GIBBOUS" width="200">
        </a>
        <div class="discription">WAXING GIBBOUS</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="full moon.jpeg">
            <img src="full moon.jpeg" alt="FULL MOON" width="200">
        </a>
        <div class="discription">FULL MOON</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="wanning gibbous.jpg">
            <img src="wanning gibbous.jpg" alt="WANNING GIBBOUS" width="200">
        </a>
        <div class="discription">WANNING GIBBOUS</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="third quarter.jpg">
            <img src="third quarter.jpg" alt="THIRD QUARTER" width="200">
        </a>
        <div class="discription">THIRD QUARTER</div>
    </div>
    <div class="gallery">
        <a target="_blank" href="wanning crecent.jpg">
            <img src="wanning crecent.jpg" alt="WANNING CRESCENT" width="200">
        </a>
        <div class="discription">WANNING CRESCENT</div>
    </div>
</body>
   ```
   style.css:
   ```
   .gallery{
    display: inline-block;
    border:1px solid rgb(197, 193, 193);
    margin:5px;
    width:200;
}
.gallery .description{
    padding: 10px;
    text-align:center;}
.gallery:hover{
    border: 1px solid rgb(14, 12, 12);}
.gallery img{
     height:auto;
}        
```

## OUTPUT:
![alt text](<Screenshot 2025-05-17 230123.png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
