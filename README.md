<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Rahul H R | Portfolio</title>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet"
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f3f4f6;
            color: #111827;
        }

        header {
            background: #0f172a;
            color: white;
            padding: 30px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            margin: 6px 0;
            color: #cbd5f5;
        }

        nav {
            background: #1e293b;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a i {
            margin-right: 6px;
        }

        section {
            background: white;
            margin: 20px;
            padding: 20px;
            border-radius: 8px;
        }

        h2 {
            border-bottom: 2px solid #3b82f6;
            padding-bottom: 6px;
            color: #0f172a;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .skill-box {
            background: #f1f5f9;
            padding: 15px;
            border-radius: 6px;
            text-align: center;
            font-weight: bold;
        }

        .skill-box i {
            font-size: 28px;
            color: #2563eb;
            margin-bottom: 8px;
        }

        .project {
            border-left: 4px solid #2563eb;
            padding-left: 12px;
            margin-top: 15px;
        }

        footer {
            background: #0f172a;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        a {
            color: #2563eb;
        }
    </style>
</head>

<body>

<header>
    <h1>Rahul H R</h1>
    <p>BE Computer Science | 2026 Passout</p>
    <p>Java Full Stack Developer</p>
</header>

<nav>
    <a href="#about"><i class="fa-solid fa-user"></i>About</a>
    <a href="#skills"><i class="fa-solid fa-laptop-code"></i>Skills</a>
    <a href="#projects"><i class="fa-solid fa-diagram-project"></i>Projects</a>
    <a href="#contact"><i class="fa-solid fa-envelope"></i>Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a Computer Science Engineering student (2026 passout) with strong
        knowledge in Java and web technologies. Currently doing a Java Full Stack
        internship and actively seeking entry-level software developer roles.
    </p>
</section>

<section id="skills">
    <h2>Technical Skills</h2>

    <div class="skills">
        <div class="skill-box">
            <i class="fa-brands fa-java"></i>
            Java
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-html5"></i>
            HTML
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-css3-alt"></i>
            CSS
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-js"></i>
            JavaScript
        </div>

        <div class="skill-box">
            <i class="fa-solid fa-database"></i>
            SQL
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-git-alt"></i>
            Git
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-github"></i>
            GitHub
        </div>

        <div class="skill-box">
            <i class="fa-brands fa-react"></i>
            React (Basics)
        </div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project">
        <h3>Real-Time Object Tracking & Management System</h3>
        <p><i class="fa-solid fa-tools"></i> Python, Flask, SQLite, HTML, CSS</p>
        <p>
            Developed a secure web application with login, CRUD operations,
            QR-code generation, and session management.
        </p>
    </div>

    <div class="project">
        <h3>Dynamic Load Balancing Simulation</h3>
        <p><i class="fa-solid fa-tools"></i> Python, Flask, JavaScript, Chart.js</p>
        <p>
            Implemented Round Robin and Least Connection algorithms to optimize
            server load distribution.
        </p>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p><i class="fa-solid fa-envelope"></i> rahulravikumar976@gmail.com</p>
    <p><i class="fa-brands fa-linkedin"></i>
        <a href="https://www.linkedin.com/in/rahul-h-r-1a442427b" target="_blank">
            LinkedIn Profile
        </a>
    </p>
    <p><i class="fa-brands fa-github"></i>
        <a href="https://github.com/rahulhr976" target="_blank">
            GitHub Profile
        </a>
    </p>
</section>

<footer>
    <p>© 2026 Rahul H R | Portfolio</p>
</footer>

</body>
</html>
