<!DOCTYPE html><html lang="en"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shaheer | UI/UX Designer & Front-End Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }body {
  font-family: 'Inter', sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
  padding: 2rem;
}

header {
  text-align: center;
  padding: 4rem 0;
  animation: fadeIn 1s ease-in-out;
}

header h1 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}

header p {
  font-size: 1.2rem;
  color: #666;
}

nav {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-bottom: 3rem;
  animation: fadeIn 1.2s ease-in-out;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: 600;
}

section {
  max-width: 900px;
  margin: 0 auto 3rem auto;
  padding: 1rem;
  animation: fadeIn 1.4s ease-in-out;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.project {
  background: #fff;
  padding: 1rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
  transition: transform 0.3s;
}

.project:hover {
  transform: translateY(-5px);
}

.contact {
  text-align: center;
}

footer {
  text-align: center;
  padding: 2rem 0;
  font-size: 0.9rem;
  color: #aaa;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

  </style>
</head><body>
  <header>
    <h1>Hey, I'm Shaheer</h1>
    <p>UI/UX Designer & Front-End Developer</p>
  </header>  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="about">
    <h2>About Me</h2>
    <p>I’m passionate about designing beautiful, user-friendly interfaces and bringing them to life through front-end development. I work with Figma, HTML, CSS, JavaScript, and React to create delightful digital experiences.</p>
  </section>  <section id="projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>A clean, modern personal portfolio designed in Figma and built using HTML, CSS, and JavaScript. <br><a href="#">View Live</a> | <a href="#">Read Case Study</a></p>
    </div>
    <div class="project">
      <h3>UI/UX Case Study</h3>
      <p>Redesigned a travel app to improve usability and reduce user drop-off. Focused on UX research, wireframes, and prototyping. <br><a href="#">View Prototype</a> | <a href="#">Read Full Study</a></p>
    </div>
  </section>  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Let's connect! Email me at <a href="mailto: siddiquizain169@gmail.com">zain@example.com</a></p>
    <p>or find me on <a href="#">LinkedIn</a> | <a href="#">GitHub</a></p>
  </section>  <footer>
    <p>&copy; 2025 Zain. All rights reserved.</p>
  </footer>
</body></html>
