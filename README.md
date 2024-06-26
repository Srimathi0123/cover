# Ex.06 Book Front Cover Page Design
## Date:08/04/2024

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
## page.html
```
<html>
    <head>
        <title>
            HTML page
        </title>
        <style>
img{
    height: 60%;
    width:25%;
    /* position: absolute;
    left:63%;
    top:64%; */
    float: right;
    /* opacity: 70%; */

}
h1{
    font-size: 400%;
}
p{font-size: 200%;

}       
.container{
    color: rgb(15, 15, 16);
    position: absolute;
    top: 10%;
    left: 30%;
    padding: 25px;
    background-image: url(./bgimg1.jpg);
    background-repeat: no-repeat;
    background-size: 100% 100%;
    color: white;
 
    height: 90%;
    width: 35%;
    background-color: aqua;
}
/* *{
    background-color: rgb(167, 58, 58);
} */
hr{
    color: orange;
}
.center
{
    height: 35%;
    align-items: flex-end;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
.details
{
    height: 10%;
    align-items: center;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
#hr1
{
    width: 20%;
    margin-left: 0.2%;
    color: blue;
}


        </style>
    </head>
<body>
<div class="container">
    <h2> SEC INSIGHT</h2>
    <hr id="hr1">
    <h1>Learn JavaScript VISUALLY With Interactive Exercises
    </h1>
    <p>It covers how to read and understand JavaScript, the JavaScript syntax, the basics of object-oriented programming, and the essential programming concepts in JavaScript.
    </p>
    <div class ="center">
        <p>
            Third Edition            
        </p>    
        <img src="imgsri.jpg">
    </div>
    <hr>
    <div class="details">
        <p>SRIMATHI V</p>
        <p>SEC</p>
    </div>    
</div>    
</body>
</html>


```


## OUTPUT:
![image](https://github.com/Srimathi0123/cover/assets/118673240/b916d056-0a19-4a53-a9a7-c2c7e16b7bc2)







## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
