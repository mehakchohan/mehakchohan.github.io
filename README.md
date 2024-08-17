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

    <footer>
        <p>&copy; 2024 Mehak Chohan. All Rights Reserved.</p>
    </footer>

</body>
</html>
