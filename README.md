<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet Delights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff3e0;
        }
        header {
            background-color: #d32f2f;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .recipe img {
            width: 100%;
            max-width: 400px;
            margin: 10px;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #b71c1c;
            color: white;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Gourmet Delights</h1>
    <nav>
        <a href="#about">About Us</a>
        <a href="#recipes">Recipes</a>
        <a href="#tips">Culinary Tips</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to Gourmet Delights! We are passionate about sharing delicious recipes and culinary tips to inspire your cooking adventures. Join us as we explore the world of gourmet cuisine!</p>
</section>

<section id="recipes">
    <h2>Our Recipes</h2>
    <div class="recipe">
        <h3>Spaghetti Carbonara</h3>
        <img src="https://via.placeholder.com/400?text=Spaghetti+Carbonara" alt="Spaghetti Carbonara">
        <p>A classic Italian pasta dish made with eggs, cheese, pancetta, and pepper.</p>
    </div>
    <div class="recipe">
        <h3>Chocolate Lava Cake</h3>
        <img src="https://via.placeholder.com/400?text=Chocolate+Lava+Cake" alt="Chocolate Lava Cake">
        <p>A rich and gooey chocolate cake with a molten center that will delight chocolate lovers.</p>
    </div>
    <div class="recipe">
        <h3>Caesar Salad</h3>
        <img src="https://via.placeholder.com/400?text=Caesar+Salad" alt="Caesar Salad">
        <p>A fresh salad with romaine lettuce, croutons, and Caesar dressing.</p>
    </div>
</section>

<section id="tips">
    <h2>Culinary Tips</h2>
    <ul>
        <li>Always taste your food as you cook to adjust seasoning.</li>
        <li>Use fresh herbs for better flavor in your dishes.</li>
        <li>Let meat rest after cooking for a juicier result.</li>
        <li>Invest in good quality kitchen tools for a better cooking experience.</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <input type="submit" value="Submit">
    </form>
</section>

<footer>
    <p>&copy; 2024 Gourmet Delights. All rights reserved.</p>
</footer>

</body>
</html>
