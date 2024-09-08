<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jethro Zhao - Resume</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2C3E50;
            --secondary-color: #34495E;
            --background-color: #F8F9FA;
            --text-color: #333333;
            --accent-color: #3498DB;
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
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 2.5rem;
            font-weight: 600;
            color: var(--primary-color);
            margin-bottom: 10px;
        }
        
        h2 {
            font-size: 1.8rem;
            color: var(--secondary-color);
            border-bottom: 1px solid var(--accent-color);
            padding-bottom: 5px;
            margin-top: 30px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            font-size: 0.9rem;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .entry {
            margin-bottom: 20px;
        }
        
        .entry-content {
            padding: 15px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }
        
        .entry-title {
            font-weight: 600;
            color: var(--primary-color);
            font-size: 1.1rem;
            margin-bottom: 5px;
        }
        
        .entry-org {
            font-weight: 400;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }
        
        .entry-date {
            font-size: 0.85rem;
            color: var(--text-color);
            opacity: 0.8;
            margin-bottom: 10px;
        }
        
        .entry-description {
            font-size: 0.9rem;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background-color: var(--accent-color);
            color: white;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.85rem;
        }
        
        @media screen and (max-width: 600px) {
            .container {
                padding: 20px 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Jethro Zhao</h1>
            <div class="contact-info">
                <span>xiaoyaoj@usc.edu</span>
                <span> 🇺🇸US: +1 310 293 5738 | 🇭🇰HK: +852 9191 1019</span>
                <span>48 Deep Water Bay Road, Hong Kong</span>
            </div>
        </header>

        <section class="section" id="experience">
            <h2>Work Experience</h2>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Junior Reporter & Social Media Manager</p>
                    <p class="entry-org">South China Morning Post</p>
                    <p class="entry-date">June 2021 - July 2021</p>
                    <div class="entry-description">
                        <ul>
                            <li>Conducted interviews & co-wrote 3 articles</li>
                            <li>Compiled reader responses, movie and event news for daily paper</li>
                            <li>Managed Instagram & grew following 14%</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">AI Software Intern</p>
                    <p class="entry-org">New Vision Asset Management Ltd</p>
                    <p class="entry-date">June 2023 - August 2023</p>
                    <div class="entry-description">
                        <ul>
                            <li>Developed a program using LLMs to retrieve and analyse equity research reports</li>
                            <li>Generated potential investment opportunities under current market conditions</li>
                            <li>Saved analysts significant time in reading equity research reports</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Data Science Intern</p>
                    <p class="entry-org">Animoca Brands Limited</p>
                    <p class="entry-date">June 2024 - August 2024</p>
                    <div class="entry-description">
                        <ul>
                            <li>Designed and implemented initial dashboard and database for emerging projects using SQL</li>
                            <li>Communicated with 4 prospective clients and partners to design and conduct experiments</li>
                            <li>Performed data wrangling and analysed experiment data using matplotlib</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" id="education">
            <h2>Education</h2>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Bachelor of Science, Artificial Intelligence for Business</p>
                    <p class="entry-org">University of Southern California, Marshall School of Business | Viterbi School of Engineering</p>
                    <p class="entry-date">August 2023 - Present</p>
                    <div class="entry-description">
                        <p>GPA: 3.8</p>
                        <p>Pursuing a dual degree program combining business acumen with cutting-edge AI technology</p>
                    </div>
                </div>
            </div>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Entrepreneurship And Innovation: Changing The World Via Venture Creation</p>
                    <p class="entry-org">Columbia University</p>
                    <p class="entry-date">June 2021 - August 2021</p>
                    <div class="entry-description">
                        <p>Intensive summer program focused on entrepreneurship and innovation strategies</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" id="activities">
            <h2>Extra-Curricular Activities</h2>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Founder, Co-ordinator</p>
                    <p class="entry-org">Project Reboot</p>
                    <p class="entry-date">August 2021 - June 2023</p>
                    <div class="entry-description">
                        <ul>
                            <li>Established program and managed 16 people</li>
                            <li>Collected and recycled 25kg of e-waste</li>
                            <li>Donated 243 calculators to children in Cambodia</li>
                            <li>Raised $2,000 USD+</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Treasurer, Marketing Director</p>
                    <p class="entry-org">Project Privates</p>
                    <p class="entry-date">October 2021 - June 2023</p>
                    <div class="entry-description">
                        <ul>
                            <li>Sold merchandise to fundraise $3,000 USD for the Hong Kong cancer foundation</li>
                            <li>Promoted men's health awareness in high schools</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="entry">
                <div class="entry-content">
                    <p class="entry-title">Founder, Director</p>
                    <p class="entry-org">Bloom Fashion</p>
                    <p class="entry-date">January 2022 - February 2023</p>
                    <div class="entry-description">
                        <ul>
                            <li>Founded fashion advisory startup for Hong Kong men</li>
                            <li>Managed 8-member team</li>
                            <li>Coordinated company operations</li>
                            <li>Established communications with 3 clothing brands</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <span class="skill">Java</span>
                <span class="skill">Python</span>
                <span class="skill">C++</span>
                <span class="skill">R</span>
                <span class="skill">SQL</span>
                <span class="skill">English (Bilingual)</span>
                <span class="skill">Chinese (Bilingual)</span>
            </div>
        </section>
    </div>
</body>
</html>
