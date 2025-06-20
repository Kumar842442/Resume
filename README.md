
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kumar Amrendra | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Kumar Amrendra</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="hero">
    <div class="container">
      <h2>Hello, I'm Kumar Amrendra</h2>
      <p>Frontend Developer | Tech Enthusiast | Lifelong Learner</p>
    </div>
  </section>

  <section id="about" class="section">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I'm a passionate developer with experience in building responsive web applications using HTML, CSS, JavaScript, and modern frameworks. I enjoy solving problems and learning new technologies.
      </p>
    </div>
  </section>

  <section id="skills" class="section">
    <div class="container">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>React</li>
        <li>Git & GitHub</li>
        <li>Responsive Design</li>
      </ul>
    </div>
  </section>

  <section id="projects" class="section">
    <div class="container">
      <h2>Projects</h2>
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio to showcase my skills and projects.</p>
      </div>
      <div class="project">
        <h3>Weather App</h3>
        <p>A weather app using OpenWeather API with real-time updates.</p>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </section>

  <section id="contact" class="section">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:kumar@example.com">kumar@example.com</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a></p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Kumar Amrendra. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}
.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
}
header {
  background: #333;
  color: #fff;
  padding: 20px 0;
}
header h1 {
  text-align: center;
}
nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  margin-top: 10px;
}
nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}
#hero {
  background: #0077cc;
  color: #fff;
  padding: 60px 0;
  text-align: center;
}
.section {
  padding: 40px 0;
}
.skills-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.skills-list li {
  background: #0077cc;
  color: white;
  padding: 8px 12px;
  border-radius: 5px;
}
.project {
  background: #eee;
  padding: 20px;
  margin-bottom: 20px;
  border-left: 5px solid #0077cc;
}
footer {
  background: #222;
  color: #aaa;
  text-align: center;
  padding: 15px 0;// Optional: Add smooth scroll effect
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    document.querySelector(this.getAttribute('href'))
      .scrollIntoView({ behavior: 'smooth' });
  });
});
  margin-top: 40px;
}
a:hover {
  text-decoration: underline;
}
