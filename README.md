<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Prafulla</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
      color: white;
      scroll-behavior: smooth;
    }

    nav {
      position: fixed;
      width: 100%;
      top: 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      padding: 1rem 2rem;
      z-index: 100;
    }

    nav h1 {
      font-size: 1.5rem;
      color: #00ffe7;
    }

    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: white;
      transition: 0.3s ease;
    }

    nav a:hover {
      color: #00ffe7;
    }

    header {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      flex-direction: column;
      padding: 2rem;
    }

    header h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    header p {
      font-size: 1.2rem;
      max-width: 600px;
    }

    .btn {
      margin-top: 2rem;
      padding: 0.8rem 2rem;
      background: #00ffe7;
      color: black;
      border: none;
      border-radius: 30px;
      font-weight: 600;
      box-shadow: 0 0 10px #00ffe7;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: black;
      color: #00ffe7;
      border: 1px solid #00ffe7;
    }

    section {
      padding: 5rem 2rem;
      text-align: center;
    }

    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 1rem;
    }

    .skills li {
      background: rgba(255, 255, 255, 0.05);
      padding: 0.7rem 1.5rem;
      border-radius: 20px;
      border: 1px solid #00ffe7;
    }

    .projects .card {
      background: rgba(255, 255, 255, 0.05);
      margin: 1rem auto;
      padding: 1rem;
      max-width: 600px;
      border-radius: 15px;
      box-shadow: 0 0 10px #00ffe7;
    }

    footer {
      background: rgba(255, 255, 255, 0.03);
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
      color: #aaa;
    }

    @media (max-width: 768px) {
      header h2 {
        font-size: 2rem;
      }

      nav {
        flex-direction: column;
        gap: 0.5rem;
      }

      .skills ul {
        flex-direction: column;
        gap: 0.5rem;
      }
    }
  </style>
</head>
<body>

  <nav>
    <h1>Prafulla</h1>
    <div>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header>
    <h2>Hey, I'm Prafulla</h2>
    <p>A driven UPSC aspirant, coder, fitness junkie.</p>
    <button class="btn">Explore More</button>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm just a techie with passion in gaming and building businesses.</p>
  </section>

  <section class="skills" id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>Python</li>
      <li>DBMS & SQL</li>
      <li>Fitness & Nutrition</li>
      <li>UPSC GS</li>
      <li>Web Development</li>
      <li>Entrepreneurship</li>
    </ul>
  </section>

  <section class="projects" id="projects">
    <h2>Projects</h2>
    <div class="card">
      <h3>Portfolio Website</h3>
      <p>This website itself. Fully responsive, clean, and fast.</p>
    </div>
    <div class="card">
      <h3>Python Automation</h3>
      <p>Scripts to make life easier—from study routines to email tasks. (Coming soon)</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Want to build something real? Hit me up: <br> <strong>prafultripathi682@gmail.com</strong></p>
  </section>

  <footer>
    Made by Prafulla
  </footer>

</body>
</html># html-portfolio
