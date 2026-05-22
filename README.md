<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Micaiah Padgett | Portfolio</title>

    <style>

        /* RESET */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif ;
            background-color: #ececee;
            color: cream
            line-height: 1.6;
        }

        /* NAVIGATION */

        nav {
            background-color: #ececee;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
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
            color: #233;
            font-weight: bold;
        }

        nav a:hover {
            color: #ececee;
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
            font-size: 50px;
            margin-bottom: 15px;
        }

        .hero-content p {
            font-size: 20px;
            margin-bottom: 25px;
        }

        .btn {
            background-color: white;
            color: #0077ff;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .btn:hover {
            background-color: #eaaea;
        }

        /* GENERAL SECTION STYLING */

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
            gap: 15px;
            margin-top: 30px;
        }

        .skill-box {
            background-color: white;
            padding: 15px 25px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        /* PROJECTS */

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .project-card {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
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
            color: #0077ff;
            text-decoration: none;
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
                font-size: 36px;
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
                Currently Learning
            </p>

            <a href="#projects" class="btn">View My Work</a>
        </div>

    </section>

    <!-- ABOUT SECTION -->

    <section class="about" id="about">

        <h2>About Me</h2>

        <p>
            Hi my name is Micaiah, I'm currently exploring how digital design and architecture intersect through web development, visual storytelling, and user-centered experiences.  
        </p>

    </section>

    <!-- SKILLS SECTION -->

    <section id="skills">

        <h2>Skills</h2>

        <div class="skills-container">

            <div class="skill-box">HTML</div>
            <div class="skill-box">CSS</div>
            <div class="skill-box">JavaScript</div>
            <div class="skill-box">Responsive Design</div>
            <div class="skill-box">UI Design</div>

        </div>

    </section>

    <!-- PROJECTS SECTION -->

    <section id="projects">

        <h2>Projects</h2>

        <div class="projects-grid">

            <div class="project-card">

                <img src="https://via.placeholder.com/400x250" alt="Project Image">

                <h3>Portfolio Website</h3>

                <p>
                    A personal website built using HTML and CSS to showcase my work.
                </p>

            </div>

            <div class="project-card">

                <img src="https://via.placeholder.com/400x250" alt="Project Image">

                <h3>Future Project</h3>

                <p>
                    More projects from my web development courses will be added here.
                </p>

            </div>

        </div>

    </section>

    <!-- CONTACT SECTION -->

    <section class="contact" id="contact">

        <h2>Contact</h2>

        <p>Email: mspadgett04@gmail.com</p>

        <p>
            GitHub:
            <a href="#">github.com/padgetmh</a>
        </p>

    </section>

    <!-- FOOTER -->

    <footer>

        <p>© 2026 Micaiah Padgett | Portfolio Website</p>

    </footer>

</body>
</html>
