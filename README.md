<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jethro Zhao - Personal Website</title>
    <style>
        :root {
            --bg-color: #f5f2eb;
            --text-color: #1a2721;
            --accent-color: #1e5631;
            --card-bg: #ffffff;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: var(--bg-color);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav {
            display: flex;
            justify-content: flex-end;
            padding: 1rem 0;
        }
        nav a {
            color: var(--text-color);
            text-decoration: none;
            margin-left: 1.5rem;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        nav a:hover, nav a.active {
            color: var(--accent-color);
        }
        main {
            padding-top: 80px; /* Increased padding to prevent clipping */
        }
        h1, h2 {
            font-family: Georgia, serif;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        h2 {
            font-size: 2rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
            color: var(--accent-color);
        }
        .card {
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .contact-info {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        .contact-info a {
            color: var(--text-color);
            text-decoration: none;
            display: flex;
            align-items: center;
        }
        .contact-info a:hover {
            color: var(--accent-color);
        }
        .icon {
            width: 20px;
            height: 20px;
            margin-right: 0.5rem;
        }
        footer {
            background-color: var(--accent-color);
            color: var(--bg-color);
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        .social-links a {
            color: var(--text-color);
            text-decoration: none;
        }
        .social-links a:hover {
            color: var(--accent-color);
        }
        .collapsible {
            cursor: pointer;
        }
        .content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }
        #about {
            padding-top: 2rem; /* Added padding to create space between nav and name card */
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <a href="#about" class="active">About</a>
                <a href="#experience">Experience</a>
                <a href="#education">Education</a>
                <a href="#projects">Projects</a>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="about">
            <div class="card">
                <h1>Jethro Zhao</h1>
                <p>Data Science & AI Enthusiast</p>
                <div class="contact-info">
                    <a href="mailto:xjzhaoyj@usc.edu">
                        <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        xjzhaoyj@usc.edu
                    </a>
                    <a href="tel:+13102235738">
                        <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                        +1 310 223 5738
                    </a>
                    <span>
                        <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        48 Deep Water Bay Road, Hong Kong
                    </span>
                </div>
            </div>
            <p>I'm a Data Science and AI enthusiast with a passion for innovation and entrepreneurship. Currently pursuing a Bachelor's degree in Artificial Intelligence for Business at the University of Southern California.</p>
            <div class="social-links">
                <a href="https://github.com" target="_blank" rel="noopener noreferrer">
                    <svg class="icon" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
                </a>
                <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
                    <svg class="icon" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
                </a>
                <a href="mailto:xjzhaoyj@usc.edu">
                    <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                </a>
            </div>
        </section>

        <section id="experience">
            <h2>Experience</h2>
            <div class="card collapsible">
                <h3>Data Science Intern</h3>
                <p>Animoca Brands Limited | June 2024 - August 2024</p>
                <div class="content">
                    <p>Designed and implemented initial dashboard and database for emerging projects using SQL. Communicated with 4 prospective clients and partners to design and conduct experiments to evaluate these solutions. Performed data wrangling to clean datasets and analyzed experimental data using matplotlib.</p>
                </div>
            </div>
            <div class="card collapsible">
                <h3>AI Software Intern</h3>
                <p>New Vision Asset Management Ltd | June 2023 - August 2023</p>
                <div class="content">
                    <p>Developed a program using LLMs to retrieve and analyze equity research reports to generate potential investment opportunities under current market conditions. This saved analysts in the company time that was otherwise spent reading equity research reports.</p>
                </div>
            </div>
            <div class="card collapsible">
                <h3>Junior Reporter & Social Media Manager</h3>
                <p>South China Morning Post | June 2021 - July 2021</p>
                <div class="content">
                    <p>Conducted interviews & co-wrote 3 articles. Compiled reader responses, movie and event news for daily paper. Managed Instagram & grew following 14%.</p>
                </div>
            </div>
        </section>

        <section id="education">
            <h2>Education</h2>
            <div class="card collapsible">
                <h3>University of Southern California</h3>
                <p>Bachelor of Science, Artificial Intelligence for Business | August 2023 - Present</p>
                <div class="content">
                    <p>Marshall School of Business | Viterbi School of Engineering</p>
                    <p>GPA: 3.8</p>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="card collapsible">
                <h3>Bloom Fashion</h3>
                <p>Founder, Director | January 2022 - February 2023</p>
                <div class="content">
                    <p>Founded fashion advisory startup for Hong Kong men; managing 8-member team. Coordinated company operations and established communications with 3 clothing brands.</p>
                </div>
            </div>
            <div class="card collapsible">
                <h3>Project Privates</h3>
                <p>Treasurer, Marketing Director | October 2021 - June 2023</p>
                <div class="content">
                    <p>Sold merchandise to fundraise $3,000 USD for the Hong Kong cancer foundation to promote men's health awareness in highschools.</p>
                </div>
            </div>
            <div class="card collapsible">
                <h3>Project Reboot</h3>
                <p>Founder, Co-ordinator | August 2021 - June 2023</p>
                <div class="content">
                    <p>Established program and managed 15 people. Collected  and recycled 25kg of e-waste. Donated 243 calculators to children in Cambodia. Raised $2,000 USD+.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Jethro Zhao. All rights reserved.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', (event) => {
            // Highlight active nav item
            const navLinks = document.querySelectorAll('nav a');
            const sections = document.querySelectorAll('main section');

            window.addEventListener('scroll', () => {
                let current = '';
                sections.forEach(section => {
                    const sectionTop = section.offsetTop;
                    const sectionHeight = section.clientHeight;
                    if (pageYOffset >= sectionTop - 60) {
                        current = section.getAttribute('id');
                    }
                });

                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href').slice(1) === current) {
                        link.classList.add('active');
                    }
                });
            });

            // Collapsible sections
            const collapsibles = document.querySelectorAll('.collapsible');
            collapsibles.forEach(item => {
                item.addEventListener('click', function() {
                    this.classList.toggle('active');
                    const content = this.querySelector('.content');
                    if (content.style.maxHeight) {
                        content.style.maxHeight = null;
                    } else {
                        content.style.maxHeight = content.scrollHeight + 'px';
                    }
                });
            });
        });
    </script>
</body>
</html>
