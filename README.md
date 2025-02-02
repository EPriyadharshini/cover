# Ex.06 Book Front Cover Page Design
## Date:
28/11/2023
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
    <title>DATA SCIENCE IN AI</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:rgb(252, 250, 250);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(img2.jpeg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(252, 248, 248);
        
        }
        
        
        .hrstyle{
            width:90px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(247, 241, 241);
            top:240px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(248, 243, 243);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:240px;
            
        }
        .pub{
            color:rgb(244, 247, 247);
            font-size: medium;
            position: relative;
            top:200px;
            left:350px;
        }
        .ed{
            color:rgb(248, 245, 245);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:145px;
        
        }
        .subtitle{
            color:rgb(245, 242, 242)
            font-family:unicorn;
            font-size: MEDIUM;
            position: relative;
            margin-right:100;
            top:40px;
        }
        .mypic{
            position: relative;
            top:220px;
            left: 290px;
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
                The Power of AI in your hands
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(17, 17, 17)242)">
            </div>
            <div class="booktitle">
                <h1>AI CHRONICALS</h1></div>
                <div class="subtitle">
                CREATING THE FUTURE 
                </div>
                <div class="subtitle">
                THROUGH LEARNING...
                    </div>
            <div class="subtitle">
                Future unveiled
            </div>
            <div class="subtitle">
                Code chronicals 
            </div>
            <div class="subtitle">
               ... Begins...

            </div>

            <div class="mypic">
                <img src="img3.jpeg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(254, 250, 250)">
            </div>
            <div class="author">
               <p><b>Priyadharshini E</b></p>
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
![Alt text](<Screenshot 2023-12-01 142148.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
