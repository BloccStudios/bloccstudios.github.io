<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blocc Studios</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      text-align: center;
      padding: 3rem 1rem;
      background: linear-gradient(to bottom, #111, #000);
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      color: #aaa;
    }
    nav {
      text-align: center;
      padding: 1rem;
      background-color: #111;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #e0b84f; /* gold accent */
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .service {
      background-color: #111;
      padding: 2rem;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px rgba(255, 215, 0, 0.1);
    }
    .service h3 {
      margin-top: 0;
      color: #e0b84f;
    }
    .contact {
      text-align: center;
    }
    .contact a {
      display: block;
      margin: 0.5rem 0;
      color: #e0b84f;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #111;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Blocc Studios</h1>
    <p>Own Your Sound, Own The Blocc</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2 style="text-align:center; color:#e0b84f;">Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Mixing</h3>
        <p>Professional mixing to balance and enhance your sound for a polished, industry-standard result.</p>
      </div>
      <div class="service">
        <h3>Mastering</h3>
        <p>Final mastering to make your track radio-ready, with clarity, punch, and power.</p>
      </div>
      <div class="service">
        <h3>Voice Over Recording</h3>
        <p>Crisp and clear recordings for ads, podcasts, narrations, and more in a professional studio environment.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2 style="color:#e0b84f;">Get In Touch</h2>
    <p>We’d love to work with you. Reach out today!</p>
    <a href="mailto:BloccStudios021@gmail.com">📧 BloccStudios021@gmail.com</a>
    <a href="https://instagram.com/bloccstudios_cpt" target="_blank">📷 Instagram: @bloccstudios_cpt</a>
  </section>

  <footer>
    <p>© 2025 Blocc Studios. All rights reserved.</p>
  </footer>
</body>
</html>
