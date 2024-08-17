<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mehak Chohan | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
            border-bottom: 1px solid #eee;
        }
        header .logo {
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #333;
        }
        header nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        header nav ul li {
            display: inline;
        }
        header nav ul li a {
            text-decoration: none;
            color: #333;
            text-transform: uppercase;
            font-size: 14px;
        }
        .main-content {
            text-align: center;
            padding: 100px 0;
        }
        .main-content h1 {
            font-size: 48px;
            margin: 0;
            font-weight: 700;
            color: #000;
        }
        .main-content p {
            font-size: 20px;
            color: #666;
            margin: 20px 0;
        }
        .main-content a {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #000;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            border-radius: 5px;
        }
        section {
            padding: 60px 0;
        }
        .projects {
            background-color: #f9f9f9;
        }
        .projects h2 {
            text-align: center;
            font-size: 36px;
            color: #333;
        }
        .project-list {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 40px;
        }
        .project-item {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 48%;
        }
        .project-item h3 {
            font-size: 24px;
            margin-top: 0;
        }
        .project-item p {
            color: #666;
        }
        .contact {
            background-color: #333;
            color: #fff;
        }
        .contact h2 {
            text-align: center;
            font-size: 36px;
            color: #fff;
        }
        .contact form {
            max-width: 600px;
            margin: 20px auto;
            text-align: center;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .contact input[type="submit"] {
            background-color: #000;
            color: #fff;
            text-transform: uppercase;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
            border-top: 1px solid #eee;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>

    <header class="container">
        <div class="logo">
            MC.
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="main-content">
        <h1>I'm Mehak Chohan</h1>
        <p>Sophomore Student at the University of Michigan, passionate about software development and AI.</p>
        <p>Working on making meaningful contributions to the tech world.</p>
        <a href="#about">See More About Me</a>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-list">
                <div class="project-item">
                    <h3>Project 1</h3>
                    <p>Brief description of your project. You can explain what it is, how it works, and what technologies you used.</p>
                </div>
                <div class="project-item">
                    <h3>Project 2</h3>
                    <p>Brief description of your project. You can explain what it is, how it works, and what technologies you used.</p>
                </div>
                <!-- Add more project items as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Mehak Chohan. All Rights Reserved.</p>
    </footer>

</body>
</html>
