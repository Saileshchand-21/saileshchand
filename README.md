# saileshchand
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Gym</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home</h2>
        <p>Welcome to the best gym in town. We offer state-of-the-art equipment and professional trainers.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Our gym has been serving the community for over 10 years. We are dedicated to helping you achieve your fitness goals.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Personal Training</li>
            <li>Group Classes</li>
            <li>Nutrition Counseling</li>
            <li>Yoga and Pilates</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Gym Website. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
