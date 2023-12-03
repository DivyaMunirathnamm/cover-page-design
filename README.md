# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:
Step 1:
clone the git hub repository.

Step 2:
Create an app in the Django interface.

step 3
Create a folder named 'static' in the app folder.

step 4:
create a new HTML file in the static folder.

step 5:
Write the HTML code with relevant CSS properties.

step 6:
Choose the appropriate style and color scheme.

step 7:
Insert the images in their appropriate places.

step 8:
Publish the website in the localhost.

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
            color:pink and aqua;
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/bgg.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(239, 74, 74);

        }

        
        .hrstyle{
            width:245px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(93, 8, 36);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
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
            font-size: medium;
            position: relative;
            top:155px;
            left:160px;
        }
        .ed{
            color: rgb(8, 46, 46);
            font-size: large;
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
        .mypic{
            position: relative;
            top: 115px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SAVEETHA ENGINEERING COLLEGE
            </div>
            <div class="hrstyle">
                <hr style="color: purple;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="SEC">
                       HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="/static/pic.jpeg" width="150" height="140" alt=>
            </div>
            <div class="id">
                <hr style="color: cornflowerblue;">
            </div>
            <div class="author">
               <p><b>DIVYA M</b></p>
            </div>
            <div class="pub">
                COMPUTER SCIENCE AND ENGINEERING
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```


## Output:

![Screenshot from 2023-12-03 21-47-54](https://github.com/DivyaMunirathnamm/cover-page-design/assets/147474097/11aff0c4-503a-473a-9b85-40d84acce6cd)

## Result:
The program for designing book front cover page using HTML and CSS is executed successfully.
