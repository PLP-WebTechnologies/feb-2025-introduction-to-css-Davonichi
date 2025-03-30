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

Happy Coding! 💻✨

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">Welcome to My Styled Page</header>
    
    <section class="section">
        <h2 class="title">About This Page</h2>
        <p id="highlight">This is a sample webpage demonstrating CSS styling.</p>
        <div class="img-container">
            <img src="https://via.placeholder.com/400" alt="Sample Image">
        </div>
    </section>
</body>
</html>

CSS
/* Global Styles */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Header Styling */
.header {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 20px;
    font-size: 24px;
}

/* Styling an Image */
.img-container img {
    width: 100%;
    max-width: 400px;
    border: 5px solid #007bff;
    border-radius: 10px;
    margin: 20px auto;
    display: block;
}

/* Section Styling */
.section {
    background: white;
    padding: 20px;
    margin: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* ID Selector Example */
#highlight {
    color: #d9534f;
    font-weight: bold;
}
