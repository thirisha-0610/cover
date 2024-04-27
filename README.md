# Ex.06 Book Front Cover Page Design
## Date:24/04/2024

## NAME: THIRISHA A
## REG NO: 212223040228

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
<html>

<head>
    <title>POSTER</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(poster.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(245, 245, 245);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: blue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color: chartreuse;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color: brown;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: cadetblue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color: darkgoldenrod;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position:relative;
            top: 150px;
            left: 260px;
            width: 100px;
            height: 100px;
            bottom: 100px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                LEARNING
            </div>
            <div class="hrstyle">
                <hr style="color:blueviolet">
            </div>
            <div class="booktitle">
                <h1>JavaScript: The Good Parts</h1></div>
            <div class="subtitle">
                Essential JavaScript: A Guide to Efficiency
            </div>
            <div class="subtitle">
                Unlock the Power of Clean Code
            </div>

            <div class="mypic">
                <img src="PHOTO.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(255, 205, 251)">
            </div>
            <div class="author">
               <p><b>THIRISHA A</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:

![Screenshot (26) - Copy](https://github.com/thirisha-0610/cover/assets/149347494/21ac9957-4fb5-4f89-9746-7eb4777385fa)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
