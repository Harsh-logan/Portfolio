
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harsh Sinha - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
            color: #c9d1d9;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background: rgba(22, 27, 34, 0.9);
            padding: 50px 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 25px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: #58a6ff;
            text-decoration: none;
            font-size: 20px;
            font-weight: 600;
            transition: color 0.3s ease-in-out;
        }
        nav ul li a:hover {
            color: #1f6feb;
        }
        .profile-photo {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            border: 5px solid #58a6ff;
            margin-top: 20px;
        }
        .section {
            padding: 80px 20px;
            border-bottom: 1px solid #30363d;
            position: relative;
            background: rgba(22, 27, 34, 0.85);
            border-radius: 12px;
            margin: 30px auto;
            max-width: 900px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
        }
        h2 {
            color: #58a6ff;
            margin-bottom: 20px;
            font-size: 30px;
            font-weight: 700;
        }
        .project, .skills-list {
            max-width: 800px;
            margin: 30px auto;
            padding: 30px;
            background: rgba(34, 40, 49, 0.9);
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            transition: transform 0.3s ease-in-out;
        }
        .project:hover, .skills-list:hover {
            transform: scale(1.05);
        }
        footer {
            background: rgba(22, 27, 34, 0.9);
            padding: 30px;
            font-size: 16px;
            color: #8b949e;
        }
    </style>
</head>
<body>
    <header>
        <h1>Harsh Sinha</h1>
        <p>Backend Developer</p>
        <img src="profile.jpg" alt="Profile Photo" class="profile-photo">
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>Enthusiastic and resourceful Computer Science graduate with a strong background in backend development and problem-solving.</p>
    </section>
    
    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project">
            <h3>Jarvis Automation</h3>
            <p>AI-based automation using Python and Speech Recognition.</p>
        </div>
        <div class="project">
            <h3>Security Camera</h3>
            <p>Facial recognition-based security system using OpenCV.</p>
        </div>
    </section>
    
    <section id="skills" class="section">
        <h2>Skills</h2>
        <div class="skills-list">
            <ul>
                <li>Java, Python, Go</li>
                <li>SQL, MySQL</li>
                <li>Data Structures & Algorithms</li>
                <li>Machine Learning</li>
                <li>Networking & Linux</li>
            </ul>
        </div>
    </section>
    
    <section id="education" class="section">
        <h2>Education</h2>
        <p>MCA - Galgotias University (Pursuing)</p>
        <p>BCA - IGNOU, Delhi (CGPA: 6.5)</p>
    </section>
    
    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>Email: harshlogan20@gmail.com</p>
        <p>Phone: +91 7827750546</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/harsh-sinha-15b20a193">Profile</a></p>
    </section>
    
    <footer>
        <p>&copy; 2025 Harsh Sinha | All Rights Reserved</p>
    </footer>
</body>
</html>
