# site1<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investment Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Investment Tracker</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to Investment Tracker, where you can manage and track your investments effortlessly.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Portfolio Management</li>
            <li>Investment Advice</li>
            <li>Market Analysis</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Investment Tracker. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
