<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - REYNEIL AUREADA</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Arial', sans-serif;
      background: brown;
      color: white;
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 36px;
      color: white;
    }
    .navbar {
      background: grey;
      padding: 20px 40px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 10;
    }
    .navbar ul {
      list-style: none;
      display: flex;
      justify-content: right;
      gap: 20px;
    }
    .navbar a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 20px;
    }
    .navbar a:hover {
      color: white;
    }
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: #362828;
      color: white;
    }
    .hero h1 {
      font-size: 48px;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .btn {
      background: brown;
      padding: 10px 20px;
      border: none;
      color: black;
      font-size: 16px;
      border-radius: 5px;
      text-decoration: none;
    }
    .btn:hover {
      background: black;
    }
    .about {
      background: grey;
      padding: 50px 20px;
    }
    .about-content {
      display: flex;
      gap: 20px;
      align-items: center;
      justify-content: space-between;
    }
    .profile-pic {
      max-width: 300px;
      border-radius: 20px;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    }
    .about-content .text {
      max-width: 600px;
    }
    .about-content .text h3 {
      font-size: 28px;
      margin-bottom: 10px;
      color: black;
    }
    .about-content .text p {
      margin-bottom: 15px;
    }
    .social-icons a {
      color: brown;
      text-decoration: none;
      margin-right: 10px;
      font-weight: bold;
    }
    .social-icons a:hover {
      color: black;
    }
    .skills {
      background: grey;
      padding: 50px 20px;
    }
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      text-align: center;
    }
    .skill-item {
      background: black;
      padding: 20px;
      border-radius: 10px;
      color: white;
      font-size: 18px;
    }

    /* Projects Section */
    .projects {
      background: grey;
      padding: 50px 20px;
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .project-item {
      background: #251C1C;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
.project-item img {
  max-width: 90%; 
  height: auto;
  border-radius: 10px;
  margin-bottom: 10px;
}
    .project-item h3 {
      color: white;
      margin-bottom: 10px;
    }

    .project-item a {
      color: black;
      text-decoration: none;
    }

    .project-item a:hover {
      color: white;
    }
    .contact {
      background: grey;
      padding: 50px 20px;
    }

    .contact-form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 600px;
      margin: 0 auto;
    }

    .contact-form input,
    .contact-form textarea {
      padding: 10px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      background: black;
      color: white;
    }

    .contact-form button {
      background: black;
      padding: 10px 20px;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background: black;
    }
  </style>
</head>
<body>
 
  <header class="hero" id="home">
    <nav class="navbar">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
<section>
    <div class="hero-content">
      <h1>Hello, My Name is</h1>
      <h2>REYNEIL AUREADA</h2>
      <p class="role">Frontend Developer</p><br>
      <a href="https://sg.docworkspace.com/d/sIFG-9JqzAf3Q67wG?sa=601.1094" class="btn">RESUME</a>
    </div>
  </header>
  </section>
  <section id="about" class="about">
    <div class="container">
      <h2>About Me</h2>
      <div class="about-content">
        <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
        <div class="text">
          <h3>I’m REYNEIL AUREADA</h3>
          <p>A <strong>Frontend Developer</strong> based in <strong>Philippines</strong>.</p>
          <p>
            I creating responsive user interfaces and building web applications that enhance user experience.
          </p>
          <p>I’m always open to job opportunities where I can contribute and grow.</p>
          <div class="social-icons">
            <a href="">LinkedIn</a>
            <a href="https://github.com/ljescalicas">GitHub</a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="skills" class="skills">
    <div class="container">
      <h2>Programming Skills</h2>
      <div class="skills-grid">
        <div class="skill-item">HTML</div>
        <div class="skill-item">CSS</div>
        <div class="skill-item">JavaScript</div>
        <div class="skill-item">C++</div>
        <div class="skill-item">Java</div>
        <div class="skill-item">Visual Basic</div>
      </div>
    </div>
  </section>
  <section id="accomplishment" class="achievement">
    <div class="container">
      <h2>Acoomplishment</h2>
      <div class="project-grid">
        <div class="project-item">
          <img src="mtr.jpg" alt="Project 1">
          <h3>MTR</h3>
           
        </div>
        <div class="project-item">
          <img src="PHONE.jpg" alt="Project 2" style="  max-width: 26%; 
  height: auto;
  border-radius: 10px;
  margin-bottom: 10px;">
          <h3>PHONE</h3>    
        </div>
      </div>
    </div>
  </section>
  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form action="#" method="POST" class="contact-form">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>
  <footer>
    <p style="text-align: center; font-size: 20px">&copy; Portfolio 2025 REYNEIL AUREADA. All rights reserved.</p>
  </footer>
</body>
</html>
