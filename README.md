<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TF2 Themed Website</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Alfa+Slab+One&family=Bigshot+One&display=swap" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to bottom, #2a1e16, #3e2a19);
            color: #fff;
            font-family: 'Bigshot One', cursive;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: rgba(50, 40, 30, 0.95);
            padding: 20px;
            border-radius: 10px;
        }
        header {
            background: #2a1e16;
            padding: 20px 0;
        }
        h1 {
            color: #f0a030;
            font-family: 'Alfa Slab One', cursive;
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
            font-size: 18px;
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
            font-size: 16px;
        }
        button:hover {
            background-color: #d2691e;
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background: #2a1e16;
        }
    </style>
</head>
<body>
    <header>
        <h1>Team Fortress 2 Fan Site</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">History</a></li>
                <li><a href="#">Artwork</a></li>
            </ul>
        </nav>
    </header>
    
    <div class="container">
        <section class="hero">
            <h1>Welcome to the TF2 Fan Site</h1>
            <p>"Grass grows, birds fly, sun shines, and brotha' - I hurt people."</p>
            <button>Join the Fight</button>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2025 TF2 Fan Site. Not affiliated with Valve.</p>
    </footer>
</body>
</html>
