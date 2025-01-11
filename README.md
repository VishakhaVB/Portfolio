<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body, h1, h2, p, ul, table {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        
        body {
            background-color: #f9ffe6;
            line-height: 1.6;
            color: #333;
        }
        
        /* Header */
        header {
            background-color: #e6ffee;
            text-align: center;
            padding: 20px;
        }
        
        header .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 10px auto;
        }
        
        header h1 {
            color: #0056b3;
            font-size: 2.5rem;
        }
        
        header p {
            font-size: 1.2rem;
            color: #333;
        }
        
        
        nav ul {
            list-style: none;
            background: #333;
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: #fff;
            padding: 10px 15px;
            display: inline-block;
            transition: background 0.3s;
        }
        
        nav ul li a:hover {
            background: #0056b3;
            border-radius: 5px;
        }
        
        
        .section {
            padding: 20px;
            margin: 20px 0;
        }
        
        .section h2 {
            text-align: center;
            margin-bottom: 15px;
            color: #0056b3;
        }
        
        
        #projects p, #contact p {
            text-align: center;
            max-width: 600px;
            margin: 0 auto;
        }
        
        
        .skills-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skills-container span {
            background: #ffcccb;
            padding: 10px 15px;
            border-radius: 15px;
            color: #333;
            font-weight: bold;
        }
        
        /* Table */
        table {
            width: 80%;
            margin: 0 auto;
            border-collapse: collapse;
            text-align: center;
            margin-top: 10px;
        }
        
        table th, table td {
            border: 1px solid #ddd;
            padding: 10px;
        }
        
        table th {
            background: #333;
            color: #fff;
        }
        
        table tr:nth-child(even) {
            background: #f2f2f2;
        }
        
        /* Footer */
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: #fff;
        }
        .projects-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        
        .project {
            background: #e6ffee;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .project h3 {
            margin-bottom: 10px;
            color: #0056b3;
        }
        
        .project p {
            margin-bottom: 15px;
            font-size: 0.9rem;
        }
        
        .project a {
            text-decoration: none;
            color: #fff;
            background: #0056b3;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        
        .project a:hover {
            background: #003d82;
        }
        
        .project:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }</style>
   
</head>
<body>
    <header>
        <div class="container">
            <img src="15.png" alt="Profile Picture" class="profile-pic">
            <h1>Hello! I'm Vishakha Bhilwadkar</h1>
            <p>A passionate coder and aspiring software engineer</p>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
            My name is Vishakha Bhilwadkar. I am currently pursuing a B.Tech degree in IT. I aspire to become a skilled software engineer and contribute to impactful projects.
            I love coding and enjoy learning new technologies to enhance my skills. My dream is to study abroad for my master's degree and build innovative applications that help people.
        </p>
    </section>

    <section id="skills" class="section">
        <h2>Skills</h2>
        <div class="skills-container">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>SQL</span>
            <span>Python</span>
            <span>Java</span>
            <span>C++</span>
            <span>C</span>
        </div>
    </section>

    <section id="education" class="section">
        <h2>Education</h2>
        <table>
            <thead>
                <tr>
                    <th>Class</th>
                    <th>Grades</th>
                    <th>Board/University</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>X</td>
                    <td>90%</td>
                    <td>Maharashtra Board</td>
                </tr>
                <tr>
                    <td>XII</td>
                    <td>75%</td>
                    <td>Maharashtra Board</td>
                </tr>
                <tr>
                    <td>FY B.Tech (IT)</td>
                    <td>N/A</td>
                    <td>SPPU</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="projects-container">
            <div class="project">
                <h3>Portfolio Website</h3>
                <p>A personal portfolio website to showcase my skills and projects.</p>
                <a href="https://github.com/yourgithub/portfolio" target="_blank">View Project</a>
            </div>
            <div class="project">
                <h3>To-Do List App</h3>
                <p>A simple and efficient to-do list app built with JavaScript.</p>
                <a href="https://github.com/yourgithub/todo-app" target="_blank">View Project</a>
            </div>
            <div class="project">
                <h3>Weather App</h3>
                <p>An app that fetches real-time weather data using an API.</p>
                <a href="https://github.com/yourgithub/weather-app" target="_blank">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:vishakhabhilwadkar@gmail.com">vishakhabhilwadkar@gmail.com</a></p>
        <p>Phone: 7756126241</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/vishakha-bhilwadkar-987722285?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app " target="_blank">Vishakha LinkedIn</a></p>
        <p>GitHub: <a href="https://github.com/VishakhaVB" target="_blank">Vishakha GitHub</a></p>
    </section>

    <footer>
        <p>© 2024 Vishakha. All rights reserved.</p>
    </footer>
</body>
</html>
