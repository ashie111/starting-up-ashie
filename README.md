# starting-up-ashie
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Header Section (Introduction) -->
    <header id="about">
        <h1>ASHIE</h1>
        <p>Welcome to my portfolio website;ashie</p>
    </header>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Web Development</li>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>R</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <!-- Getting started -->
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <!-- High school grad and freshman -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <!-- contact me at astina.pandey@gmail.com -->
    </section>

</body>
</html>
/* Reset some default browser styles */
body, h1, h2, ul, li {
    margin: 0;
    padding: 0;
}

/* Global Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f7;
}

.container {
    max-width: 960px;
    margin: 0 auto;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #3498db;
    color: #fff;
    padding: 60px 0;
    text-align: center;
}

header h1 {
    font-size: 36px;
}

/* Navigation Styles */
nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    background-color: #333;
}

nav li {
    margin: 0 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Section Styles */
section {
    background-color: #fff;
    padding: 40px;
    margin: 20px 0;
    border-radius: 5px;
}

section h2 {
    font-size: 24px;
    margin-bottom: 20px;
}

/* Footer Styles (optional) */
footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}

/* Responsive Styles */
@media screen and (max-width: 768px) {
    header h1 {
        font-size: 28px;
    }

    nav ul {
        flex-direction: column;
        text-align: center;
    }

    nav li {
        margin: 10px 0;
    }
}
