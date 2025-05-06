<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Your Name | Portfolio</title>
  <style>
    :root {
      --nord0: #2E3440;
      --nord1: #3B4252;
      --nord2: #434C5E;
      --nord3: #4C566A;
      --nord4: #D8DEE9;
      --nord5: #E5E9F0;
      --nord6: #ECEFF4;
      --nord7: #8FBCBB;
      --nord8: #88C0D0;
      --nord9: #81A1C1;
      --nord10: #5E81AC;
      --nord11: #BF616A;
      --nord12: #D08770;
      --nord13: #EBCB8B;
      --nord14: #A3BE8C;
      --nord15: #B48EAD;
    }
    
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
      margin: 0;
      padding: 0;
      background: var(--nord0);
      color: var(--nord6);
      line-height: 1.6;
    }
    
    @supports (font-variation-settings: normal) {
      body { font-family: 'Inter var', sans-serif; }
    }
    
    header {
      background: var(--nord1);
      color: var(--nord6);
      padding: 3rem 20px;
      text-align: center;
      border-bottom: 1px solid var(--nord2);
    }
    
    h1 {
      margin: 0;
      font-size: 2.5rem;
      color: var(--nord8);
    }
    
    h2 {
      color: var(--nord8);
      border-bottom: 1px solid var(--nord3);
      padding-bottom: 0.5rem;
      margin-top: 2rem;
    }
    
    h3 {
      color: var(--nord7);
    }
    
    nav {
      background: var(--nord2);
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    
    nav a {
      color: var(--nord6);
      padding: 1rem 1.5rem;
      text-decoration: none;
      transition: all 0.3s ease;
      font-weight: 500;
    }
    
    nav a:hover {
      background: var(--nord3);
      color: var(--nord8);
    }
    
    section {
      padding: 2rem 20px;
      max-width: 900px;
      margin: auto;
    }
    
    .project, .certification {
      background: var(--nord1);
      margin-bottom: 1.5rem;
      padding: 1.5rem;
      border-radius: 8px;
      border-left: 4px solid var(--nord10);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .project:hover, .certification:hover {
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    
    .language-tag {
      display: inline-block;
      background: var(--nord3);
      color: var(--nord8);
      padding: 0.4rem 0.8rem;
      margin: 0.3rem;
      border-radius: 20px;
      font-size: 0.9rem;
      font-weight: 500;
    }
    
    a {
      color: var(--nord8);
      text-decoration: none;
      transition: color 0.3s ease;
    }
    
    a:hover {
      color: var(--nord7);
      text-decoration: underline;
    }
    
    .btn {
      display: inline-block;
      background: var(--nord10);
      color: var(--nord6);
      padding: 0.6rem 1.2rem;
      border-radius: 4px;
      margin-top: 0.5rem;
      font-weight: 500;
      transition: background 0.3s ease;
    }
    
    .btn:hover {
      background: var(--nord9);
      text-decoration: none;
    }
    
    footer {
      text-align: center;
      padding: 2rem 20px;
      background: var(--nord1);
      color: var(--nord4);
      font-size: 0.9em;
      border-top: 1px solid var(--nord2);
    }
    
    ul {
      padding-left: 1.2rem;
    }
    
    li {
      margin-bottom: 0.8rem;
    }
    
    strong {
      color: var(--nord4);
    }
    
    .certification {
      display: flex;
      flex-direction: column;
    }
    
    .cert-link {
      align-self: flex-start;
      margin-top: 0.8rem;
    }
    
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
      
      nav a {
        width: 100%;
        text-align: center;
      }
      
      section {
        padding: 1.5rem 15px;
      }
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

<header>
  <h1>Your Name</h1>
  <p>Welcome to my GitHub portfolio!</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#languages">Languages</a>
  <a href="#projects">Projects</a>
  <a href="#experience">Experience</a>
  <a href="#certifications">Certifications</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>I'm a developer passionate about building web apps, scripts, and open-source tools. I focus on creating clean, efficient code and solving real-world problems with elegant solutions.</p>
</section>

<section id="languages">
  <h2>Most Used Languages</h2>
  <div class="language-tag">JavaScript</div>
  <div class="language-tag">Python</div>
  <div class="language-tag">HTML</div>
  <div class="language-tag">CSS</div>
  <div class="language-tag">TypeScript</div>
  <div class="language-tag">SQL</div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="project">
    <h3>Weather App</h3>
    <p>A responsive web application that displays real-time weather data using the OpenWeather API, with location detection and 5-day forecasts.</p>
    <a href="https://github.com/yourusername/weather-app" target="_blank" class="btn">View on GitHub</a>
  </div>

  <div class="project">
    <h3>Portfolio Site</h3>
    <p>This portfolio – built with modern HTML/CSS, featuring responsive design and dark mode. Hosted via GitHub Pages.</p>
    <a href="https://github.com/yourusername/portfolio" target="_blank" class="btn">View on GitHub</a>
  </div>
</section>

<section id="experience">
  <h2>Experience</h2>
  <ul>
    <li><strong>Software Engineering Intern</strong> at ABC Tech (Summer 2024)<br>
    Built internal dashboard tools using React and Node.js that improved team productivity by 30%</li>
    <li><strong>Freelance Web Developer</strong> (2023–2024)<br>
    Created responsive websites and web applications for small businesses and startups</li>
  </ul>
</section>

<section id="certifications">
  <h2>Certifications</h2>
  <div class="certification">
    <strong>Meta Front-End Developer Professional Certificate</strong>
    <span>Coursera – Issued Jan 2024</span>
    <a href="meta-frontend-cert.pdf" download class="btn cert-link">Download Certificate</a>
  </div>
  <div class="certification">
    <strong>Python for Everybody Specialization</strong>
    <span>University of Michigan, Coursera – Completed Dec 2023</span>
    <a href="python-certificate.pdf" download class="btn cert-link">Download Certificate</a>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p><strong>Email:</strong> <a href="mailto:yourname@example.com">yourname@example.com</a></p>
  <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a></p>
  <p><strong>GitHub:</strong> <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
  <p><strong>Resume:</strong> <a href="resume.pdf" download class="btn">Download PDF</a></p>
</section>

<footer>
  &copy; 2025 Your Name. All rights reserved.<br>
  Made with ♥ using the Nord color palette
</footer>

</body>
</html>