body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: #007bff;
    color: white;
    padding: 15px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
}

section {
    margin: 30px;
}

.gallery img {
    width: 200px;
    height: auto;
    margin: 10px;
    border-radius: 5px;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
}

footer {
    margin-top: 30px;
    background-color: #f1f1f1;
    padding: 10px;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Graphic Design Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Graphic Design Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Welcome!</h2>
        <p>I'm a graphic designer passionate about creating stunning visuals.</p>
    </section>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="gallery">
            <img src="images/design1.jpg" alt="Design 1">
            <img src="images/design2.jpg" alt="Design 2">
            <img src="images/design3.jpg" alt="Design 3">
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Find me on <a href="https://www.fiverr.com/" target="_blank">Fiverr</a> or email me at <strong>your-email@example.com</strong></p>
    </section>
    
    <footer>
        <p>&copy; 2025 My Portfolio</p>
    </footer>
</body>
</html>
