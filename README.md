# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:

Write your own steps here.
### Step 2:

Create a static file directory and mention the changes in settings.
### Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.
### Step 4:

Write down the code for book cover using HTML and CSS.
### Step 5:

Add images and other contents using CSS record a screenshot of it. Validate the HTML and CSS code.
### Step 6:

Publish the website in the given URL.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #000000;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
            color:orange;
        }
        .author{
            color:white;
            display: inline;
            position: relative;
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 40px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:190px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:160px;
            left:330px;
        }
        .edition{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
            
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size:cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
        <div class="tophr">
                <hr style="color:orange;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="photo.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: white;">
            </div>
            <div class="author">
               <p><b>KALPANA S</b></p>
            </div>
            <div class="publisher">
                PACKT>
            </div>
            <div class="edition">
                <b>Third Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:
![image](https://github.com/Kalpanareshma/cover-page-design/assets/122040453/fc5641a1-7323-4aa7-8c8d-352def5ed146)
![image](https://github.com/Kalpanareshma/cover-page-design/assets/122040453/a995b86e-8c6f-489c-b9af-cee8fac2589c)


## Result:
Therfore the creation of webpage for a book using HTML,CSS is executed successfully.
