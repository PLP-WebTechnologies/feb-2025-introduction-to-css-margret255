# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <link rel="stylesheet" href="css.css"> 
</head>
<body>

    <h1 class="title">Welcome to CSS Styling</h1>

    <p id="description">This is an example of applying CSS to an HTML page.</p>

    <img src="https://images.pexels.com/photos/1231234/pexels-photo-1231234.jpeg" alt="Scenic View from Pexels" width="600">

    <div class="box">
        <p>This box demonstrates margin, padding, and borders.</p>
    </div>

</body>
</html>


/* 1. Using an element selector */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 20px;
}

/* 2. Using a class selector */
.title {
    color: blue;
    text-align: center;
    font-size: 24px;
}

/* 3. Using an ID selector */
#description {
    font-size: 18px;
    font-style: italic;
    color: darkgreen;
}

/* Styling an image */
.styled-image {
    width: 300px;
    height: auto;
    border: 3px solid black;
    border-radius: 10px;
    display: block;
    margin: 20px auto;
}

/* Margin, Padding, and Borders */
.box {
    border: 2px solid red;
    padding: 15px;
    margin: 20px;
    background-color: white;
    text-align: center;
}


