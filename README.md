<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Danyatu Enterprise Developer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <div class="logo">DANYATU</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#cv">CV</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  background: #f5f5f5;
  color: #222;
  line-height: 1.6;
}

header {
  background: #111;
  color: #fff;
  padding: 1rem 2rem;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #00bcd4;
}

.hero {
  background: #00bcd4;
  color: white;
  text-align: center;
  padding: 4rem 2rem;
}

.about, .projects, .contact {
  padding: 3rem 2rem;
  text-align: center;
}

.project-list {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
}

.project-card {
  background: white;
  padding: 1rem;
  border-radius: 8px;
  width: 300px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.contact form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.contact input, .contact textarea {
  padding: 0.8rem;
  border: 1px solid #ccc;
  border-radius: 6px;
}

.contact button {
  padding: 0.8rem;
  background: #00bcd4;
  color: white;
  border: none;
  cursor: pointer;
  border-radius: 6px;
}

.contact button:hover {
  background: #0097a7;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #111;
  color: white;
}

  <section id="home" class="hero">
    <h1>Welcome to Danyatu Enterprise Developer</h1>
    <p>Smart Digital Solutions for a Better Tomorrow</p>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>Danyatu Enterprise Developer specializes in providing ICT solutions, software development, and digital innovation to businesses and individuals.</p>
  </section>

  <section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <div class="project-list">
      <div class="project-card">
        <h3>School Management System</h3>
        <p>A full system to manage students, staff, and academics efficiently.</p>
      </div>
      <div class="project-card">
        <h3>Inventory App</h3>
        <p>Custom inventory tracking system for local enterprises.</p>
      </div>
    </div>
  </section>

  <section id="cv" class="cv">
    <h2>My CV</h2>
    <p>Download my latest curriculum vitae:</p>
    <a class="cv-download" href="cv.pdf" download>Download CV (PDF)</a>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Phone: 0715488044 / 0702540129<br>Email: <a href="mailto:princedancan27@gmail.com">princedancan27@gmail.com</a></p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <div class="map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15955.036022588697!2d35.01070095!3d-0.6293728999999999!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x182da15b2d7d6c4d%3A0x9e5af85cd35b35a2!2sKebirigo%2C%20Kenya!5e0!3m2!1sen!2ske!4v1721451000000" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div class="whatsapp">
      <a href="https://wa.me/254715488044" target="_blank">
        <img src="https://img.icons8.com/color/48/000000/whatsapp--v1.png" alt="WhatsApp" /> Chat with us on WhatsApp
      </a>
    </div>
  </section>
    <p>© 2025 Danyatu Enterprise Developer | All rights reserved</p>
  </footer>
</body>
</html>
