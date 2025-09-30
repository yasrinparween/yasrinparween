<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yasrin Parween - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f0f2f5;
            color: #333;
        }

        header {
            background-color: #24292e;
            color: white;
            text-align: center;
            padding: 50px 20px 30px;
        }

        header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
        }

        header h1 {
            margin: 15px 0 5px;
        }

        header p {
            margin: 5px 0;
        }

        header a {
            color: #58a6ff;
            margin: 0 10px;
            text-decoration: none;
        }

        header a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }

        .section {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .section h2 {
            margin-top: 0;
            color: #24292e;
            border-bottom: 2px solid #58a6ff;
            display: inline-block;
            padding-bottom: 5px;
        }

        .skills span {
            display: inline-block;
            background-color: #58a6ff;
            color: white;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
            font-size: 14px;
        }

        .projects ul {
            list-style: none;
            padding-left: 0;
        }

        .projects li {
            background-color: #e1e4e8;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
        }

        .resume a {
            display: inline-block;
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
        }

        .resume a:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>
        <img src="images/profile.jpg" alt="Profile Photo">
        <h1>Yasrin Parween</h1>
        <p>Java Full Stack | Web Developer | ML Enthusiast</p>
        <p>
            <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank">GitHub</a> |
            <a href="https://www.linkedin.com/in/YOUR_LINKEDIN" target="_blank">LinkedIn</a> |
            <a href="mailto:YOUR_EMAIL">Email</a>
        </p>
    </header>

    <div class="container">
        <div class="section about">
            <h2>About Me</h2>
            <p>Final year B.Tech student (2026 passout) with 8.8 CGPA. Experienced as Web Developer Intern at Cognifyz Technologies and Java Developer Intern at Skill Craft. Passionate about web and software development.</p>
        </div>

        <div class="section skills">
            <h2>Skills</h2>
            <span>Java Full Stack</span>
            <span>Web Development</span>
            <span>SQL & NoSQL</span>
            <span>MongoDB</span>
            <span>Data Structures</span>
            <span>OS</span>
            <span>Software Development</span>
        </div>

        <div class="section projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Airline Database Management System:</strong> Manage airline operations efficiently using database management.</li>
                <li><strong>Spreadsheet Application (Excel Clone):</strong> Real-time spreadsheet functionality similar to Excel.</li>
                <li><strong>Real-time Face Detection Application:</strong> Detect faces using ML in live webcam feed.</li>
            </ul>
        </div>

        <div class="section resume">
            <h2>Resume</h2>
            <a href="resume.pdf" target="_blank">Download My Resume</a>
        </div>
    </div>
</body>
</html>
