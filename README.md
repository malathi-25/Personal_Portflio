<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malathi's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="logo">Malathi</div>
        <nav class="nav-menu">
            <ul>
                <li><a href="#profile">Profile</a></li>
                <li><a href="#work">Work</a></li>
                <li><a href="#contact">Contact</a></li>
                </ul>
        </nav>
    </header>

    <section id="profile" class="section profile-section">
        <div class="profile-content">
            <img src="profile-image.jpg" alt="Malathi Profile Picture" class="profile-img">
            <h1>Hi, I'm Malathi</h1>
            <h2>[Your Professional Title/Tagline]</h2>
            <p>A brief introduction about your skills, passion, and what you do. Match the text from your Figma design here.</p>
        </div>
    </section>

    <section id="work" class="section work-section">
        <h2>🚀 My Work</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="project1-thumbnail.jpg" alt="Project 1 Thumbnail">
                <h3>Project Title 1</h3>
                <p>Short description of the project and your role.</p>
                <a href="[Link to live demo or GitHub]" target="_blank">View Project</a>
            </div>
            <div class="project-card">
                <img src="project2-thumbnail.jpg" alt="Project 2 Thumbnail">
                <h3>Project Title 2</h3>
                <p>Short description of the project and your role.</p>
                <a href="[Link to live demo or GitHub]" target="_blank">View Project</a>
            </div>
            </div>
    </section>

    <section id="contact" class="section contact-section">
        <h2>📧 Contact Me</h2>
        <form class="contact-form">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit" class="submit-btn">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p>&copy; 2026 Malathi. Designed based on Figma. All rights reserved.</p>
        <div class="social-links">
            <a href="[Your GitHub URL]" target="_blank">GitHub</a> |
            <a href="[Your LinkedIn URL]" target="_blank">LinkedIn</a>
        </div>
    </footer>

</body>
</html>
