
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--     <title>Jethro Zhao - Resume</title> -->
    <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --background-color: #F5F4F1;
            --text-color: #333333;
            --accent-color: #4A7B3F;
            --light-gray: #E5E5E5;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .header-main {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }
        
        h1 {
            font-family: 'Libre Baskerville', serif;
            font-size: 3rem;
            font-weight: 700;
            color: var(--text-color);
            margin: 0;
            position: relative;
        }

        h1::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 2px;
            background-color: var(--accent-color);
        }

        h1 a {
            color: inherit;
            text-decoration: none;
        }
        
        h2 {
            font-family: 'Libre Baskerville', serif;
            font-size: 1.8rem;
            color: var(--accent-color);
            border-bottom: 1px solid var(--accent-color);
            padding-bottom: 5px;
            margin-top: 30px;
        }
        
        .social-icons {
            display: flex;
            gap: 10px;
        }
        
        .social-icon {
            width: 24px;
            height: 24px;
            background-color: var(--accent-color);
            border-radius: 5px;
            transition: transform 0.3s ease;
        }
        
        .social-icon:hover {
            transform: scale(1.1);
        }
        
        .contact-info {
            font-size: 0.9rem;
            margin-top: 10px;
            text-align: center;
        }
        
        .intro {
            margin-bottom: 30px;
            text-align: center;
            font-style: italic;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .entry {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: all 0.5s ease;
            margin-bottom: 15px;
        }
        
        .entry-header {
            display: flex;
            align-items: center;
            padding: 10px;
            cursor: pointer;
        }
        
        .entry-logo {
            width: 40px;
            height: 40px;
            margin-right: 15px;
            background-color: var(--light-gray);
            border-radius: 5px;
        }
        
        .entry-content {
            flex-grow: 1;
        }
        
        .entry-title {
            font-weight: 600;
            color: var(--text-color);
            font-size: 1.1rem;
            margin-bottom: 3px;
        }
        
        .entry-org {
            font-weight: 400;
            color: var(--accent-color);
            margin-bottom: 3px;
        }
        
        .entry-date {
            font-size: 0.85rem;
            color: var(--text-color);
            opacity: 0.8;
        }
        
        .entry-details {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease;
            padding: 0 10px;
        }
        
        .entry:hover .entry-details {
            max-height: 300px;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .project {
            background-color: white;
            border-radius: 5px;
            padding: 15px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }
        
        .project-title {
            font-weight: 600;
            margin-bottom: 5px;
            color: var(--accent-color);
        }
        
        .project-description {
            font-size: 0.9rem;
        }
        
        @media screen and (max-width: 600px) {
            .container {
                padding: 20px 10px;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .header-main {
                flex-direction: column;
                align-items: center;
            }
            
            .social-icons {
                margin-top: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-main">
                <h1>Jethro Zhao</h1>
                <div class="social-icons">
                    <a href="https://www.linkedin.com/in/jethro-zhao" target="_blank">
                        <img src="icon/linkedin.png" alt="LinkedIn" class="social-icon">
                    </a>
                    <a href="https://github.com/jethrozhao" target="_blank">
                        <img src="icon/github.png" alt="GitHub" class="social-icon">
                    </a>
                    <a href="https://www.instagram.com/by.jethrozhao/" target="_blank">
                        <img src="icon/instagram.png" alt="Instagram" class="social-icon">
                    </a>
                </div>
            </div>
        </header>

        <div class="contact-info">
            <p>xiaoyaoj@usc.edu | 🇺🇸 US: +1 (310) 293 5738 | 🇭🇰 HK: +852 9191 1019</p>
        </div>

        <section class="intro">
            <p>👋 Hey! I'm Jethro -- a data analyst, software engineer, and tennis enthusiast. I'm a current sophomore studying Artificial Intelligence for Business at USC in LA. </p>
        </section>

        <section class="section" id="experience">
            <h2>Work Experience</h2>
            <div class="entry">
                <div class="entry-header">
                    <div class="entry-logo">
                        <img src="icon/animocabrands.png" alt="AnimocaBrands" class="entry-logo">
                    </div>
                    <div class="entry-content">
                        <p class="entry-title">Data Science Intern</p>
                        <p class="entry-org">Animoca Brands Limited</p>
                        <p class="entry-date">June 2024 - August 2024</p>
                    </div>
                </div>
                <div class="entry-details">
                    <ul>
                        <li>Designed and implemented initial dashboard and database for emerging projects using SQL</li>
                        <li>Communicated with 4 prospective clients and partners to design and conduct experiments to evaluate these solutions</li>
                        <li>Performed data wrangling to clean datasets and analysed experiment data using matplotlib</li>
                    </ul>
                </div>
            </div>
            <div class="entry">
                <div class="entry-header">
                    <div class="entry-logo">
                        <img src="icon/newvision.jpeg" alt="NewVision" class="entry-logo">
                    </div>
                    <div class="entry-content">
                        <p class="entry-title">AI Software Intern</p>
                        <p class="entry-org">New Vision Asset Management Ltd</p>
                        <p class="entry-date">June 2023 - August 2023</p>
                    </div>
                </div>
                <div class="entry-details">
                    <ul>
                        <li>Developed a program using LLMs to retrieve and analyse equity research reports to generate potential investment opportunities under current market conditions</li>
                        <li>This innovation saved analysts in the company significant time that was otherwise spent reading equity research reports</li>
                    </ul>
                </div>
            </div>
            <div class="entry">
                <div class="entry-header">
                    <div class="entry-logo">
                         <img src="icon/scmp.jpg" alt="SCMP" class="entry-logo">
                    </div>
                    <div class="entry-content">
                        <p class="entry-title">Junior Reporter & Social Media Manager</p>
                        <p class="entry-org">South China Morning Post</p>
                        <p class="entry-date">June 2021 - July 2021</p>
                    </div>
                </div>
                <div class="entry-details">
                    <ul>
                        <li>Conducted interviews & co-wrote 3 articles</li>
                        <li>Compiled reader responses, movie and event news for daily paper</li>
                        <li>Managed Instagram & grew following 14%</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="section" id="education">
            <h2>Education</h2>
            <div class="entry">
                <div class="entry-header">
                    <div class="entry-logo">
                        <img src="icon/USC.png" alt="USC" class="entry-logo">
                    </div>
                    <div class="entry-content">
                        <p class="entry-title">Bachelor of Science, Artificial Intelligence for Business</p>
                        <p class="entry-org">University of Southern California</p>
                        <p class="entry-date">August 2023 - Present</p>
                    </div>
                </div>
                <div class="entry-details">
                    <p>GPA: 3.8</p>
                    <p>Pursuing a dual degree program combining business acumen with cutting-edge AI technology</p>
                </div>
            </div>
            <div class="entry">
                <div class="entry-header">
                    <div class="entry-logo">
                         <img src="icon/columbia.jpeg" alt="Columbia" class="entry-logo">
                    </div>
                    <div class="entry-content">
                        <p class="entry-title">Entrepreneurship And Innovation: Changing The World Via Venture Creation</p>
                        <p class="entry-org">Columbia University</p>
                        <p class="entry-date">June 2021 - August 2021</p>
                    </div>
                </div>
                <div class="entry-details">
                    <p>Intensive summer program focused on entrepreneurship and innovation strategies</p>
                    <p>Developed skills in venture creation and business model innovation</p>
                </div>
            </div>
        </section>

        <section class="section" id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <p class="project-title">Project Reboot</p>
                    <p class="project-description">Collected and recycled 25kg of e-waste. Donated 243 calculators to children in Cambodia.</p>
                </div>
                <div class="project">
                    <p class="project-title">Project Privates</p>
                    <p class="project-description">Fundraised $3,000 USD for the Hong Kong cancer foundation to promote men's health awareness.</p>
                </div>
                <div class="project">
                    <p class="project-title">Bloom Fashion</p>
                    <p class="project-description">Founded fashion advisory startup for Hong Kong men, managing 8-member team.</p>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
