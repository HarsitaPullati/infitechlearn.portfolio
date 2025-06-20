<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harshitha | Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Pullati Harshitha</h1>
    <p>Aspiring Web Developer | InfiTech Intern</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m Harshitha, an enthusiastic learner in web development. I’m currently doing an internship at InfiTech Learn. I enjoy creating simple, beautiful, and user-friendly websites.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript (Basics)</li>
      <li>Git & GitHub</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>This website shows my bio, skills, and contact details. Built using HTML and CSS.</p>
    </div>
    <div class="project">
      <h3>To-Do List App</h3>
      <p>A basic app to add and delete daily tasks using HTML, CSS, and JavaScript.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:pullatiharshitha@gmail.com">pullatiharshitha@gmail.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/pullatiharshitha@gmai">linkedin.com/in/pullatiharshitha@gmai</a></p>
  </section>

  <footer>
    <p>© 2025 Pullati Harshitha. All Rights Reserved.</p>
  </footer>
</body>
</html>
.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #4b6cb7;
  color: white;
  padding: 2rem;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  background: #333;
  padding: 0.5rem;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 1rem;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 2rem;
  max-width: 900px;
  margin: auto;
  background: white;
  margin-top: 1rem;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.project {
  margin-bottom: 1rem;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #4b6cb7;
  color: white;
  margin-top: 2rem;
}
