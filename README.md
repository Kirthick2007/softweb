# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
## DEVELOPED BY : KIRTHICK SHA R
## REG NO : 212224230124
## HOME.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sha Hotel - Home</title>
  <style>
   
    body {
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background-image: url('d1.jpg'); 
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      color: #ffffff;
    }

    .overlay {
      background: rgba(0, 0, 0, 0.65);
      min-height: 100vh;
      backdrop-filter: blur(2px);
    }

    header {
      background: rgba(0, 12, 91, 0.85);
      padding: 25px 0;
      text-align: center;
      border-bottom: 2px solid rgba(255, 255, 255, 0.2);
    }

    header h1 {
      margin: 0;
      font-size: 40px;
      letter-spacing: 1px;
      font-weight: 700;
    }

    header p {
      margin: 5px 0 0;
      font-size: 18px;
      opacity: 0.9;
    }

    nav {
      background: rgba(0, 12, 91, 0.85);
      padding: 12px 0;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.25);
    }

    nav a {
      font-size: 18px;
      font-weight: 600;
      color: #ffecb3;
      margin: 0 20px;
      text-decoration: none;
      padding: 8px 12px;
      border-radius: 6px;
      transition: 0.3s ease;
    }

    nav a:hover {
      background: #ffecb3;
      color: #001152;
    }

    section {
      padding: 120px 30px;
      text-align: center;
    }

    section h2 {
      font-size: 42px;
      color: #ffd966;
      margin-bottom: 15px;
      text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.4);
    }

    section p {
      font-size: 20px;
      max-width: 750px;
      margin: 20px auto;
      line-height: 1.6;
      color: #fef9c3;
    }

    footer {
      background: rgba(0, 12, 91, 0.85);
      padding: 12px;
      text-align: center;
      font-weight: 600;
      font-size: 16px;
      color: #ffecb3;
      border-top: 2px solid rgba(255, 255, 255, 0.2);
      position: fixed;
      bottom: 0;
      width: 100%;
      letter-spacing: 0.5px;
    }

  </style>
</head>

<body>
  <div class="overlay">

    <header>
      <h1>🍗 Welcome to Sha Hotel 🍗</h1>
      <p>The Home of Authentic Flavors</p>
    </header>

    <nav>
      <a href="home.html">Home</a>
      <a href="food.html">Our Food</a>
      <a href="chef.html">Our Chefs</a>
      <a href="contact.html">Contact</a>
    </nav>

    <section>
      <h2>Delicious Biryani Awaits You!</h2>
      <p>
        Experience the rich tradition of Hyderabadi, Dum, and Chicken Biryani prepared with premium ingredients, aromatic spices, and an authentic touch of love.  
        Taste the royal flavors of India — only at Sha Hotel.
      </p>
    </section>

    <footer>
      © 2025 Sha Hotel | Taste the Royal Tradition
    </footer>

  </div>
</body>
</html>


