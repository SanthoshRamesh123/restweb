# Ex.07 Restaurant Website
## Date:27/05/2025

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Logo and Navigation -->
    <header>
        <div class="logo">
            <img src="beacon_restaurants-2.jpg" alt=" beacon_restaurant">
            <h1>beacon restaurants</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="overlay-text">
            <h2>30% Off This Weekend</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer pulvinar tempus quam.</p>
        </div>
        <img src="Spicy-Pasta-recipe-optimised-scaled.webp" alt="Pasta Dish">
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="feature-card">
            <h3>Our New Menu</h3>
            <img src="download.jpg" alt="Grilled Dish">
            <h1>"Farm-fresh veggies kissed by the flame".</h1>
            <h1>The aroma of flame-grilled goodness that makes your mouth water.</h1>
        </div>
        <div class="feature-card">
            <h3>Book a table</h3>
            <img src="th.jpg" alt="Briyani Dish">
            <h1>"A touch of gourmet in every bite." or "Not just a salad, an experience."</h1>
            <h1>Looks as good as it tastes.</h1>
        </div>
        <div class="feature-card">
            <h3>Culinary Team</h3>
            <img src="chef photo.jpg" alt="Chef in the Kitchen">
            <h1>Excellence in every bite, thanks to our chef's dedication.</h1>
            <h1>The chef is the creative mastermind behind the menu, designing dishes that showcase skill, innovation, and taste.</h1>
        </div>
    </section>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <h2>Lavanya</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <h2>Hema</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <h2>Radha</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <h2>Mohan</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <h2>Anu</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <h2>Raji</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by SANTHOSH R</p>
    </footer>
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

      <section class="menu">
    <h1>Our Menu</h1>
    <div class="menu-grid">
      
      <!-- Main Courses -->
      <div class="menu-item">
        <h2>Lemon Herb Grilled Chicken</h2>
        <p>Juicy chicken breasts grilled with zesty lemon and mixed herbs.</p>
        <p class="price">Rs. 280</p>
      </div>
      <div class="menu-item">
        <h2>Creamy Tuscan Paneer</h2>
        <p>Soft paneer cubes in a creamy tomato and spinach sauce.</p>
        <p class="price">Rs. 220</p>
      </div>
      <div class="menu-item">
        <h2>Thai Basil Fried Rice</h2>
        <p>Wok-tossed rice with fresh vegetables, soy, and Thai basil.</p>
        <p class="price">Rs. 180</p>
      </div>
      <div class="menu-item">
        <h2>Butter Garlic Prawns</h2>
        <p>Succulent prawns sautéed in butter and fresh garlic.</p>
        <p class="price">Rs. 350</p>
      </div>

      <!-- Pastas & Noodles -->
      <div class="menu-item">
        <h2>Spaghetti Aglio e Olio</h2>
        <p>Classic pasta with olive oil, garlic, and red chili flakes.</p>
        <p class="price">Rs. 160</p>
      </div>
      <div class="menu-item">
        <h2>Creamy Alfredo Penne</h2>
        <p>Penne pasta in a rich and creamy Alfredo sauce with mushrooms.</p>
        <p class="price">Rs. 200</p>
      </div>

      <!-- Starters & Salads -->
      <div class="menu-item">
        <h2>Cheesy Jalapeño Poppers</h2>
        <p>Spicy jalapeños stuffed with cheese, coated, and fried to perfection.</p>
        <p class="price">Rs. 130</p>
      </div>
      <div class="menu-item">
        <h2>Greek Veggie Salad</h2>
        <p>A refreshing mix of cucumbers, tomatoes, olives, and feta cheese.</p>
        <p class="price">Rs. 150</p>
      </div>
      <div class="menu-item">
        <h2>Spicy Chicken Wings</h2>
        <p>Wings tossed in a hot and tangy buffalo sauce.</p>
        <p class="price">Rs. 190</p>
      </div>

      <!-- Snacks & Street Food -->
      <div class="menu-item">
        <h2>Loaded Nachos</h2>
        <p>Corn chips layered with salsa, beans, cheese, and jalapeños.</p>
        <p class="price">Rs. 170</p>
      </div>
      <div class="menu-item">
        <h2>Tandoori Aloo Tikka</h2>
        <p>Marinated baby potatoes grilled in tandoor-style spices.</p>
        <p class="price">Rs. 120</p>
      </div>
      <div class="menu-item">
        <h2>Masala Corn Cups</h2>
        <p>Sweet corn spiced with lemon, chaat masala, and butter.</p>
        <p class="price">Rs. 80</p>
      </div>

      <!-- Desserts -->
      <div class="menu-item">
        <h2>Lemon Cheesecake</h2>
        <p>Creamy cheesecake with a tangy lemon twist.</p>
        <p class="price">Rs. 150</p>
      </div>
      <div class="menu-item">
        <h2>Chocolate Lava Cake</h2>
        <p>Warm chocolate cake with a gooey molten center.</p>
        <p class="price">Rs. 140</p>
      </div>
      <div class="menu-item">
        <h2>Rose Falooda</h2>
        <p>Classic Indian dessert drink with rose syrup, vermicelli, and ice cream.</p>
        <p class="price">Rs. 110</p>
      </div>

    </div>
  </section>

    <footer>
        <p>Designed by SANTHOSH</p>
    </footer>
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 41/A Restaurant St., City, tamilnadu</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by SANTHOSH R</p>
    </footer>
</body>
</html>
style.css

/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f9f9f9;
    color: #333;
}

/* Header Section */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #222;
    color: #fff;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav li {
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Hero Section */
.hero {
    position: relative;
    text-align: center;
    color: #fff;
}

.hero img {
    width: 100%;
    height: auto;
    opacity: 0.8;
}

.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 2rem;
}

.overlay-text h2 {
    font-size: 3rem;
    font-weight: bold;
}

/* Features Section */
.features {
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
}

.feature-card {
    text-align: center;
    padding: 10px;
    background-color: #fdf0d5;
    border-radius: 10px;
    width: 30%;
}

.feature-card img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

h3 {
    margin: 10px 0;
    font-size: 1.5rem;
    color: #222;
}
```

## OUTPUT:
![Screenshot 2025-05-27 091647](https://github.com/user-attachments/assets/2fa5ab9c-a8f5-4ef3-8702-e8d0fec77c84)
![Screenshot 2025-05-27 091615](https://github.com/user-attachments/assets/d639a339-f913-4383-9db0-1eecf9dedfdb)
![Screenshot 2025-05-27 091701](https://github.com/user-attachments/assets/25507a93-c0ca-4bf2-8d29-0f5e75e5b3e7)
![Screenshot 2025-05-27 091736](https://github.com/user-attachments/assets/8c09474f-84d5-4662-b42f-5bac75402025)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
