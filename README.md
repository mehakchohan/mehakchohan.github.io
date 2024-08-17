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
            background-color: #f0f0f0;
        }
        .main-content h1 {
            font-size: 48px;
            margin: 0;
            font-weight: 700;
            color: #2c3e50;
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
            background-color: #2c3e50;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            border-radius: 5px;
        }
        .projects {
            padding: 50px 0;
            background-color: #ffffff;
            text-align: center;
        }
        .projects h2 {
            font-size: 36px;
            margin-bottom: 40px;
            color: #2c3e50;
        }
        .project-item {
            display: inline-block;
            width: 45%;
            margin: 2.5%;
            vertical-align: top;
        }
        .project-item img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .project-item h3 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        .project-item p {
            font-size: 16px;
            color: #666;
        }
        .contact {
            padding: 50px 0;
            text-align: center;
            background-color: #f0f0f0;
        }
        .contact h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .contact p {
            font-size: 18px;
            color: #666;
            margin-bottom: 10px;
        }
        .contact a {
            font-size: 18px;
            color: #2c3e50;
            text-decoration: none;
            display: block;
            margin: 5px 0;
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

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <!-- Project 1 -->
        <div class="project-item">
            <img src="https://via.placeholder.com/800x400" alt="Project 1">
            <h3>Project Title 1</h3>
            <p>A brief description of what this project is about. You can explain the technologies used and the purpose of the project.</p>
        </div>
        <!-- Project 2 -->
        <div class="project-item">
            <img src="https://via.placeholder.com/800x400" alt="Project 2">
            <h3>Project Title 2</h3>
            <p>A brief description of what this project is about. You can explain the technologies used and the purpose of the project.</p>
        </div>
        <!-- Add more project items as needed -->
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>You can reach out to me via the following contacts:</p>
        <a href="mailto:your.email@example.com">Email: your.email@example.com</a>
        <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn: yourprofile</a>
        <!-- Add more contact links as needed -->
    </section>

    <footer>
        <p>&copy; 2024 Mehak Chohan. All Rights Reserved.</p>
    </footer>

</body>
</html>
