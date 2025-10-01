<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Julien Largetpiet</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1a1a1a, #333);
      color: #f5f5f5;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem 10%;
      background: rgba(0, 0, 0, 0.7);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.5rem;
      color: #00e0ff;
    }

    nav a {
      color: #f5f5f5;
      text-decoration: none;
      margin-left: 2rem;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #00e0ff;
    }

    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: url("https://picsum.photos/1600/900?blur") center/cover no-repeat;
      position: relative;
    }

    .hero::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.6);
    }

    .hero-content {
      position: relative;
      z-index: 2;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
      color: #00e0ff;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .btn {
      background: #00e0ff;
      color: #111;
      padding: 0.75rem 2rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #00bcd4;
    }

    section {
      padding: 4rem 10%;
    }

    section h3 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: #00e0ff;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background: #222;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #111;
      color: #aaa;
    }

    footer a {
      color: #00e0ff;
      text-decoration: none;
      margin: 0 0.5rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Julien Largetpiet</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Hello, I'm Julien 👋</h2>
      <p>Developer • Builder • Tech Enthusiast</p>
      <a href="#projects" class="btn">See My Work</a>
    </div>
  </section>

  <section id="about">
    <h3>About Me</h3>
    <p>
      I’m passionate about technology, building clean solutions, and experimenting with new ideas.  
      Always learning, always curious 🚀.
    </p>
  </section>

  <section id="projects">
    <h3>Projects</h3>
    <div class="projects">
      <div class="card">
        <h4>🌐 Website</h4>
        <p>My personal site hosted at julienlargetpiet.tech</p>
      </div>
      <div class="card">
        <h4>⚡ Rust HTTP Server</h4>
        <p>A fast, multithreaded server written in Rust.</p>
      </div>
      <div class="card">
        <h4>📦 More Coming</h4>
        <p>Stay tuned for more projects!</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h3>Contact</h3>
    <p>Feel free to reach out to me:</p>
    <p>
      <a href="mailto:julien@example.com">📧 Email</a> |
      <a href="https://github.com/julienlargetpiet" target="_blank">💻 GitHub</a> |
      <a href="https://www.linkedin.com/in/YOUR-LINK" target="_blank">🔗 LinkedIn</a>
    </p>
  </section>

  <footer>
    <p>© 2025 Julien Largetpiet | Built with ❤️</p>
  </footer>

</body>
</html>


