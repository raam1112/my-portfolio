<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raamnath | Portfolio</title>
  <meta name="description" content="Raamnath's portfolio showcasing development skills and projects.">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
      transition: background 0.3s, color 0.3s;
    }
    nav {
      background-color: #161b22;
      padding: 1rem;
      text-align: center;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 999;
      box-shadow: 0 2px 5px rgba(0,255,0,0.1);
    }
    nav a {
      color: #58a6ff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #1f6feb;
    }
    header {
      padding: 8rem 2rem 3rem;
      text-align: center;
      background: url('https://i.postimg.cc/yxrQpGdV/7e5492e1-bce2-48e3-84ce-dd222f7cb6ff.jpg') no-repeat center center;
      background-size: cover;
      color: #ffffff;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
    }
    header img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid #58a6ff;
      margin-bottom: 1rem;
    }
    header h1 {
      font-size: 2.5rem;
      color: #ffffff;
    }
    header p {
      font-size: 1.2rem;
      color: #d1d5da;
    }
    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background-color: #161b22;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(88,166,255,0.1);
    }
    h2 {
      color: #58a6ff;
      margin-bottom: 1rem;
      border-bottom: 2px solid #30363d;
      padding-bottom: 0.5rem;
    }
    .skills-list li {
      display: inline-block;
      background: #30363d;
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      border-radius: 30px;
      color: #c9d1d9;
    }
    .certifications-list {
      list-style-type: none;
      padding-left: 0;
    }
    .certifications-list li {
      background: #21262d;
      margin: 0.5rem 0;
      padding: 0.75rem 1rem;
      border-left: 4px solid #58a6ff;
      border-radius: 5px;
    }
    .button {
      background: #238636;
      color: white;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #2ea043;
    }
    .social-links {
      text-align: center;
      margin-top: 2rem;
    }
    .social-links a {
      color: inherit;
      font-size: 1.8rem;
      margin: 0 10px;
      transition: transform 0.3s ease, color 0.3s ease;
    }
    .social-links a[href*="linkedin"] { color: #0077b5; }
    .social-links a[href*="github"] { color: #333; }
    .social-links a[href*="facebook"] { color: #3b5998; }
    .social-links a[href*="twitter"] { color: #1da1f2; }
    .social-links a[href*="instagram"] { color: #e1306c; }
    .social-links a[href*="leetcode"] { color: #f89f1b; }
    .social-links a[href*="skillrack"] { color: #00b894; }
    .social-links a:hover {
      transform: scale(1.2);
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #0d1117;
      color: #8b949e;
      font-size: 0.9rem;
    }

    .dark-mode {
      background-color: #0d1117;
      color: #c9d1d9;
    }
    .light-mode {
      background-color: #f0f1f6;
      color: #333;
    }
    .light-mode header {
      background: url('https://i.postimg.cc/yxrQpGdV/7e5492e1-bce2-48e3-84ce-dd222f7cb6ff.jpg') no-repeat center center;
      background-size: cover;
    }
    .light-mode nav {
      background-color: #f0f1f6;
      color: #333;
    }
    .light-mode nav a {
      color: #007bff;
    }

    .theme-toggle {
      position: fixed;
      top: 60px;
      right: 20px;
      background: #58a6ff;
      color: white;
      padding: 20px 25px;
      border-radius: 40px;
      cursor: pointer;
      font-size: 1rem;
      transition: background 0.3s;
    }
    .theme-toggle:hover {
      background: #1f6feb;
    }

    @media screen and (max-width: 768px) {
      header {
        padding: 6rem 1rem 2rem;
      }
      section {
        padding: 1.5rem;
      }
      .social-links a {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body class="dark-mode">

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#certifications">Certifications</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<header>
  <img src="https://th.bing.com/th/id/OIP.2VdM2TKxzgCdOA46eQEc3wHaHa?pid=ImgDet&w=192&h=192&c=7" alt="Raamnath profile picture">
  <h1>Raamnath</h1>
  <p>Aspiring Developer | Passionate about coding and technology</p>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>I am Raamnath, currently pursuing B.Tech in Information Technology at Sri Sairam Institute Of Technology. I'm an enthusiastic learner and love exploring new technologies and coding solutions to real-world problems.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul class="skills-list">
    <li>C</li>
    <li>C++</li>
    <li>Python</li>
  </ul>
</section>

<section id="certificates">
  <h2>Licenses & Certificates</h2>
  <ul class="cert-list">
    <li>
      <strong>Web Design Course for Beginner to Advanced</strong> – Udemy<br>
      <a href="https://www.udemy.com/certificate/UC-3d0f717b-52a5-414d-a05d-3bebdf753155/" target="_blank">View Certificate</a>
    </li>
    <li>
      <strong>Python</strong> – GeeksForGeeks<br>
      <a href="https://media.geeksforgeeks.org/courses/certificates/646bd8c3591321831fa580e30479dd49.pdf" target="_blank">View Certificate</a>
    </li>
    <li>
      <strong>Python(Basic)</strong> – HackerRank<br>
      <a href="https://www.hackerrank.com/certificates/795d3e04fa97" target="_blank">View Certificate</a>
    </li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <p>Explore my development projects and contributions on <a href="https://github.com/Raam1112" target="_blank">GitHub</a>.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <a class="button" href="mailto:raamnathannamalai@gmail.com">Email Me</a>
  <div class="social-links">
    <a href="https://linkedin.com/in/raamnath" target="_blank" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/Raam1112" target="_blank" aria-label="GitHub"><i class="fab fa-github"></i></a>
    <a href="mailto:raamnathannamalai@gmail.com" aria-label="Email"><i class="fas fa-envelope"></i></a>
    <a href="https://facebook.com/raamnath1211" target="_blank" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
    <a href="https://twitter.com/Raamnath1211" target="_blank" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com/rockstar_raam" target="_blank" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
    <a href="https://leetcode.com/raam1211" target="_blank" aria-label="LeetCode"><i class="fas fa-code"></i></a>
    <a href="https://skillrack.com/profile/501141/raamnath" target="_blank" aria-label="SkillRack"><i class="fas fa-laptop-code"></i></a>
  </div>
</section>

<footer>
  &copy; 2025 Raamnath. Designed with precision and passion.
</footer>

<button class="theme-toggle" onclick="toggleTheme()">Toggle Theme</button>

<script>
  function toggleTheme() {
    const body = document.body;
    const currentTheme = body.classList.contains('dark-mode') ? 'dark' : 'light';

    if (currentTheme === 'dark') {
      body.classList.remove('dark-mode');
      body.classList.add('light-mode');
    } else {
      body.classList.remove('light-mode');
      body.classList.add('dark-mode');
    }
  }
</script>

</body>
</html>
