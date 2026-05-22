<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Micaiah Padgett | Portfolio</title>

    <!-- FONT AWESOME -->

    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>

        /* RESET */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #DAD5CF;
            color: #395A7F;
            line-height: 1.6;
        }

        /* NAVIGATION */

        nav {
            background-color: #DAD5CF;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav h1 {
            font-size: 24px;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #395A7F;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #7fa8d1;
        }

        /* HERO SECTION */

        .hero {
            height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(to right, #a3cae9, #395a7f);
            color: white;
            padding: 20px;
        }

        .hero-content h2 {
            font-size: 55px;
            margin-bottom: 15px;
        }

        .hero-content p {
            font-size: 22px;
            margin-bottom: 25px;
        }

        .btn {
            background-color: #DAD5CF;
            color: #395a7f;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: white;
        }

        /* GENERAL SECTION */

        section {
            padding: 80px 10%;
        }

        section h2 {
            font-size: 36px;
            margin-bottom: 20px;
            text-align: center;
        }

        /* ABOUT */

        .about p {
            max-width: 700px;
            margin: auto;
            text-align: center;
            font-size: 18px;
        }

        /* SKILLS */

        .skills-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }

        .skill-box {
            background: linear-gradient(to right, #a3cae9, #395a7f);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);

            width: 150px;
            text-align: center;

            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 12px;

            color: white;

            transition: transform 0.3s;
        }

        .skill-box:hover {
            transform: translateY(-5px);
        }

        .skill-box i {
            font-size: 40px;
        }

        /* PROJECTS */

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .project-card {
            background: linear-gradient(to right, #a3cae9, #395a7f);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            color: white;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        /* CONTACT */

        .contact {
            text-align: center;
        }

        .contact a {
            color: #395A7F;
            text-decoration: none;
            font-weight: bold;
        }

        /* FOOTER */

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* MOBILE */

        @media (max-width: 768px) {

            .hero-content h2 {
                font-size: 38px;
            }

            .hero-content p {
                font-size: 18px;
            }

            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
        }

    </style>
</head>

<body>

    <!-- NAVBAR -->

    <nav>

        <h1>Micaiah Padgett</h1>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </nav>

    <!-- HERO SECTION -->

    <section class="hero">

        <div class="hero-content">

            <h2>Architecture Student & Aspiring Web Developer</h2>

            <p>
                Exploring digital design, architecture, and modern web experiences.
            </p>

            <a href="#projects" class="btn">View My Work</a>

        </div>

    </section>

    <!-- ABOUT -->

    <section class="about" id="about">

        <h2>About Me</h2>

        <p>
            Hi, my name is Micaiah. I'm currently exploring how digital design and
            architecture intersect through web development, visual storytelling,
            and user-centered experiences.
        </p>

    </section>

    <!-- SKILLS -->

    <section id="skills">

        <h2>Skills</h2>

        <div class="skills-container">

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
                <i class="fa-solid fa-mobile-screen"></i>
                Responsive Design
            </div>

            <div class="skill-box">
                <i class="fa-solid fa-palette"></i>
                UI Design
            </div>

        </div>

    </section>

    <!-- PROJECTS -->

    <section id="projects">

        <h2>Projects</h2>

        <div class="projects-grid">

            <div class="project-card">

                <img src="https://via.placeholder.com/400x250"
                    alt="Portfolio Website">

                <h3>Portfolio Website</h3>

                <p>
                    A personal website built using HTML and CSS to showcase my work.
                </p>

            </div>

            <div class="project-card">

                <img src="https://via.placeholder.com/400x250"
                    alt="Future Project">

                <h3>Future Project</h3>

                <p>
                    More projects from my web development courses will be added here.
                </p>

            </div>

        </div>

    </section>

    <!-- CONTACT -->

    <section class="contact" id="contact">

        <h2>Contact</h2>

        <p>Email: mspadgett04@gmail.com</p>

        <p>
            GitHub:
            <a href="https://github.com/padgetmh" target="_blank">
                github.com/padgetmh
            </a>
        </p>

    </section>

    <!-- FOOTER -->

    <footer>

        <p>© 2026 Micaiah Padgett | Portfolio Website</p>

    </footer>

</body>

</html>
