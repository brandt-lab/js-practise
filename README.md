# js-practise
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A basic HTML5 template">
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
</head>
<body>
<h1>Hi world !!! this is elkanah</h1>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website.</p>
        </section>

        <section id="about">
            <h2>About</h2>
            <p>This section provides information about the website or company.</p>
        </section>

        <section id="services">
            <h2>Services</h2>
            <p>Here are the services we offer:</p>
            <ul>
                <li>Web Development</li>
                <li>SEO Optimization</li>
                <li>Graphic Design</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Get in touch with us!</p>
            <form action="/submit" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 My Website. All rights reserved.</p>
    </footer>

    <script src="script.js"></script> <!-- Link to external JavaScript file -->
</body>
</html>
