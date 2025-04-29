# Ex.06 Book Front Cover Page Design
## Name: VASANTH N
# Date: 25/04/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Book Title</title>
        
            <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Qwitcher+Grypen:wght@400;700display=swap" rel="stylesheet">
        
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700family=Londrina+Sketchfamily=Qwitcher+Grypen:wght@400;700&display=swap" rel="stylesheet">
        
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700display=swap" rel="stylesheet">
        
        
            <style>
                body {
                    margin: 0;
                    padding: 0;
                    height: 100vh;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    font-family: 'Georgia', serif;
                    
                   
                }
                .book-cover {
                    width: 400px;
                    height: 600px;
                    background-image: url("c:\Users\admin\Desktop\html agilan\money full.jpg");
                    border: 8px solid #b5651d;
                    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
                    display: flex;
                    flex-direction: column;
                    justify-content: space-between;
                    padding: 40px;
                    text-align: center;
                }
                .title {
                    font-size: 60px;
                    font-weight:bolder;
                    color: #3e3a39;
                    font-family: "Qwitcher Grypen", cursive;
                }
                .author {
                    font-size: 29px;
                    /*margin-top: 10px;*/
                    color: #6b4f3f;
                    font-family: "Caveat", cursive;
                    font-weight: 900;
                    text-align: right;
                }
                .moneyimage{
                    width: 280px; text-align: center;
                }
                .bestsellerimage{
                    width: 70px;
                    float: right;
                }
                /*.images{
                    display: flex;
                    width: 28px; 
                } */
                .about{
                    letter-spacing: 2px;
                    color: green;
                    font-weight: 400;
                }
                .publisher {
                    font-size: 18px;
                    color: #6b4f3f;
                }
                 .cover-design {
                    margin-top: 0px; 
                    background-size: cover;
                    background-position: center;
                    height: 200px;
                    border: 2px solid #b5651d;
                }  
                .about2{
                    font-weight: 200;
                    font-style: italic;
                }
                .about2sub{
                    letter-spacing: 1px;
                    font-weight: 500;
                    font-size:medium;
                }
                .footer {
                    font-size: 14px;
                    margin-top: 20px;
                    color: #3e3a39;
                    font-family: "Caveat", cursive;
        
                }
            </style>
        </head>
        <body>
            
        
            <div class="book-cover">
                <div class="title">The Psychology of Money</div>
                <div class="author"> --Morgan Housel</div>
                
                <div class="cover-design">
                    {% load static%}
                    <img src={% static 'images/money_full.jpg' %} height="200px" width="397px" >
                </div>
                <div class="about"> TIMELESS LESSONS ON WEALTH, GREED, AND HAPPINESS </div>
                <h3 class="about2">"Everyone should own a copy." </h3>
                <h2 class="about2sub">- JAMES CLEAR</h2>
                <div class="footer">New york times` Bestselling Author of `Atomic Habits</div>
            </div>
        
        </body>
        </html>

# OUTPUT:
![image](https://github.com/user-attachments/assets/9eb278e6-0b57-4572-b5f4-30dc2386f7cb)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
