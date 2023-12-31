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
cover.html
<html>
<head>
    <title>AI</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(./images/sky.png);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(14, 255, 255);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:cornflowerblue;
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(255, 12, 12);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(7, 250, 40);
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:rgb(12, 7, 182);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:rgb(0, 0, 0);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
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
                SCOFT
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>DEVELOPMENT OF AI</h1></div>
            <div class="subtitle">
                 FUTURE OF TECHNOLOGY
            </div>
            <div class="subtitle">
                 Top seller of 2023
            </div>

            <div class="mypic">
                <img src="./images/author.jpg" width="80" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(0, 0, 0)">
            </div>
            <div class="author">
               <p><b>Dineshkarthik N</b></p>
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


## OUTPUT:
![Screenshot 2023-12-31 184232](https://github.com/dinesh2068/cover/assets/151390189/e8bedbd9-cb54-409a-96d0-b63be4317ba8)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
