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
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #2c3e50;
            color: #fff;
            padding: 15px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
            text-align: right;
        }
        header ul li {
            display: inline;
            padding: 0 15px;
        }
        header .logo {
            float: left;
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        header nav {
            float: right;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
            height: 600px;
            text-align: center;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .hero h1 {
            font-size: 60px;
            margin: 0;
            text-transform: uppercase;
            background-color: rgba(0, 0, 0, 0.6);
            padding: 10px 20px;
            border-radius: 5px;
        }
        .hero p {
            font-size: 24px;
            margin-top: 10px;
            background-color: rgba(0, 0, 0, 0.6);
            padding: 10px 20px;
            border-radius: 5px;
        }
        .about-me {
            padding: 50px 0;
            text-align: center;
            background-color: #ecf0f1;
        }
        .about-me h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .about-me p {
            font-size: 18px;
            width: 70%;
            margin: auto;
            color: #34495e;
        }
        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">
                Mehak Chohan
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Mehak Chohan | Sophomore Student at the University of Michigan</p>
    </section>

    <section id="about" class="about-me">
        <h2>About Me</h2>
        <p>
            I am a sophomore at the University of Michigan studying Computer Science. I am passionate about software development, artificial intelligence, and eager to gain experience in the tech industry. My goal is to contribute to impactful projects and develop innovative solutions.
        </p>
    </section>

    <footer>
        <p>&copy; 2024 Mehak Chohan. All Rights Reserved.</p>
    </footer>

</body>
</html>
