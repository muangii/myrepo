#myrepo


<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    :root {
      --primary-color: #800000; /* Maroon */
      --accent-color: #d4af37;  /* Soft Gold */
      --background-color: #f3ece7; /* Warm neutral to complement maroon */
      --text-color: #333;
      --heading-font: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      --body-font: 'Arial', sans-serif;
    }

    body {
      margin: 0;
      padding: 0;
      background-color: var(--background-color);
      font-family: var(--body-font);
      color: var(--text-color);
    }

    header {
      background-color: var(--primary-color);
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      font-size: 4rem;
      font-weight: bold;
      background: linear-gradient(45deg, #FFD700, #fff1b5);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      padding: 10px 20px;
      border-radius: 12px;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
    }

    h1, h2 {
      font-family: var(--heading-font);
      color: var(--primary-color);
    }

    .bio {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .bio img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 4px solid var(--accent-color);
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
    }

    .skill-tag {
      background-color: var(--accent-color);
      color: white;
      padding: 8px 15px;
      border-radius: 20px;
      font-weight: bold;
    }

    .portfolio-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: white;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .cta-button {
      background-color: var(--accent-color);
      color: var(--primary-color);
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    form {
      max-width: 500px;
      margin: auto;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact-info {
      text-align: center;
      margin-top: 30px;
    }

    .contact-info p {
      margin: 5px 0;
    }

    .contact-info a {
      color: var(--primary-color);
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background-color: var(--primary-color);
      color: black;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">M</div>
    <nav>
      <a href="#about">About Me</a>
      <a href="#skills">Skills</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <div class="bio">
      <img src="https://via.placeholder.com/150" alt="Professional Photo" />
      <h1>About Me</h1>
      <p>
        Hello! I'm a passionate and driven data analyst with a deep interest in technology and innovation. I specialize in cloud computing, AI, and predictive analytics, and I enjoy using data to uncover meaningful insights and solve real-world problems.
      </p>
      <p>
        What makes me unique is my combination of technical expertise and a creative mindset. I enjoy presenting data in visually compelling ways, blending storytelling with analytics. My mission is to contribute to data-driven solutions that make a positive impact.
      </p>
      <p>
        My ideal job title is <strong>Data Analyst or AI Solutions Architect</strong>, roles that allow me to harness my skills and passions. I chose this specialization because it aligns with my long-term goal of driving innovation and transformation through data.
      </p>
      <p>
        One of the GCGOs that resonates most with me is <strong>"Global Citizenship and Innovation"</strong>. It connects directly with my desire to impact global challenges using modern technologies. My specialization in data analysis allows me to align my skills with this goal—whether by optimizing healthcare solutions, improving sustainability efforts, or designing ethical AI models.
      </p>
      <p>
        Top insights from experts in my field include:
        <ul>
          <li>Continuously build your portfolio with real-world projects.</li>
          <li>Stay updated with emerging technologies and tools.</li>
          <li>Network with professionals and seek mentorship.</li>
        </ul>
      </p>
    </div>
  </section>

  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <span class="skill-tag">Python</span>
      <span class="skill-tag">SQL</span>
      <span class="skill-tag">Tableau</span>
      <span class="skill-tag">Power BI</span>
      <span class="skill-tag">Cloud Computing</span>
      <span class="skill-tag">Data Visualization</span>
      <span class="skill-tag">Machine Learning</span>
    </div>
  </section>

  <section id="portfolio">
    <h2>My Work</h2>
    <div class="portfolio-container">
      <div class="project-card">
        <h3>Sales Forecasting Dashboard</h3>
        <p>Created a predictive dashboard using Python and Power BI to forecast quarterly sales and provide actionable insights.</p>
      </div>
      <div class="project-card">
        <h3>Healthcare Data Analysis</h3>
        <p>Analyzed patient data to uncover trends and optimize treatment strategies using Python and machine learning.</p>
      </div>
      <div class="project-card">
        <h3>Cloud Resource Optimization</h3>
        <p>Designed a cost-effective cloud infrastructure with AWS to scale enterprise data operations.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your name" required />
      <input type="email" placeholder="Your email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button class="cta-button" type="submit">Send Message</button>
    </form>
    <div class="contact-info">
      <p>Phone: +254 745679169</p>
      <p>Email: <a href="mailto:muangiimaina@gmail.com">muangiimaina@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/martin-maina-b0521635a/" target="_blank">linkedin.com/in/martin-maina-b0521635a</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>

