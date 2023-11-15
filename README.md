# Ex.06 Book Front Cover Page Design
## Date:26/10/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

        <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            body {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                margin: 0;
                background-color: #f0f0f0;
            }
    
            .bookpage {
                width: 400px;
                height: 600px;
                color: rgb(245, 112, 11);
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(book.jpg);
                background-size: cover;
                position: relative;
            }
    
            .insight {
                color: white;
            }
    
            .booktitle {
                font-family: 'Algerian', cursive;
                font-size: 30px;
                text-align: center;
                position: relative;
                top: 30px;
            }
    
            .subtitle {
                font-family: Tahoma;
                font-size: large;
                text-align: center; /* Center the subtitle text */
                position: relative;
                top: 40px;
            }
    
            .author {
                font-family: 'Algerian', cursive;
                position: absolute;
                bottom: 10px;
                right: 10px;
                color: rgb(255, 0, 51);
                font-size: 25px;
            }
    
            
        </style>
        <title>Book Cover Page</title>
    </head>
    
    <body>
        <div class="bookpage">
            <div class="insight">FICTION</div>
            <div class="booktitle">
                <h1>The Noob</h1>
            </div>
            <div class="author">
                Rakesh Kumar.S
            </div>
            
        </div>
    </body>
    </html>


## OUTPUT:
![Screenshot 2023-11-11 194643](https://github.com/Rakesh2k23/cover/assets/141472158/e8cbdd7c-20bc-43cb-9438-53279b54e502)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
