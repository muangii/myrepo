# myrepo
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal Portfolio Website">
    <title>Your Name - Portfolio</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: maroon;
            padding: 20px;
            text-align: center;
            color: white;
        }

        header h1 {
            font-size: 2.5rem;
        }

        nav {
            text-align: center;
            margin-top: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            padding: 8px 16px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #fff;
            color: maroon;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        .about-me, .skills, .contact {
            margin: 20px auto;
            max-width: 900px;
        }

        .about-me h2, .skills h2, .contact h2 {
            font-size: 2rem;
            color: maroon;
        }

        .about-me p, .skills ul, .contact form {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        .skills ul {
            list-style: none;
            padding: 0;
        }

        .skills ul li {
            margin-bottom: 10px;
        }

        footer {
            background-color: maroon;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer p {
            font-size: 1rem;
        }

        footer a {
            color: white;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <p>Welcome to my personal portfolio</p>
</header>

<nav>
    <a href="#about-me">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about-me" class="about-me">
    <h2>About Me</h2>
    <p>
        I am a passionate professional with a love for creating dynamic and impactful solutions.
        My background in Data Science and experience in various technical fields has enabled me to
        develop a unique set of skills, ranging from data analysis to machine learning.
    </p>
</section>

<section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
        <li>Data Science</li>
        <li>Python, R, SQL</li>
        <li>Machine Learning Algorithms</li>
        <li>Data Visualization (Tableau, PowerBI)</li>
        <li>Cloud Computing (AWS, GCP)</li>
    </ul>
</section>

<section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
        <input type="text" placeholder="Your Name" required><br><br>
        <input type="email" placeholder="Your Email" required><br><br>
        <textarea placeholder="Your Message" required></textarea><br><br>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Your Name | <a href="https://www.linkedin.com/in/yourname">LinkedIn</a> | <a href="mailto:your.email@example.com">Email</a></p>
</footer>

<script>
    // Form submission behavior (just a placeholder)
    document.querySelector('form').addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Your message has been sent!');
    });
</script>

</body>
</html>
