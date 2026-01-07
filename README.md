# Ex.05 Book Front Cover Page Design
## Date:7-1-2026

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
book.html

<!DOCTYPE html>
<html>

<head>
    <title>CYBER</title>
    <style>
        .bookpage{

            width: 400px;
            height: 800px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bgimage.jpeg);
            background-size: cover;
        }
            
        
        .insight{
            color:whitesmoke;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:white;
            top:250px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(246, 243, 243);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 10px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:300px;
            
        }
        .pub{
            color:whitesmoke;
            font-size: medium;
            position: relative;
            top:270px;
            left:330px;
        }
        .ed{
            color:whitesmoke;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:250px;
        
        }
        .subtitle{

            color:rgb(255, 254, 253);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            right:6px;
            width: 100px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                CYBER SECURITY
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>CYBER SECURITY</h1>
            <h2>FUNDAMENTALS</h2></div>
            <div class="subtitle">
                 
            </div>
            <div align="center"class="subtitle">
                 <P>BEST SECURITY PRACTICES</P>
            </div>

            <div class="mypic">
                <img src="profile.jpeg" width="80" height="100" align="bottom"></img>
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>kamalesh </b></p>
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
<img width="1908" height="1079" alt="Screenshot 2026-01-07 210438" src="https://github.com/user-attachments/assets/3fb9e50e-9565-404b-8eec-1c79917c054a" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
