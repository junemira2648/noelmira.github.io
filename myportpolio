<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noel L. Mira Jr.- Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            background-image: url('https://images.unsplash.com/photo-1517694712202-14dd9538aa97?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80');
            background-attachment: fixed;
            background-size: cover;
            background-position: center;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.85);
            pointer-events: none;
            z-index: -1;
        }

        header {
            background: #2b2b2b;
            color: white;
            padding: 2rem 0;
            position: sticky;
            top: 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            z-index: 100;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        nav .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.8;
        }

        .hero {
            background: linear-gradient(rgba(26, 26, 26, 0.7), rgba(26, 26, 26, 0.7)), url('https://images.unsplash.com/photo-1517694712202-14dd9538aa97?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            text-align: center;
            padding: 6rem 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        .cta-button {
            display: inline-block;
            background-color: white;
            color: #1a1a1a;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        section {
            margin: 4rem 0;
            padding: 3rem 0;
            border-bottom: 1px solid #999;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            color: #2b2b2b;
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            align-items: center;
        }

        .about-skills {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 1.5rem;
        }

        .about-skill-item {
            text-align: center;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .about-skill-item .icon {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        .about-skill-item p {
            font-size: 0.9rem;
            color: #2b2b2b;
            font-weight: 500;
        }

        .about-icon {
            font-size: 5rem;
            color: #2b2b2b;
            margin-bottom: 1rem;
        }

        .about-text p {
            margin-bottom: 1rem;
            font-size: 1rem;
            line-height: 1.8;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
        }

        .skill-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
        }

        .skill-card h3 {
            color: #2b2b2b;
            margin-bottom: 0.5rem;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
        }

        .project-card h3 {
            color: #2b2b2b;
            margin-bottom: 0.5rem;
        }

        .project-card .project-content {
            padding: 1.5rem;
        }

        .project-card .project-link {
            color: #2b2b2b;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .project-card .project-link:hover {
            color: #555555;
        }

        .contact-section {
            text-align: center;
            padding: 3rem 0;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .contact-info a {
            color: #2b2b2b;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s;
        }

        .contact-info a:hover {
            color: #555555;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            .about-content {
                grid-template-columns: 1fr;
            }

            nav ul {
                gap: 1rem;
                font-size: 0.9rem;
            }

            .hero h1 {
                font-size: 2rem;
            }

            section h2 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Noel L. Mira Jr.</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Hi, I'm Noel L. Mira Jr.</h1>
        <p>Aspiring Developer | Learning & Growing</p>
        <a href="#projects" class="cta-button">View My Work</a>
    </section>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Welcome to my portfolio! I'm a passionate developer with a love for creating beautiful and functional web applications.</p>
                    <p>I specialize in modern web technologies and enjoy tackling complex problems with elegant solutions. When I'm not coding, you'll find me exploring new technologies and contributing to open-source projects.</p>
                    <p>Let's build something amazing together!</p>
                </div>
                <div class="about-skills">
                    <div class="about-skill-item">
                        <div class="icon">🌐</div>
                        <p>HTML, CSS, JavaScript</p>
                    </div>
                    <div class="about-skill-item">
                        <div class="icon">⚙️</div>
                        <p>Workflow Automation</p>
                    </div>
                    <div class="about-skill-item">
                        <div class="icon">🤖</div>
                        <p>n8n, Zapier, Make.com</p>
                    </div>
                    <div class="about-skill-item">
                        <div class="icon">💼</div>
                        <p>GoHighLevel CRM</p>
                    </div>
                    <div class="about-skill-item">
                        <div class="icon">📢</div>
                        <p>Facebook & Google Ads</p>
                    </div>
                    <div class="about-skill-item">
                        <div class="icon">🔧</div>
                        <p>API Integrations</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project-card">
                    <div class="project-content">
                        <h3>Freelance Field IT Support</h3>
                        <p><strong>2017 - 2022</strong></p>
                        <p>Provided comprehensive IT troubleshooting and technical support. Handled hardware failures, software errors, and network issues. Offered remote engineering support and on-site "smart hands" services. Managed technology projects and educated users on technical solutions.</p>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-content">
                        <h3>Technical Support Representative</h3>
                        <p><strong>2022 - 2023</strong></p>
                        <p>Delivered exceptional technical service to T-Mobile clients. Resolved technical queries, troubleshot device issues, and processed transactions. Educated customers on device features while maintaining company standards and strong communication skills.</p>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-content">
                        <h3>Workflow Automation & Integration Specialist</h3>
                        <p><strong>Current Focus</strong></p>
                        <p>Specializing in automation tools, CRM management, and digital marketing support. Building expertise in n8n, GoHighLevel, and API integrations to streamline business processes.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill-card">
                    <h3>Frontend</h3>
                    <p>HTML, CSS, JavaScript</p>
                </div>
                <div class="skill-card">
                    <h3>Workflow Automation</h3>
                    <p>n8n, Zapier, Make.com</p>
                </div>
                <div class="skill-card">
                    <h3>CRM & Tools</h3>
                    <p>GoHighLevel, Google Workspace</p>
                </div>
                <div class="skill-card">
                    <h3>Digital Marketing</h3>
                    <p>Facebook Ads, Google Ads</p>
                </div>
                <div class="skill-card">
                    <h3>Technical Skills</h3>
                    <p>API Integrations, Lead Tracking, Support</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact-section">
            <h2>Let's Connect</h2>
            <p>I'm always interested in hearing about new projects and opportunities.</p>
            <div class="contact-info">
                <a href="mailto:noelmira2020@gmail.com">📧 Email</a>
                <a href="https://github.com/junemira2648" target="_blank">💻 GitHub</a>
                <a href="https://www.linkedin.com/in/noel-mira-jr-088084271/" target="_blank">💼 LinkedIn</a>
                <a href="https://www.facebook.com/JownjownMiruh/" target="_blank">👍 Facebook</a>
                <a href="tel:+639761870825">📱 +639761870825</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Noel L. Mira Jr. All rights reserved.</p>
    </footer>
</body>
</html>
