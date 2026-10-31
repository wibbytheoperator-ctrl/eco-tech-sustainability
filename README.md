# eco-tech-sustainability
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eco-Tech and Sustainability</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1> Eco-Tech</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#technology">Technology</a>
        <a href="#tips">Tips</a>
    </nav>
</header>

<section id="home" class="hero">
    <h2>Technology for a Greener Future</h2>
    <p>Protecting our planet through innovation and sustainability.</p>
    <a href="#about" class="btn">Explore More</a>
</section>

<section id="about">
    <h2>About Eco-Tech</h2>
    <p>
        Eco-Tech combines technology and environmental protection
        to create a cleaner, greener, and healthier world.
    </p>
</section>

<section id="technology">
    <h2>Eco-Friendly Technologies</h2>

    <div class="container">
        <div class="card">
            <h3> Solar Energy</h3>
            <p>Uses sunlight to produce clean electricity.</p>
        </div>

        <div class="card">
            <h3> Wind Energy</h3>
            <p>Uses wind power to generate renewable energy.</p>
        </div>

        <div class="card">
            <h3> Electric Vehicles</h3>
            <p>Helps reduce pollution from transportation.</p>
        </div>
    </div>
</section>

<section id="tips">
    <h2>Sustainability Tips</h2>
    <ul>
        <li>Reduce, reuse, and recycle.</li>
        <li>Save electricity and water.</li>
        <li>Plant more trees.</li>
        <li>Avoid single-use plastics.</li>
        <li>Use eco-friendly products.</li>
    </ul>
</section>

<footer>
    <p>© 2026 Eco-Tech and Sustainability</p>
    <p>Go Green, Save the Planet! </p>
</footer>

<script src="script.js"></script>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #f0f8f0;
    color: #333;
}

header {
    background: #14532d;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
}

.hero {
    background: #86c98b;
    text-align: center;
    padding: 100px 20px;
    color: #123b20;
}

.hero h2 {
    font-size: 35px;
    margin-bottom: 15px;
}

.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: #14532d;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 50px 20px;
    text-align: center;
}

.container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 25px;
}

.card {
    background: white;
    padding: 25px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 3px 8px #aaa;
}

ul {
    display: inline-block;
    text-align: left;
    line-height: 2;
}

footer {
    background: #14532d;
    color: white;
    text-align: center;
    padding: 20px;
}

@media (max-width: 600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        display: inline-block;
        margin: 5px;
    }
}


alert("Welcome to Eco-Tech and Sustainability!");

console.log("Let's protect our planet!");
