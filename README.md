<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TF2 Themed Website</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Alfa+Slab+One&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #3e2a19; /* TF2 Official Website Background Color */
            color: #fff;
            font-family: 'Alfa Slab One', cursive;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav a {
            color: #f0a030;
            text-decoration: none;
        }
        .hero {
            padding: 50px;
        }
        button {
            background-color: #a85225;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        button:hover {
            background-color: #d2691e;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Classes</a></li>
                <li><a href="#">Weapons</a></li>
                <li><a href="#">Maps</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <h1>Welcome to the TF2 Fan Site</h1>
        <p>"Grass grows, birds fly, sun shines, and brotha' - I hurt people."</p>
        <button>Join the Fight</button>
    </section>
    
    <footer>
        <p>&copy; 2025 TF2 Fan Site. Not affiliated with Valve.</p>
    </footer>
</body>
</html>
