<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Thobejane Dineo | Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #070707;
      margin: 0;
      padding: 0;
    }

    header {
      background: #f1d1d1;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }

    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }

    .card {
      background: #fff;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    a {
      color: #007acc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      background: #1f1f1f;
      color: white;
      padding: 1rem;
      margin-top: 3rem;
    }

    ul {
      padding-left: 20px;
    }

    h2 {
      color: #007acc;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 4px;
      border: 1px solid #ccc;
      border-radius: 6px;
      box-sizing: border-box;
      font-size: 1rem;
    }

    button {
      background-color: #007acc;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #005f99;
    }

    .whatsapp-button {
      display: inline-block;
      background-color: #25d366;
      color: white;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
      transition: background-color 0.3s ease;
    }

    .whatsapp-button:hover {
      background-color: #1ebd5a;
    }

    .resume-button {
      display: inline-block;
      background-color: #007acc;
      color: white;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
      transition: background-color 0.3s ease;
    }

    .resume-button:hover {
      background-color: #005f99;
    }
  </style>
</head>
<body>

  <header>
    <h1>Thobejane Dineo</h1>
    <p>Junior Developer | App & Web Creator </p>
  </header>

  <section class="card">
    <h2>👩‍💻 About Me</h2>
    <p>Hello! I'm Dineo, a passionate developer building apps and websites that solve real problems — especially for rural communities. I work with Flutter, Firebase, HTML/CSS/JS, and more.</p>

    <a href="Resume.pdf" download class="resume-button">📄 Download My Resume</a>
  </section>

  <section class="card">
    <h2>🌐 Web Projects</h2>
    <ul>
      <li><a href="file:///C:/Users/Dineo/Desktop/New%20folder/tiktok/index.html" target="_blank" rel="noopener noreferrer">Have a look</a></li>
      <li><a href="file:///C:/Users/Dineo/Desktop/New%20folder/website2/index.html" target="_blank" rel="noopener noreferrer">Have a look</a></li>
       <li><a href="file:///C:/Users/Dineo/Desktop/New%20folder/E-Commerce/index.html" target="_blank" rel="noopener noreferrer">Have a look</a></li>
      <li><a href="file:///C:/Users/Dineo/Desktop/New%20folder/toyota/index.html" target="_blank" rel="noopener noreferrer">Have a look</a></li>
    </ul>
  </section>

  <section class="card">
    <h2>📱 My Apps (Private)</h2>
    <p><strong>Note:</strong> I’ve developed powerful educational and service-based apps. They are kept private to protect my original ideas.</p>
    <p>If you're interested in viewing or collaborating, please <a href="#contact">contact me directly</a>.</p>
  </section>

  <section class="card">
    <h2>🎓 Certificates</h2>
    <ul>
      <li><a href="Qualification.pdf" target="_blank" rel="noopener noreferrer">Information Technology Management</a></li>
      <li><a href="Virtual Assistant.png" target="_blank" rel="noopener noreferrer">Virtual Assistant</a></li>
      <li><a href="certificates/dsa.pdf" target="_blank" rel="noopener noreferrer">Data Science<a></a></li>
      <li><a href="Data Science Job Simulation.pdf" target="_blank" rel="noopener noreferrer">Data Science Job Simulation<a></a></li>
      <li><a href="certificates/dsa.pdf" target="_blank" rel="noopener noreferrer">Explore Internet Search and beyond<a></a></li>
      <li><a href="AI Fluency.pdf" target="_blank" rel="noopener noreferrer">AI Fluency<a></a></li>
      <li><a href="Explore AI for All.pdf" target="_blank" rel="noopener noreferrer">Explore AI for All<a></a></li>
      <li><a href="Introduction to Data Science.pdf" target="_blank" rel="noopener noreferrer">Introduction to Data Science<a></a></li>
      <li><a href="Microsoft Copilot.pdf" target="_blank" rel="noopener noreferrer">Microsoft Copilot<a></a></li>
      <li><a href="Explore Generative AI.pdf" target="_blank" rel="noopener noreferrer">Explore Generative AI<a></a></li>
      <li><a href="Explore AI basics.pdf" target="_blank" rel="noopener noreferrer">Explore AI basics<a></a></li>
      <li><a href="Explore responsible AI.pdf" target="_blank" rel="noopener noreferrer">Explore responsible AI<a></a></li>
      <li><a href="Introduction to Cybersecurity.pdf" target="_blank" rel="noopener noreferrer">Introduction to Cybersecurity<a></a></li>
      <li><a href="Data Science with Python.pdf" target="_blank" rel="noopener noreferrer">Data Science with Python<a></a></li>
      <!-- Add more certificate links as needed -->
    </ul>
  </section>

  <section class="card" id="contact">
    <h2>📬 Contact Me</h2>
    <form action="https://formsubmit.co/thobejanedineo7@gmail.com" method="POST" >
      <input type="hidden" name="_captcha" value="false">

      <label for="name">Name:</label><br/>
      <input type="text" name="name" id="name" required><br/><br/>

      <label for="email">Email:</label><br/>
      <input type="email" name="email" id="email" required><br/><br/>

      <label for="message">Message:</label><br/>
      <textarea name="message" id="message" rows="5" required></textarea><br/><br/>

      <button type="submit">Send Message</button>
    </form>

    <br/>
    <h3>Or chat with me on WhatsApp:</h3>
    <a href="https://wa.me/27796372089" target="_blank" rel="noopener noreferrer" class="whatsapp-button">💬 Message Me on WhatsApp</a>
  </section>

  <footer>
    &copy; 2025 Thobejane Dineo
  </footer>

</body>
</html>


