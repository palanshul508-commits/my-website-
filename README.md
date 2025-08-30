# my-website-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
      text-align: center;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px;
    }
    header h1 {
      margin: 0;
    }
    nav {
      margin: 15px 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4CAF50;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
    }
    .about, .projects, .contact {
      background: white;
      margin: 20px auto;
      max-width: 800px;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      background: #333;
      color: white;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <p>Hello, I'm <b>Your Name</b> 👋</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>I am learning web development and this is my first personal website.</p>
  </section>

  <section id="projects" class="projects">
    <h2>My Projects</h2>
    <p>1. Portfolio Website</p>
    <p>2. Python Mini Programs</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: yourname@example.com</p>
    <p>Instagram: @yourusername</p>
  </section>

  <footer>
    <p>© 2025 Your Name | All Rights Reserved</p>
  </footer>
</body>
</html>
