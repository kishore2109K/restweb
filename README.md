# Ex.07 Restaurant Website
## Date:18.11.24
## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
HTML code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <img src="Asset 7@4x.png" alt="Little Lemon Logo" class="logo">
    <h1>Welcome to Little Lemon</h1>
    <p>Your destination for delicious, fresh meals.</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>At Little Lemon, we take pride in serving the freshest ingredients and the most delightful dishes. Come and taste the magic!</p>
</section>

<section id="menu" class="section">
    <h2>Our Menu</h2>
    <div class="menu">
        <div class="menu-item">
            <img src="Greek-Lemon-Chicken-main.webp" alt="Classic Lemon Chicken">
            <h3>Classic Lemon Chicken</h3>
            <p>Grilled chicken with a tangy lemon glaze - Rs. 150</p>
        </div>
        <div class="menu-item">
            <img src="farm+fresh+salad-3.jpg" alt="Fresh Garden Salad">
            <h3>Fresh Garden Salad</h3>
            <p>A mix of greens with our signature lemon vinaigrette - Rs. 60</p>
        </div>
        <div class="menu-item">
            <img src="images.jpeg" alt="Lemon Tart">
            <h3>Lemon Tart</h3>
            <p>A sweet and zesty dessert to end your meal perfectly - Rs. 80</p>
        </div>
        <div class="menu-item">
            <img src="How-to-Make-Chicken-Alfredo-Pasta-hero-02082017.webp" alt="Lemon Herb Pasta">
            <h3>Lemon Herb Pasta</h3>
            <p>Pasta tossed with fresh herbs and lemon zest - Rs. 130</p>
        </div>
        <div class="menu-item">
            <img src="download.jpeg" alt="Classic Lemonade">
            <h3>Classic Lemonade</h3>
            <p>A refreshing drink with the perfect balance of sweet and sour - Rs. 50</p>
        </div>
        <div class="menu-item">
            <img src="download (1).jpeg" alt="Grilled Lemon Fish">
            <h3>Grilled Lemon Fish</h3>
            <p>Freshly caught fish grilled with lemon and herbs - Rs. 200</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: contact@littlelemon.com</p>
    <p>Phone: (555) 123-4567</p>
    <p>Address: 123 Lemon Lane, Citrus City</p>
</section>

<footer>
    <p>&copy; 2024 Little Lemon Restaurant. All rights reserved.</p>
</footer>

</body>
</html>
```

CSS code:
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #f4c430;
    color: white;
    text-align: center;
    padding: 1.5rem;
    position: relative;
}

header img {
    position: absolute;
    top: 20px;
    left: 10px;
    width: 80px;  
    height: 100px;  
    border-radius: 50%;  
    object-fit: contain;
}

nav {
    background-color: #333;
    overflow: hidden;
}

nav a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

nav a:hover {
    background-color: #ddd;
    color: black;
}

.hero {
    text-align: center;
    padding: 2rem;
    background-image: url('restaurant.jpg'); /* Replace with your hero image */
    background-size: cover;
    color: white;
    background-position: center;
}

.section {
    padding: 2rem;
    text-align: center;
}

.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
}

.menu-item {
    border: 1px solid #ddd;
    padding: 1rem;
    width: 300px;
    border-radius: 8px;
    background-color: white;
    text-align: center;
}

.menu-item img {
    max-width: 100%;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: white;
}

.contact-image {
    max-width: 100%;
    height: auto;
    margin-top: 1rem;
    border-radius: 8px;
}
```

## OUTPUT:
![Screenshot 2024-11-18 223459](https://github.com/user-attachments/assets/8abf38fe-8fd9-4465-9766-259aea751239)
![Screenshot 2024-11-18 223524](https://github.com/user-attachments/assets/b9d4b1db-d8b6-4513-81a2-d97f6bbda75e)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
