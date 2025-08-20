# Ex02 Commercial Website
## Date: 14/08/25

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
## html code 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Business</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Sathya Fashions</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Orders</a></li>
                    <li><a href="#">Cart</a></li>
                    <li><a href="#">Account</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h3>New Offers!</h3>
            <img src="premium-face-cream-banner-ads-260nw-1204702888.webp" alt="Offer Banner">
            <a href="#" class="btn">View More</a>
        </div>
    </section>

    <section class="services">
        <div class="container">
            <div class="service">
                <img src="IMG-20240820-WA0186-741x640.jpg" alt="Wishcare Serum">
                <h3>Wishcare Hair Growth Serum</h3>
                <p>Concentrate With 3% Redensyl, 4% Anagain, Rice Water, Biotin (30ml)</p>
            </div>
            <div class="service">
                <img src="download.jpeg" alt="Ponds Cream">
                <h3>Ponds Age Miracle</h3>
                <p>Anti Aging Day Cream With 10% Retinol-C Niacinamide (30ml)</p>
            </div>
            <div class="service">
                <img src="619zXxIq0RL.jpg" alt="Cetaphil Cleanser">
                <h3>Cetaphil Cleanser</h3>
                <p>Gentle Skin Cleanser Dry to Normal Skin with Niacinamide (125ml)</p>
            </div>
            <div class="service">
                <img src="images.jpeg" alt="Nykaa So Creme">
                <h3>Nykaa So Creme!</h3>
                <p>Infused with the nourishing benefits of Vitamin E and Almond Oil (4.2g)</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 SATHYA E-RETAIL LIMITED All Rights Reserved.</p>
    </footer>
</body>
</html>

```
## CSS code
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background: #db599e;
    padding: 20px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.container {
    width: 90%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.hero {
    background: #ffe6ef;
    text-align: center;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.hero img {
    max-width: 100%;
    border-radius: 10px;
    display: block;
    margin: 0 auto; 
}

.hero .btn {
    display: inline-block;
    background: #a10f7d;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    margin-top: 20px;
    border-radius: 5px;
    align-self: center; 
}

.services {
    padding: 50px 0;
    background: #f9f9f9;
    text-align: center;
}

.services .container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.service {
    width: 22%;
    padding: 20px;
    background: #fff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
}

.service img {
    width: 50px;
    height: 50px;
}

.projects {
    padding: 50px 0;
    text-align: center;
}

.project-gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.project img {
    width: 250px;
    height: 150px;
    border-radius: 5px;
}

footer {
    background: #7a0a47;
    color: #fff;
    text-align: center;
    padding: 15px;
    position: relative;
    bottom: 0;
    width: 100%;
}
```
## OUTPUT
<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/5df2e382-ce6e-4e0b-a09f-313f5d2a0ea2" />
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/f67d6b9c-a29e-4ef1-a1fa-b0ade4cdf9e1" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
