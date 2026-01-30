<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Renz E. Capua | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background-color: #e6e1cd;
      color: #333;
      line-height: 1.6;
    }

    /* ===== NAVBAR ===== */
    nav {
      background: #1f1f1f;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav h2 {
      color: #fff;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 14px;
    }

    /* ===== HERO ===== */
    .hero {
      background: #a89072;
      text-align: center;
      padding: 80px 20px;
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 14px;
    }

    /* ===== SECTIONS ===== */
    section {
      padding: 70px 10%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
      font-size: 24px;
    }

    /* ===== ABOUT ===== */
    .about-boxes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .box {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      font-size: 14px;
    }

    /* ===== SKILLS ===== */
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .skill-card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }

    .progress {
      background: #ddd;
      border-radius: 20px;
      overflow: hidden;
      margin-top: 10px;
    }

    .progress span {
      display: block;
      height: 10px;
      background: #4caf50;
    }

    /* ===== PROJECTS ===== */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }

    .project-card h3 {
      margin-bottom: 10px;
    }

    /* ===== CONTACT ===== */
    .contact-form {
      max-width: 600px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 8px;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact-form button {
      background: #1f1f1f;
      color: #fff;
      border: none;
      padding: 12px 25px;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1f1f1f;
      color: #fff;
      font-size: 13px;
    }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav>
    <h2>Portfolio</h2>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero" id="home">
    <h1>Hello there! 👋<br>I'm Renz E. Capua</h1>
    <p>Happy to see you here!</p>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2 class="section-title">☕ About Me</h2>

    <div class="about-boxes">
      <div class="box">
        I'm a second-year Bachelor of Science in Computer Science student with a strong interest in design and technology. I enjoy blending creativity and functionality.
      </div>

      <div class="box">
        I'm also passionate about cycling. Riding helps me stay focused, creative, and balanced in both my technical and creative work.
      </div>

      <div class="box">
        🏆 Won first place in a university-wide design contest focused on creative mental health awareness campaigns.
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2 class="section-title">🛠 Design Skills</h2>

    <div class="skills">
      <div class="skill-card">
        <h3>UI/UX Design</h3>
        <p>Designing user-friendly interfaces with strong functionality.</p>
        <div class="progress">
          <span style="width: 85%"></span>
        </div>
      </div>

      <div class="skill-card">
        <h3>Adobe Photoshop</h3>
        <p>Creating and editing graphics for branding and content.</p>
        <div class="progress">
          <span style="width: 70%"></span>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2 class="section-title">📁 Projects</h2>

    <div class="projects">
      <div class="project-card">
        <h3>Mental Health Awareness Website</h3>
        <p>A creative web design project promoting mental health awareness using clean UI and visuals.</p>
      </div>

      <div class="project-card">
        <h3>Student Portfolio Website</h3>
        <p>A personal portfolio website built using HTML and CSS to showcase skills and projects.</p>
      </div>

      <div class="project-card">
        <h3>UI Redesign Concept</h3>
        <p>A UI/UX redesign concept for a mobile app focusing on usability and accessibility.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2 class="section-title">📬 Contact Me</h2>

    <div class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button>Send Message</button>
    </div>
  </section>

  <footer>
    © 2026 Renz E. Capua | All Rights Reserved
  </footer>

</body>
</html>
