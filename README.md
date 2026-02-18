# Ex02 Commercial Website
## Date:18.02.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

### index.css

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Header -->
<header>
    <h1>My Business</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Home Section -->
<section id="home" class="home">
    <h2>Welcome to Our Business</h2>
    <p>We provide high-quality products and services for our customers.</p>
    <button>Buy Now</button>
</section>

<!-- Services Section -->
<section id="services" class="services">
    <h2>Our Services</h2>
    <div class="box">
        <h3>Web Development</h3>
        <p>We create professional websites.</p>
    </div>
    <div class="box">
        <h3>App Development</h3>
        <p>We develop mobile applications.</p>
    </div>
</section>

<!-- Products Section -->
<section id="products" class="products">
    <h2>Our Products</h2>
    <div class="box">
        <h3>Laptop</h3>
        <p>Price: ₹50,000</p>
        <button>Order</button>
    </div>
    <div class="box">
        <h3>Mobile</h3>
        <p>Price: ₹20,000</p>
        <button>Order</button>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: business@gmail.com</p>
    <p>Phone: 9876543210</p>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 My Business. All Rights Reserved.</p>
</footer>

</body>
</html>


```

### style.css

```

/* Body */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f7181c; /* Dark blue */
    color: #ffffff;
    text-align: center; /* Center all text */
}

/* Header */
header {
    background: linear-gradient(to right, #ccced5, #3a86ff);
    padding: 20px;
}

header h1 {
    margin: 0;
    color: #00d4ff;
}

/* Navigation */
nav ul {
    list-style: none;
    padding: 0;
    margin-top: 10px;
}

nav ul li {
    display: inline-block;
    margin: 0 15px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #c0b340;
}

/* Home Section */
.home {
    padding: 80px 20px;
    background: linear-gradient(to right, #0b132b, #1c2541);
}

.home h2 {
    color: #00d4ff;
}

.home button {
    background-color: #00d4ff;
    color: black;
    padding: 12px 25px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.home button:hover {
    background-color: #0096c7;
}

/* Services Section */
.services {
    padding: 60px 20px;
}

.services h2 {
    color: #00ff88;
}

/* Products Section */
.products {
    padding: 60px 20px;
}

.products h2 {
    color: #c77dff;
}

/* Box Container Center */
.services,
.products {
    display: flex;
    flex-direction: column;
    align-items: center;
}

/* Boxes */
.box {
    background-color: #1ac160;
    padding: 20px;
    margin: 15px;
    width: 250px;
    border-radius: 10px;
    border-left: 5px solid #00d4ff;
    text-align: center;
}

/* Hover effect */
.box:hover {
    background-color: #d09816;
    transform: scale(1.05);
}

/* Footer */
footer {
    background-color: #1c2541;
    padding: 15px;
    margin-top: 20px;
}


```





## OUTPUT

<img width="1920" height="1200" alt="Screenshot 2026-02-18 145604" src="https://github.com/user-attachments/assets/62815cdc-c187-4712-99cb-a59b38a65ea8" />


<img width="1920" height="1200" alt="Screenshot 2026-02-18 145616" src="https://github.com/user-attachments/assets/e4c8ea4d-4744-41b9-af9e-f33ca43a5a0f" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
