# my-website


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gloria and Buzz Bee</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FFF8DC;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #FFEB3B;
            color: #333;
            text-align: center;
            padding: 2em 0;
            position: relative;
        }
        header img {
            width: 50px;
            height: 50px;
            position: absolute;
            top: 20px;
            left: 20px;
            animation: spin 4s linear infinite;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            font-family: 'Courier New', Courier, monospace;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        nav {
            background-color: #333;
            color: #FFF;
            text-align: center;
            padding: 1em 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: #FFF;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2em;
            transition: background-color 0.3s ease;
        }
        section:hover {
            background-color: #FFEB3B;
        }
        .about, .portfolio, .contact {
            max-width: 800px;
            margin: 0 auto;
        }
        .about p, .contact p {
            line-height: 1.6;
        }
        .portfolio img {
            width: 100%;
            height: auto;
            margin-bottom: 1em;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            background-color: #333;
            color: #FFF;
            text-align: center;
            padding: 1em 0;
        }
        .social-icons {
            margin: 1em 0;
        }
        .social-icons a {
            color: #FFF;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.5em;
        }
    </style>
</head>
<body>
    <header>
        <img src="bee.png" alt="Bee logo">
        <h1>Gloria and Buzz Bee</h1>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Hello! We are Gloria and Buzz Bee, a dynamic duo with a passion for creativity and nature. Our work is inspired by the beauty and complexity of bees, and we aim to bring a touch of that magic to everything we do. Whether it's through our art, our writing, or our community projects, we strive to make the world a brighter, more vibrant place.</p>
    </section>
    <section id="portfolio" class="portfolio">
        <h2>Portfolio</h2>
        <p>Take a look at some of our favorite projects:</p>
        <img src="project1.jpg" alt="Project 1">
        <img src="project2.jpg" alt="Project 2">
        <img src="project3.jpg" alt="Project 3">
    </section>
    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>We'd love to hear from you! Whether you have a question, a project in mind, or just want to say hi, feel free to reach out.</p>
        <p>Email: <a href="mailto:gloriaandbuzz@beemail.com">gloriaandbuzz@beemail.com</a></p>
        <div class="social-icons">
            <a href="https://twitter.com/gloriaandbuzz" target="_blank">🐝</a>
            <a href="https://facebook.com/gloriaandbuzz" target="_blank">📘</a>
            <a href="https://instagram.com/gloriaandbuzz" target="_blank">📸</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Gloria and Buzz Bee. All rights reserved.</p>
    </footer>
</body>
</html>



