# Ex.06 Book Front Cover Page Design
## Date:28-04-2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: black;
        }

        .book-cover {
            width: 533px;
            height: 800px;
            background-color:black;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            margin: 50px auto;
            position: relative;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

     
      .book-cover .title1{
    position: absolute;
    bottom: 420px;
    right: 22px;
    text-align: right;
    font-size: 24px;
    color:whitesmoke;
    text-shadow: 0px  0px 5px rgb(0, 0, 0);
    font-family: 'Great Vibes', cursive;
}

     

       .book-cover .author {
    position: absolute;
    bottom: 25px;
    right: 20px;
    font-size: 18px;
    color:whitesmoke;
    text-shadow: 0px  0px 5px rgb(0, 0, 0);
    font-family: 'Alex Brush', cursive;



}


        .book-cover .mypic
        {
            position: absolute;
            top: 630px;
            right: 10px;
            border-radius: 10%;
        }

        .book-cover .image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top:  0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <img src="book cover.jpg" alt="Book Cover Image" class="image">
         <div class="title1">- Mukesh</div>
        <img src="Photo.jpg" width="120" height="120" class="mypic">
       <div class="author">Mukesh R</div>
    </div>
</body>
</html>
```


## OUTPUT:

![alt text](<Book Cover Output.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
