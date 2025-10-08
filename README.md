# Ex.07 Restaurant Website
## Date:08:10:2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Administration - Tasty food</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Pandian Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Our Team</h2>
    <div class="admin-grid">
        <!-- Repeat for 6 people -->
        <div class="admin-item">
            <img src="person1.jpeg" alt="Person 1"style="width:20%; height:100px;">

            <h3>Sakthi</h3>
            <p>Manager</p>
        </div>
        <div class="admin-item">
            <img src="person2.jpeg" alt="Person 2"style="width:20%; height:100px;">
            <h3>Virat</h3>
            <p>Chef</p>
        </div>
        <div class="admin-item">
            <img src="person3.jpeg" alt="Person 3"style="width:20%; height:100px;">
            <h3>Siddharth</h3>
            <p>Waiter</p>
        </div>
        <div class="admin-item">
            <img src="person4.jpeg" alt="Person 4"style="width:20%; height:100px;">
            <h3>Sam</h3>
            <p>Chef</p>
        </div>
        <!-- Add remaining 3 people similarly -->
    </div>
</div>

<footer>
    &copy; 2025 Sai Praveen
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - Pandian restaurant</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Pandian Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Contact Us</h2>
    <div class="contact-info">
        <p>Address: 123 Karan Street, Food Court</p>
        <p>Phone: +91-9327861911</p>
        <p>Email: info@pandian.com</p>
        <p>Follow us on:
            <a href="#">Facebook</a>,
            <a href="#">Twitter</a>,
            <a href="#">Instagram</a>
        </p>
        <p>Business Hours: Mon-Sun: 10am - 10pm</p>
        
    </div>
</div>

<footer>
    &copy; 2025 Sai Praveen
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Pandian Restaurant - Home</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Pandian Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Welcome to Pandian Restaurant!</h2>
    <p style="text-align:center;">Enjoy our wide variety of foods and experience excellent service.</p>
    <img src="food1.jpeg" alt="Restaurant Image" style="width:25%; height:50%; margin-top:40px;">
    <img src="food2.jpeg" alt="Restaurant Image" style="width:30%; height:50%; margin-top:40px;">
    <img src="food3.jpeg" alt="Restaurant Image" style="width:28%; height:50%; margin-top:40px;">
    <img src="food4.jpeg" alt="Restaurant Image" style="width:25%; height:50%; margin-top:40px;">
    <img src="food5.jpeg" alt="Restaurant Image" style="width:30%; height:50%; margin-top:40px;">
    <img src="food6.jpeg" alt="Restaurant Image" style="width:28%; height:50%; margin-top:40px;">

</div>

<footer>
    &copy; 2025 Sai Praveen 
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Menu - Pandian Restaurant</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Pandian Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <!-- Repeat for 12 food items -->
        <div class="menu-item">
            <img src="pizza.jpeg" alt="Food 1"style="width:20%; height:100px;">
            <h3>Pizza</h3>
            <p>120</p>
        </div>
        <div class="menu-item">
            <img src="burger.jpeg" alt="Food 2"style="width:20%; height:100px;">
            <h3>Burger</h3>
            <p>130</p>
        </div>
        <div class="menu-item">
            <img src="pasta.jpeg" alt="Food 3"style="width:20%; height:100px;">
            <h3>Pasta</h3>
            <p>99</p>
        </div>
        <div class="menu-item">
            <img src="noodles.jpeg" alt="Food 4"style="width:20%; height:100px;">
            <h3>Biriyani</h3>
            <p>99</p>
        </div>
        <div class="menu-item">
            <img src="icecream.jpeg" alt="Food 5"style="width:20%; height:100px;">
            <h3>Icecream</h3>
            <p>110</p>
        </div>
        <div class="menu-item">
            <img src="sweets.jpeg" alt="Food 6"style="width:20%; height:100px;">
            <h3>Tiramisu</h3>
            <p>90</p>
        </div>
        <!-- Add remaining 9 food items similarly -->
    </div>
</div>

<footer>
    &copy; 2025 Sai Praveen 
</footer>

</body>
</html>
```

## OUTPUT:

![alt text](<restuarant/screenshot 1.jpg>)
![alt text](<restuarant/screenshot 2.jpg>)
![alt text](<restuarant/screenshot 3.jpg>)
![alt text](<restuarant/screenshot 4.jpg>)
![alt text](<restuarant/screenshot 5.jpg>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
