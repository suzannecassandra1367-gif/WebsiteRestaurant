# Ex.06 Restaurant Website
## Date:24.12.2025

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
  <title>Pizza Palace</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:Arial, sans-serif;
      background:#fff5e6;
      color:#333;
    }

    header{
      background:#d32f2f;
      padding:20px;
      text-align:center;
    }

    header h1{
      color:white;
      font-size:32px;
    }

    nav{
      background:#b71c1c;
      padding:15px;
      text-align:center;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin:0 15px;
      font-weight:bold;
    }

    .hero{
      background:url('https://images.unsplash.com/photo-1513104890138-7c749659a591?w=1200&h=600&fit=crop') center/cover;
      height:400px;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .hero h2{
      background:rgba(211,47,47,0.9);
      color:white;
      padding:20px 40px;
      border-radius:10px;
      font-size:24px;
    }

    section{
      padding:40px 20px;
      max-width:1200px;
      margin:0 auto;
    }

    h2{
      text-align:center;
      color:#d32f2f;
      margin-bottom:30px;
      font-size:28px;
    }

    .about{
      text-align:center;
      font-size:18px;
      line-height:1.8;
      max-width:800px;
      margin:0 auto;
    }

    .menu{
      display:flex;
      flex-wrap:wrap;
      gap:20px;
      justify-content:center;
    }

    .menu-card{
      background:white;
      width:250px;
      border-radius:10px;
      box-shadow:0 2px 8px rgba(0,0,0,0.1);
      overflow:hidden;
    }

    .menu-card img{
      width:100%;
      height:160px;
      object-fit:cover;
    }

    .menu-card div{
      padding:15px;
      text-align:center;
    }

    .menu-card h3{
      color:#d32f2f;
      margin-bottom:5px;
    }

    .menu-card p{
      color:#ff6f00;
      font-weight:bold;
      font-size:18px;
    }

    .menu-section{
      margin-bottom:50px;
    }

    .contact{
      background:#d32f2f;
      color:white;
      text-align:center;
      padding:40px 20px;
    }

    .contact h2{
      color:white;
    }

    .contact p{
      margin:8px 0;
      font-size:16px;
    }

    footer{
      background:#8b0000;
      color:white;
      text-align:center;
      padding:15px;
    }

    @media(max-width:768px){
      nav a{
        display:block;
        margin:5px 0;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>🍕 PIZZA PALACE</h1>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#menu">Menu</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
  <h2>Hot & Fresh Pizza Delivered to You!</h2>
</div>

<section id="about">
  <h2>About Us</h2>
  <p class="about">
    Welcome to Pizza Palace! We serve delicious wood-fired pizzas made with fresh ingredients. 
    From classic favorites to unique creations, we have something for everyone. 
    Order now and taste the difference!
  </p>
</section>

<section id="menu">
  <h2>Our Menu</h2>

  <div class="menu-section">
    <h3 style="text-align:center; color:#555; margin-bottom:20px;">🍕 Pizzas</h3>
    <div class="menu">
      <div class="menu-card">
        <img src="Marg.jpg" alt="Margherita">
        <div>
          <h3>Margherita</h3>
          <p>₹350</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="pepporoni.jpg" alt="Pepperoni">
        <div>
          <h3>Pepperoni</h3>
          <p>₹450</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="veggie.jpg" alt="Veggie">
        <div>
          <h3>Veggie Supreme</h3>
          <p>₹400</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="bbqpizza.jpg" alt="BBQ Chicken">
        <div>
          <h3>BBQ Chicken</h3>
          <p>₹480</p>
        </div>
      </div>
    </div>
  </div>

  <div class="menu-section">
    <h3 style="text-align:center; color:#555; margin-bottom:20px;">🥤 Beverages</h3>
    <div class="menu">
      <div class="menu-card">
        <img src="cokee.jpg" alt="Coke">
        <div>
          <h3>Coke</h3>
          <p>₹80</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="lemonade.jpeg" alt="Lemonade">
        <div>
            
          <h3>Fresh Lemonade</h3>
          <p>₹100</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="icetea.jpg" alt="Iced Tea">
        <div>
          <h3>Iced Tea</h3>
          <p>₹90</p>
        </div>
      </div>
    </div>
  </div>

  <div class="menu-section">
    <h3 style="text-align:center; color:#555; margin-bottom:20px;">🍗 Side Dishes</h3>
    <div class="menu">
      <div class="menu-card">
        <img src="garlicbread.jpg" alt="Garlic Bread">
        <div>
          <h3>Garlic Bread</h3>
          <p>₹150</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="chickenwings.jpg" alt="Chicken Wings">
        <div>
          <h3>Chicken Wings</h3>
          <p>₹280</p>
        </div>
      </div>

      <div class="menu-card">
        <img src="frenchfries.jpg" alt="French Fries">
        <div>
          <h3>French Fries</h3>
          <p>₹120</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>📍 Chennai, India</p>
  <p>📞 +91 98765 43210</p>
  <p>✉ pizzapalace@email.com</p>
  <p>CASS</p>
  <p>25000390</p>
</section>

<footer>
  <p>© 2025 Pizza Palace - All Rights Reserved</p>
</footer>

</body>
</html>
```

## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
