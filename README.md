<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Arushi Shrivastava - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Lobster&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: linear-gradient(to right, #fffaf0, #f4e3d9);
            overflow-x: hidden;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes scaleUp {
            from { transform: scale(0.9); }
            to { transform: scale(1); }
        }

        .header {
            background-color: #a46a45;
            color: white;
            padding: 3rem 2rem;
            text-align: center;
            position: relative;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in-out;
        }

        .header img {
            width: 140px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1rem;
            border: 4px solid #a46a45;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: scaleUp 1s ease-in-out;
        }

        .header h1 {
            margin: 0;
            font-size: 2.7rem;
            font-family: 'Lobster', cursive;
            letter-spacing: 1.5px;
        }

        .header p {
            font-size: 1.2rem;
            font-weight: 500;
            margin-top: 0.3rem;
            color: #fbe9d9;
        }

        .header button {
            background-color: #c48b65;
            color: white;
            padding: 0.5rem 1.2rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            margin-top: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease-in;
        }

        .header button:hover {
            background-color: #d4a078;
        }

        .nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
            background-color: #a46a45;
            padding: 0.8rem;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            transition: color 0.3s ease-in;
        }

        .nav a:hover {
            color: #f9dccb;
            transform: scale(1.05);
        }

        .section {
            padding: 3rem 2rem;
            text-align: center;
            color: #5a4032;
            animation: fadeIn 1.5s ease-in-out;
        }

        .section h2 {
            font-size: 2.2rem;
            margin-bottom: 1.3rem;
            color: #a46a45;
            position: relative;
        }

        .section p {
            font-size: 1.1rem;
            max-width: 750px;
            margin: 0 auto;
            color: #704f42;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
            opacity: 0;
            animation: fadeIn 2s ease-in-out forwards;
        }

        .skills div, .projects div {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
            transition: transform 0.5s ease;
        }

        .skills div:hover, .projects div:hover {
            transform: translateY(-10px);
            background-color: #ffe4d6;
        }

        .footer {
            background-color: #5a4032;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }

        .footer p {
            margin: 0;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-icons a {
            color: white;
            font-size: 1.8rem;
            transition: transform 0.3s ease-in-out;
        }

        .social-icons a:hover {
            transform: scale(1.2);
        }

        .contact-info {
            text-align: center;
            margin: 3rem 0;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>
    <header class="header">
        <img src="arushi.jpg.jpeg" alt="Profile Photo">
        <h1>Arushi Shrivastava</h1>
        <p>Bhopal, M.P.</p>
        <p>BTech CSE | Web Developer | DSA Enthusiast 🚀</p>
        <button onclick="window.location.href='#about'">Learn More</button>
    </header>

    <nav class="nav">
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
    </nav>

    <section id="about" class="section">
        <h2>About Me</h2>
        <p>Hello! I'm Arushi Shrivastava, a BTech CSE student at Amity University, Rajasthan. I'm passionate about creating beautiful and functional web designs, building efficient algorithms, and working with databases. I aim to combine my technical skills and creativity to develop impactful solutions.</p>
    </section>

    <section id="skills" class="section">
        <h2>Skills</h2>
        <div class="skills">
            <div>
                <h3>Programming Languages 🖥️</h3>
                <p>C, C++, Java</p>
            </div>
            <div>
                <h3>Web Development 🌐</h3>
                <p>HTML, CSS, JavaScript</p>
            </div>
            <div>
                <h3>Database Management 🗃️</h3>
                <p>SQL, PL/SQL</p>
            </div>
        </div>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="projects">
            <div>
                <h3>VivahVastra 💍</h3>
                <p>An e-commerce website for wedding essentials developed as part of an academic project.</p>
            </div>
            <div>
                <h3>Portfolio Website 💻</h3>
                <p>A personal portfolio website built with HTML, CSS, and JavaScript to showcase my skills and projects.</p>
            </div>
        </div>
    </section>

    <section id="experience" class="section">
        <h2>Experience</h2>
        <p>Marketing Member at Amity Innovation Incubator.</p>
    </section>

    <div class="contact-info">
        <p>Email: <strong>arushishrivastava69@gmail.com</strong></p>
    </div>

    <footer class="footer">
        <p>&copy; 2025 Arushi Shrivastava</p>
        <div class="social-icons">
            <a href="https://github.com/arushi" target="_blank">🔗 GitHub</a>
            <a href="https://www.linkedin.com/in/arushi-shrivastava-5236a3299" target="_blank">💼 LinkedIn</a>
        </div>
    </footer>
</body>
</html>
# Task-1-codsoft
