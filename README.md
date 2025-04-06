<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muhammad Ali – HSE Officer</title>

  <style>
    /* Basic Reset */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    /* Navigation Bar */
    nav {
      background-color: #003366;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 10px;
      display: inline-block;
      margin: 0 15px;
    }

    nav a:hover {
      background-color: #0055a4;
      border-radius: 5px;
    }

    /* Header Section */
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header img {
      height: 60px;
      vertical-align: middle;
    }

    header h1 {
      display: inline-block;
      margin-left: 15px;
      vertical-align: middle;
    }

    /* Section Style */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #003366;
    }

    .section-bg {
      background-color: #e9f5ff;
    }

    /* Contact Form */
    form input, form textarea, form button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      background-color: #003366;
      color: white;
      border: none;
      cursor: pointer;
    }

    form button:hover {
      background-color: #0055a4;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <div style="max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-around; align-items: center;">
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#certifications">Certifications</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- Header Section -->
  <header>
    <img src="logo.png" alt="Logo" />
    <h1>Muhammad Ali – HSE Officer</h1>
    <p>Committed to Health, Safety & Environmental Excellence</p>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I am a dedicated and results-driven Health, Safety, and Environmental (HSE) Officer with over five years of experience ensuring the safety and well-being of employees across industrial and construction projects in Saudi Arabia...</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="section-bg">
    <h2>Projects</h2>
    <ul>
      <li><strong>Risk Assessment & Hazard Control – Shandong Tiejun</strong><br>Led a full-site risk assessment project, reducing injuries by 25% within six months.</li>
      <li><strong>Safety Audit & Compliance – Shandong Tiejun</strong><br>Improved external audit scores by 30% after identifying and correcting safety gaps.</li>
      <li><strong>Training Program Development – Shandong Tiejun</strong><br>Designed a safety training program with 95% employee participation.</li>
      <li><strong>Emergency Response Enhancement – ESF Shandong Tiejun</strong><br>Upgraded emergency protocols and standardized them across multiple branches.</li>
      <li><strong>Environmental Sustainability Initiative – Shapoorji Pallonji</strong><br>Cut hazardous waste costs by 15% and energy usage by 10%.</li>
    </ul>
  </section>

  <!-- Certifications Section -->
  <section id="certifications">
    <h2>Certifications</h2>
    <ul>
      <li><strong>NEBOSH International General Certificate</strong> – NEBOSH, UK</li>
      <li><strong>ISO 45001:2018 Lead Auditor</strong> – Occupational Health & Safety Management</li>
      <li><strong>OSHA 30-Hour General Industry</strong> – OSHA, USA</li>
      <li><strong>Basic First Aid & CPR</strong> – Certified Emergency First Responder</li>
      <li><strong>Fire Safety & Emergency Preparedness</strong> – Fire Warden Certification</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact" style="padding: 60px 20px; background-color: #e9f5ff;">
    <div style="max-width: 1000px; margin: 0 auto; text-align: center;">
      <h2>Contact Me</h2>
      <form action="https://formsubmit.co/YOUR_EMAIL" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

</body>
</html>

