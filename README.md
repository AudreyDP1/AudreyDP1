<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Pink Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Pink Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is a sample website with a pink theme. You can customize it with your own content.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>About section content goes here.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Contact information goes here.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #ffe4e1; /* Light pink background */
    color: #333;
    margin: 0;
    padding: 0;
}

header {
    background-color: #ffb6c1; /* Pink header */
    color: white;
    text-align: center;
    padding: 1em 0;
}

nav {
    background-color: #ff69b4; /* Hot pink navigation */
    padding: 0.5em;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 2em;
}

section {
    margin-bottom: 2em;
}

footer {
    background-color: #ffb6c1;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
