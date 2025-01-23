<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Website</title>
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
            padding: 1rem 0;
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
            padding: 1rem;
            max-width: 800px;
            margin: auto;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
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
        <h2>Contact</h2>
        <p>Feel free to reach out to me on <a href="https://github.com/yourgithubusername" target="_blank">GitHub</a> or connect with me on <a href="mailto:yourname@email.com">email</a>.</p>
    </section>
</div>

<footer>
    <p>&copy; 2025 Your Name. All Rights Reserved.</p>
</footer>

</body>
</html>
