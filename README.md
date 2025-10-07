# Ex.06 Book Front Cover Page Design
## Date:7/02/2025

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

<html>
    <head>
        <title>Book Cover Page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="bookcover">
        <div class="margin">
        <div class="insight">
            SEC Insights
        </div>
        <div class="hrstyle">
            <hr style="color: white">
        </div>
        <div class="title">
            <h1>Rise<br>Beyond<br>Limits</h1></div>
        <div class="subtitle">
            "A guide to breaking barriers and becoming unstoppable.''   
        </div>
        <div class="subtitle">
            Top Selling Book To Build Motivation Among The Younger Ones
        </div>
        <div class="mypic">
            <img src="me.jpg" width="100" height="120">
        </div>
        <div class="id">
            <hr style="color: white">
        </div>
        <div class="author">
            <p><b>K MONISHWAR</b></p>
        </div>
        <div class="publisher">
            SEC
        </div>
        <div class="edition">
            Superb Edition
        </div>
        </div>
        </div>
    </body>
</html>

style.css

.bookcover{
    width: 400px;
    height: 600px;
    color:rgb(240, 238, 238);
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image:url(backgroundpicture.jpeg) ;
    background-size: cover;
}

.margin{
    width: 400px;
    height: 600px;
	border: solid 2px rgb(19, 18, 18);
	background-size: cover;
}
        
.insight{
    color: white;
    left: 5px;
    top: 8px;
    position: relative;
}
        
.hrstyle{
    width: 95px;
	height: 2px;
    color: white;
}

.title{
    color: white;
    font-family: Verdana;
    font-size: x-large;
    text-align: center;
    position: relative;
    top: 25px;      
}

.subtitle{
    color: rgb(118, 254, 6);
    font-family: Tahoma;
    font-size: medium;
    position: relative;
    left: 13px;
    top: 20px;
}

.mypic{
    position: relative;
    top: 110px;
    left: 290px;
    width: 75px;
    height: 80px;
    background-size:contain;
        }

.id{
    width:400px;
    height: 2px;
    position: relative;
    top:150px;
}

.author{
    display: inline;
    position: relative;
    color: rgb(201, 174, 223);
    top:135px; 
    left: 8px;           
    font-family: Times New Roman;
    font-size: medium;
}
        
.publisher{
    color: white;
    font-size: medium;
    position: relative;
    font-family:Times New Roman;
    top:100px;
    left:360px;
}

.edition{
    color: white;
    font-size: medium;
    font-family:Times New Roman;
    position: relative;
    left: 8px;
    top: 60px; 
}
```

## OUTPUT:

![alt text](<Screenshot (48).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
