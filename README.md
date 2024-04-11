# Ex.06 Book Front Cover Page Design
## Date:11-03-2024

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
    <title>AI&ML</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(back.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(40, 175, 28);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(225, 28, 143);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(174, 133, 23);
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
            color:rgb(97, 19, 161);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(69, 199, 199);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(8, 113, 50);
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
                DANCE
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(34, 188, 49)">
            </div>
            <div class="booktitle">
                <h1>INTRODUCTION TO COMPUTER SCIENCE</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="c:\Users\admin\Downloads\MY PHOTO.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(36, 17, 120)">
            </div>
            <div class="author">
               <p><b>BHUMIREDDY LAKSHMI VARDHAN REDDY</b></p>
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
``  
## OUTPUT:
![Screenshot 2024-04-11 103139](https://github.com/BhumireddyLakshmivardhanreddy/cover/assets/148514637/6084e45d-6507-4170-9d6e-399d8dfa9d64)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