```
## FOOD.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Biryani House - Food Menu</title>
  <style>
    body { background-color: #fff8f0; font-family: Arial; margin: 0; }
    header, footer { background-color: rgba(0, 12, 91, 0.85); color: white; text-align: center; padding: 15px; }
    nav { background-color: rgba(0, 12, 91, 0.85); text-align: center; padding: 10px; }
    nav a { color: white; margin: 15px; text-decoration: none; font-weight: bold; }
    h2 { text-align: center; color: #b45309; }
    .menu {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      padding: 30px;
    }
    .item {
      background-color: #fff;
      border: 2px solid #fbbf24;
      border-radius: 10px;
      width: 250px;
      text-align: center;
      padding: 15px;
    }
    img { border-radius: 10px; width: 200px; height: 150px; }
  </style>
</head>
<body>
  <header><h1>Our Special Menu</h1></header>
  <nav>
    <a href="home.html">Home</a>
    <a href="food.html">Our Food</a>
    <a href="chef.html">Our Chefs</a>
    <a href="contact.html">Contact</a>
  </nav>
  
  <h2>Signature Dishes</h2>
  <div class="menu">
    <div class="item">
      <img src="chicken 1.jpeg" alt="Chicken Biryani">
      <h3>Chicken Biryani</h3>
      <p>₹180 | Spicy & aromatic traditional biryani</p>
    </div>
    <div class="item">
      <img src="mutton1.jpg" alt="Mutton Biryani">
      <h3>Mutton Biryani</h3>
      <p>₹250 | Slow-cooked with rich masala</p>
    </div>
    <div class="item">
      <img src="veg 1.jpeg" alt="Veg Biryani">
      <h3>Veg Biryani</h3>
      <p>₹150 | Perfect for vegetarians</p>
    </div>
  </div>

  <footer>© 2025 Biryani House | Spreading Aroma Everywhere</footer>
</body>
</html>

```
## CHEF.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Biryani House - Our Chefs</title>
  <style>
    body { background-color: #fff8f0; font-family: Arial; margin: 0; }
    header, footer { background-color: rgba(0, 12, 91, 0.85); color: white; text-align: center; padding: 15px; }
    nav { background-color: rgba(0, 12, 91, 0.85); text-align: center; padding: 10px; }
    nav a { color: white; margin: 15px; text-decoration: none; font-weight: bold; }
    .chefs {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      padding: 40px;
    }
    .chef {
      background-color: #fff;
      border: 2px solid #fbbf24;
      border-radius: 10px;
      width: 250px;
      text-align: center;
      padding: 20px;
    }
    img { width: 200px; height: 200px; border-radius: 50%; }
  </style>
</head>
<body>
  <header><h1>Meet Our Chefs</h1></header>
  <nav>
    <a href="home.html">Home</a>
    <a href="food.html">Our Food</a>
    <a href="chef.html">Our Chefs</a>
    <a href="contact.html">Contact</a>
  </nav>

  <div class="chefs">
    <div class="chef">
      <img src="chef1.png" alt="Chef 1">
      <h3>John paul</h3>
      <p>Master of Hyderabadi Dum Biryani</p>
    </div>
    <div class="chef">
      <img src="chef2.png" alt="Chef 2">
      <h3>Emijackson</h3>
      <p>Expert in South Indian Spice Blends</p>
    </div>
  </div>

  <footer>© 2025 Biryani House | Cooked with Love</footer>
</body>
</html>

```
## CONTACT.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Biryani House - Contact Us</title>
  <style>
    body { background-color: #fff8f0; font-family: Arial; margin: 0; }
    header, footer { background-color: rgba(0, 12, 91, 0.85); color: white; text-align: center; padding: 15px; }
    nav { background-color: rgba(0, 12, 91, 0.85); text-align: center; padding: 10px; }
    nav a { color: white; margin: 15px; text-decoration: none; font-weight: bold; }
    form {
      background-color: #fff;
      max-width: 400px;
      margin: 50px auto;
      border: 2px solid #fbbf24;
      border-radius: 10px;
      padding: 20px;
    }
    input, textarea {
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background-color: rgba(0, 12, 91, 0.85);
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover { background-color: rgba(0, 12, 91, 0.85); }
  </style>
</head>
<body>
  <header><h1>Contact Us</h1></header>
  <nav>
    <a href="home.html">Home</a>
    <a href="food.html">Our Food</a>
    <a href="chef.html">Our Chefs</a>
    <a href="contact.html">Contact</a>
  </nav>

  <form>
    <h3>Send us a message</h3>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Your Message" rows="4" required></textarea>
    <button type="submit">Send Message</button>
  </form>

  <footer>© 2025 Biryani House | Visit us: 123 Food Street, Chennai</footer>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2025-11-13 114727-1.png>)
![alt text](<Screenshot 2025-11-13 114919-1.png>)
![alt text](<Screenshot 2025-11-13 114936-1.png>)
![alt text](<Screenshot 2025-11-13 115000-1.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
