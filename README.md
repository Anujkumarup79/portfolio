<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Anuj Kumar - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #2c3e50, #4ca1af);
      color: white;
      text-align: center;
      padding: 50px 20px;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid white;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      margin-bottom: 15px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    h2 {
      color: #2c3e50;
      margin-bottom: 10px;
    }

    section {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }

    .card {
      background-color: #ffffff;
      padding: 25px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .skill-boxes {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 10px;
    }

    .skill {
      background: #4ca1af;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      font-weight: bold;
      font-size: 15px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: background 0.3s;
    }

    .skill:hover {
      background: #357f90;
    }

    ul {
      padding-left: 20px;
    }

    li {
      margin-bottom: 8px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    input, textarea {
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    button {
      padding: 10px;
      background-color: #4ca1af;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #357f90;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
    }

    footer a {
      color: white;
      margin: 0 10px;
      font-size: 20px;
      transition: color 0.3s;
    }

    footer a:hover {
      color: #4ca1af;
    }
  </style>
</head>
<body>

  <header>
    <img src="WhatsApp Image 2025-04-24 at 10.40.36 AM.jpeg" alt="Anuj Kumar">
    <h1>Anuj Kumar</h1>
    <p>B.Tech Student | Web Developer</p>
  </header>

  <section class="card">
    <h2>About Me</h2>
    <p>Hello! I'm Anuj Kumar, a B.Tech student passionate about web development and tech projects. I enjoy building secure, clean, and user-friendly web applications.</p>
  </section>

  <section class="card">
    <h2>Skills</h2>
    <div class="skill-boxes">
      <div class="skill">HTML & CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Secure File Upload</div>
      <div class="skill">E-Waste Management</div>
    </div>
  </section>

  <section class="card">
    <h2>Projects</h2>
    <ul>
      <li><strong>Secure File Uploader:</strong> Web tool for uploading and encrypting files securely.</li>
      <li><strong>E-Waste Management System:</strong> A platform for managing e-waste disposal efficiently.</li>
    </ul>
  </section>

  <section class="card">
    <h2>Contact Me</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>Contact: ak4454578@gmail.com</p>
    <div style="margin: 10px 0;">
      <a href="https://github.com/anujkumar" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/anujkumar" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://twitter.com/anujkumar" target="_blank"><i class="fab fa-twitter"></i></a>
    </div>
    <p>&copy; 2025 Anuj Kumar</p>
  </footer>

</body>
</html>
