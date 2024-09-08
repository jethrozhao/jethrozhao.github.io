<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Jethro Zhao </title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        
        :root {
            --primary-color: #6C63FF;
            --secondary-color: #2C3E50;
            --background-color: #F8F9FA;
            --text-color: #333;
            --timeline-color: #E0E0E0;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 50px;
        }
        
        h1 {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 10px;
        }
        
        h2 {
            font-size: 2rem;
            color: var(--secondary-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 10px;
            margin-top: 40px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .contact-info span {
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .section {
            margin-bottom: 40px;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        /* New styles for the enhanced experience section */
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: var(--timeline-color);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }
        
        .job {
            padding: 10px 40px;
            position: relative;
            background-color: inherit;
            width: calc(50% - 40px);
            transition: all 0.3s ease;
        }
        
        .job:nth-child(odd) {
            left: 0;
        }
        
        .job:nth-child(even) {
            left: 50%;
        }
        
        .job::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            right: -17px;
            background-color: var(--background-color);
            border: 4px solid var(--primary-color);
            top: 15px;
            border-radius: 50%;
            z-index: 1;
        }
        
        .job:nth-child(even)::after {
            left: -16px;
        }
        
        .job-content {
            padding: 20px 30px;
            background-color: white;
            position: relative;
            border-radius: 6px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        
        .job-title {
            font-weight: 600;
            color: var(--primary-color);
            font-size: 1.2rem;
            margin-bottom: 5px;
        }
        
        .company {
            font-weight: 400;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }
        
        .date {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 10px;
        }
        
        .job-description {
            margin-top: 15px;
            display: none;
        }
        
        .job-content:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
        
        .job-content:hover .job-description {
            display: block;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background-color: var(--primary-color);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            transition: transform 0.2s;
        }
        
        .skill:hover {
            transform: translateY(-3px);
        }
        
        @media screen and (max-width: 768px) {
            .timeline::after {
                left: 31px;
            }
            
            .job {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }
            
            .job::after {
                left: 15px;
            }
            
            .job:nth-child(even) {
                left: 0%;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            h2 {
                font-size: 1.8rem;
            }
            
            .section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Your Name</h1>
            <div class="contact-info">
                <span><i class="fas fa-envelope"></i> xiaoyaoj@usc.edu</span>
                <span><i class="fas fa-phone"></i> 🇺🇸 +1(310) 293-5738 </span>
                <span><i class="fas fa-phone"></i> 🇭🇰 +852 9191 1019 </span>
                <span><i class="fas fa-map-marker-alt"></i> Los Angeles, California </span>
                <span><i class="fas fa-map-marker-alt"></i> Hong Kong, Hong Kong SAR </span>
            </div>
        </header>

        <section class="section" id="summary">
            <h2>Professional Summary</h2>
            <p>A dynamic and innovative professional with a passion for [your field]. Combining creativity with analytical skills to drive results and push boundaries in [specific area of expertise].</p>
        </section>

        <section class="section" id="experience">
            <h2>Work Experience</h2>
            <div class="timeline">
                <div class="job">
                    <div class="job-content">
                        <p class="job-title">Senior Developer</p>
                        <p class="company">Tech Innovators Inc.</p>
                        <p class="date">Jan 2020 - Present</p>
                        <div class="job-description">
                            <ul>
                                <li>Spearheaded the development of a groundbreaking AI-powered analytics platform</li>
                                <li>Led a team of 5 developers, increasing productivity by 30% through agile methodologies</li>
                                <li>Implemented machine learning algorithms to improve data processing efficiency by 50%</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="job">
                    <div class="job-content">
                        <p class="job-title">Full Stack Developer</p>
                        <p class="company">Digital Solutions Co.</p>
                        <p class="date">Mar 2017 - Dec 2019</p>
                        <div class="job-description">
                            <ul>
                                <li>Developed and maintained 10+ web applications using React and Node.js</li>
                                <li>Implemented CI/CD pipelines, reducing deployment time by 50%</li>
                                <li>Optimized database queries, improving application response time by 40%</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="job">
                    <div class="job-content">
                        <p class="job-title">Junior Web Developer</p>
                        <p class="company">WebCraft Studios</p>
                        <p class="date">Jun 2015 - Feb 2017</p>
                        <div class="job-description">
                            <ul>
                                <li>Assisted in the development of responsive websites for various clients</li>
                                <li>Collaborated with designers to implement pixel-perfect UI designs</li>
                                <li>Learned and applied best practices in web accessibility and SEO</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" id="education">
            <h2>Education</h2>
            <div class="education">
                <p class="degree">Master of Science in Computer Science</p>
                <p class="school">Tech University</p>
                <p class="date">Graduated 2017</p>
            </div>
            <div class="education">
                <p class="degree">Bachelor of Science in Software Engineering</p>
                <p class="school">State University</p>
                <p class="date">Graduated 2015</p>
            </div>
        </section>

        <section class="section" id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <span class="skill">JavaScript</span>
                <span class="skill">React</span>
                <span class="skill">Node.js</span>
                <span class="skill">Python</span>
                <span class="skill">Machine Learning</span>
                <span class="skill">AWS</span>
                <span class="skill">Docker</span>
                <span class="skill">Git</span>
            </div>
        </section>
    </div>
</body>
</html>
