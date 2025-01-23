<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website: A work in progress...</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 1rem 0;
        }
        nav a {
            text-decoration: none;
            color: #333;
            padding: 0.5rem 1rem;
            border: 1px solid #333;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }
        nav a:hover {
            background-color: #333;
            color: #fff;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }
        section {
            margin-bottom: 2rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }
        .contact {
            text-align: center;
            margin-top: 2rem;
        }
        .contact a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .contact a:hover {
            color: #0077b5;
        }
        .resume {
            text-align: center;
            margin-top: 2rem;
        }
        .resume a {
            text-decoration: none;
            color: #333;
            border: 1px solid #333;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            display: inline-block;
            margin-top: 1rem;
            transition: background-color 0.3s, color 0.3s;
        }
        .resume a:hover {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Personal Website</h1>
    <p>Your one-stop destination to explore my projects and portfolio.</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I am a passionate bioinformatician and graduate student at Boston University. I specialize in computational biology, data analysis, and molecular docking. Welcome to my portfolio!</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <strong>R Shiny App for RNASeq Analysis:</strong> An interactive tool for analyzing gene expression in Huntington's Disease patients.
            </li>
            <li>
                <strong>Computational Docking Analysis:</strong> Explored binding sites of key proteins in neurodegenerative diseases.
            </li>
            <li>
                <strong>Network Pharmacology:</strong> Virtual screening of traditional herbs for hypoglycemic activity.
            </li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:abasyal@bu.edu">abasyal@bu.edu</a></p>
        <p>GitHub: <a href="https://github.com/anuradhabasyal" target="_blank">github.com/anuradhabasyal</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/anuradha-basyal-45311a188/" target="_blank">linkedin.com/in/anuradha-basyal</a></p>
    </section>

    <section class="resume">
        <h2>Resume</h2>
        <p>Click below to view or download my resume:</p>
        <a href="/path/to/your-resume.pdf" target="_blank">View Resume</a>
    </section>
</div>

<footer>
    <p>&copy; 2025 Anuradha Basyal. All Rights Reserved.</p>
</footer>

</body>
</html>
