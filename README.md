# landing-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color:hsl(244, 69%, 82%);
            padding: 20px 0;
            color: #000000;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
            display: flex;
            align-items: center;
        }

        header h1 img {
            margin-right: 15px;
            border-radius: 50%;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #000000;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background-color: #f4f4f4;
            text-align: center;
            padding: 60px 0;
        }

        .hero h2 {
            margin: 0 0 20px;
            font-size: 2.5em;
            color: #333;
        }

        .hero p {
            font-size: 1.2em;
            margin: 0 0 20px;
        }

        .cta-button {
            background-color:hsl(244, 69%, 82%);
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
        }

        .features {
            padding: 40px 0;
            background-color:hsl(244, 69%, 82%);
        }

        .features .container {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }

        .feature {
            background-color:  hsl(150, 100%, 99%);
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            flex: 1;
        }

        footer {
            background-color: #fbfeff;
            color: #000000;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>
                <img src="images.jpeg" alt="Logo">
                Welcome to My Landing Page
            </h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h2>Discover the Beauty of Web Design</h2>
                <p>Learn to create stunning websites with our easy-to-follow tutorials.</p>
                <p>                 </p>
                <a href="#" class="cta-button">Get Started</a>
            </div>
        </section>

        <section class="features">
            <div class="container">
                <div class="feature">
                    <h3>Feature One</h3>
                    <p>Learn the basics of HTML and CSS to build your first webpage.</p>
                </div>
                <div class="feature">
                    <h3>Feature Two</h3>
                    <p>Explore advanced CSS techniques to enhance your designs.</p>
                </div>
                <div class="feature">
                    <h3>Feature Three</h3>
                    <p>Understand responsive design to make your pages mobile-friendly.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
