# Ex.06 Book Front Cover Page Design
## Date:

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="book-cover">
        <div class="title">Web Development</div>
        <div class="description"> Web development is the process of creating, building, and maintaining websites and web applications</div>
        <div class="design"> By V Rishon Anand </div>
        <img src="myphoto.jpeg" alt="Small Decoration" class="small-picture">
        <div class="edition"> 2nd Edition </div>
    </div>
</body>
</html>

styles.css

body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: blueviolet;
    font-family: Arial, sans-serif;
}

.book-cover {
    width: 500px;
    height: 650px;
    background-color:rgb(54, 39, 153);
    color:rgb(150, 89, 89);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    border: 5px solid #000;
    box-shadow: 5px 5px 15px rgba(155, 4, 4, 0.5);
    border-radius: 20px;
    background: url('bookcover3.png')
    
}

.title {
        position: absolute;
        top: 140px; 
        left: 50%; 
        transform: translateX(-50%); 
        font-size: 40px;
        font-family: 'Creepster';
        color: white;
        text-shadow: 2px 2px 5px rgba(197, 152, 152, 0.7), 0 0 25px rgba(255, 0, 0, 0.7), 0 0 5px rgba(255, 0, 0, 0.7);
        letter-spacing: 1px;
        text-transform: uppercase;
        font-weight: bold;

    }
    



.description {
    font-size: 28px;
    margin-bottom: 30px;
    font-style: italic;
    color:yellow;
}

.design {
    position: absolute;
    bottom: 110px;
    left: 550px;   
    font-size: 24px; 
    font-style: italic; 
    color:rgb(245, 247, 247); 
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
}
.small-picture {
    position: absolute;
    bottom: 110px; 
    right: 550px;  
    width: 100px; 
    height: auto;
    border-radius: 5px; 
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5); 
}

.edition {
    position: absolute;
    bottom: 160px;
    left: 550px;   
    font-size: 34px; 
    font-style: italic; 
    color:greenyellow; 
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7); 
}


```

## OUTPUT:
![alt text](<Screenshot 2024-12-02 223057.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
