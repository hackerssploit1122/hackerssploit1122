<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bright Omni — Cybersecurity Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background-color: #0e0e0e;
      color: #e6e6e6;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(145deg, #0a0a0a, #1c1c1c);
      border-bottom: 2px solid #00b4d8;
    }
    h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
      color: #00b4d8;
    }
    h2 {
      color: #00b4d8;
      border-bottom: 2px solid #00b4d8;
      display: inline-block;
      padding-bottom: 4px;
      margin-bottom: 10px;
    }
    .section {
      max-width: 900px;
      margin: 60px auto;
      padding: 0 20px;
    }
    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .card {
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 5px #00b4d8;
    }
    .card h3 {
      color: #00b4d8;
      margin-top: 0;
    }
    a {
      color: #00b4d8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 30px;
      background-color: #0a0a0a;
      color: #777;
      font-size: 0.9em;
      border-top: 1px solid #222;
    }
    img {
      display: block;
      margin: 20px auto;
      border-radius: 10px;
      max-width: 90%;
    }
    button {
      background-color: #00b4d8;
      border: none;
      color: white;
      padding: 6px 12px;
      border-radius: 5px;
      cursor: pointer;
      margin-left: 10px;
    }
    button:hover {
      background-color: #0090b3;
    }
    form {
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 5px #00b4d8;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      margin-bottom: 15px;
      border-radius: 5px;
      border: none;
      background-color: #2a2a2a;
      color: #e6e6e6;
    }
    input:focus, textarea:focus {
      outline: 2px solid #00b4d8;
    }
    input[type="submit"] {
      background-color: #00b4d8;
      color: white;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      border-radius: 5px;
    }
    input[type="submit"]:hover {
      background-color: #0090b3;
    }
    #thankyou-message {
      display: none;
      background-color: #1f1f1f;
      color: #00b4d8;
      padding: 15px;
      margin-top: 10px;
      border-radius: 8px;
      text-align: center;
    }
  </style>
</head>

<body>
  <!-- Header -->
  <header>
    <h1>Bright Omni</h1>
    <p><strong>Cybersecurity Researcher & Web Penetration Tester</strong></p>
    <p>I find, report, and help fix vulnerabilities to make the web safer.</p>
    <button onclick="document.getElementById('projects').scrollIntoView({behavior:'smooth'})">View Projects</button>
    <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Contact Me</button>
  </header>

  <!-- About -->
  <section class="section" id="about">
    <h2>About Me</h2>
    <p>Hi! I'm <strong>Bright Omni</strong>, a dedicated ethical hacker and cybersecurity researcher passionate about uncovering vulnerabilities before malicious actors do. I specialize in web application security, API testing, and vulnerability assessments.</p>
    <p>My approach combines methodical testing with creative thinking — always staying curious, continuously learning, and keeping up with the latest attack vectors and defense strategies. I believe security should be accessible, proactive, and actionable.</p>
  </section>

  <!-- Skills -->
  <section class="section" id="skills">
    <h2>Skills & Tools</h2>
    <div class="skills">
      <div class="card"><h3>Burp Suite</h3></div>
      <div class="card"><h3>Nmap</h3></div>
      <div class="card"><h3>SQLMap</h3></div>
      <div class="card"><h3>ffuf</h3></div>
      <div class="card"><h3>Metasploit</h3></div>
      <div class="card"><h3>Wireshark</h3></div>
      <div class="card"><h3>OWASP Top 10</h3></div>
      <div class="card"><h3>API Security</h3></div>
      <div class="card"><h3>Python</h3></div>
      <div class="card"><h3>Bash</h3></div>
      <div class="card"><h3>JavaScript</h3></div>
      <div class="card"><h3>Linux</h3></div>
      <div class="card"><h3>Docker</h3></div>
      <div class="card"><h3>Git/GitHub</h3></div>
    </div>
  </section>

  <!-- Projects -->
  <section class="section" id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>SQL Injection on Test App</h3>
        <p>Found and exploited authentication bypass via SQL injection in a custom lab environment.</p>
        <p><strong>Tools:</strong> Burp Suite, SQLMap</p>
      </div>
      <div class="card">
        <h3>XSS Attack Demo</h3>
        <p>Demonstrated reflected and stored XSS vulnerabilities with session hijacking proof-of-concept.</p>
        <p><strong>Tools:</strong> Burp Suite, JavaScript</p>
      </div>
      <div class="card">
        <h3>Subdomain Enumeration Tool</h3>
        <p>Built a Python automation tool for discovering hidden subdomains and potential attack surface.</p>
        <p><strong>Tools:</strong> Python, ffuf</p>
      </div>
    </div>
  </section>

  <!-- Certificate -->
  <section class="section" id="certificate">
    <h2>Certification</h2>
    <p>Certificate in <strong>Cyber Security & Ethical Hacking</strong></p>
    <img src="certificate-bright-omni.jpg" alt="Bright Omni Cybersecurity Certificate">
  </section>

  <!-- Contact -->
  <section class="section" id="contact">
    <h2>Contact Me</h2>
    <p><strong>Phone:</strong> <a href="tel:+2348087069884">08087069884</a></p>
    <p>
      <strong>Email 1:</strong> <a id="email1" href="mailto:bright7omni@gmail.com">bright7omni@gmail.com</a>
      <button onclick="copyEmail('email1')">Copy</button>
    </p>
    <p>
      <strong>Email 2:</strong> <a id="email2" href="mailto:correctbright293@gmail.com">correctbright293@gmail.com</a>
      <button onclick="copyEmail('email2')">Copy</button>
    </p>
    <p><strong>LinkedIn:</strong> 
      <a href="https://www.linkedin.com/in/correct-bright-267a56355" target="_blank">
        linkedin.com/in/correct-bright-267a56355
      </a>
    </p>
    <p><strong>GitHub:</strong> 
      <a href="https://github.com/brightomni" target="_blank">github.com/brightomni</a>
    </p>
    <p><strong>Resume:</strong> <a href="resume.pdf" target="_blank">Download Resume</a></p>

    <h3>Send Me a Message</h3>
    <form id="contact-form" action="https://formspree.io/f/your_form_id_here" method="POST">
      <label>Your Name</label>
      <input type="text" name="name" required>

      <label>Your Email</label>
      <input type="email" name="_replyto" required>

      <label>Your Message</label>
      <textarea name="message" rows="5" required></textarea>

      <input type="submit" value="Send Message">
    </form>

    <div id="thankyou-message">
      ✅ Thank you for reaching out, your message has been sent successfully!
    </div>
  </section>

  <footer>
    <p>© 2026 Bright Omni — Ethical Hacking for a Safer Internet</p>
  </footer>

  <script>
    // Contact form handler (thank-you message)
    const form = document.getElementById('contact-form');
    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const formData = new FormData(form);
      const response = await fetch(form.action, {
        method: form.method,
        body: formData,
        headers: { 'Accept': 'application/json' }
      });
      if (response.ok) {
        form.reset();
        document.getElementById('thankyou-message').style.display = 'block';
      } else {
        alert('Sorry, something went wrong. Please try again.');
      }
    });

    // Copy email buttons
    function copyEmail(id) {
      const email = document.getElementById(id).textContent;
      navigator.clipboard.writeText(email);
      alert('Email copied: ' + email);
    }
  </script>
</body>
</html>
