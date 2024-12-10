# Ex.06 Book Front Cover Page Design
## Date:10/12/2024

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
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(download.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(66, 250, 130);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(62, 237, 132);
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
            color:rgb(52, 238, 117);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(64, 241, 135);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(73, 246, 157);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                special edition
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(52, 248, 163)">
            </div>
            <div class="booktitle">
                <h1>INTRODUCTION TO WEB DEVELOPMENT</h1></div>
            <div class="subtitle">
                 -USING DJANGO
            </div>
            <div class="subtitle">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="vivin.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(42, 244, 143)">
            </div>
            <div class="author">
            <p><b>V.VIVIN MATHEW(24001048)</b></p>
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

![alt text](<Screenshot 2024-12-10 140328.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
