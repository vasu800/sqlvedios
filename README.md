<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Website - Home</title>
    <style>
    body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 10px;
}

a {
    text-decoration: none;
    color: white;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
}
<style>
</head>
<body>
    <header>
        <h1>Your Website</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Welcome to Our Website</h2>
            <p>This is the home page content.</p>
            <img src="home-image.jpg" alt="Home Image">
            <video width="320" height="240" controls>
                <source src="home-video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>


