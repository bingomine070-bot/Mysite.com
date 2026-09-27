# Mysite.com
Js buy it
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>My Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: white;
      line-height: 1.6;
    }

    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
      background: linear-gradient(135deg, #111, #252525);
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 20px;
      background: rgba(15, 15, 15, 0.9);
      text-align: center;
      z-index: 10;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: #00c3ff;
    }

    header h1 {
      font-size: 55px;
      margin-bottom: 10px;
    }

    header h1 span {
      color: #00c3ff;
    }

    header p {
      font-size: 20px;
      color: #ccc;
      margin-bottom: 25px;
    }

    .button {
      display: inline-block;
      padding: 12px 25px;
      background: #00c3ff;
      color: black;
      text-decoration: none;
      border-radius: 25px;
      font-weight: bold;
    }

    section {
      padding: 80px 10%;
      min-height: 50vh;
    }

    section h2 {
      text-align: center;
      font-size: 35px;
      margin-bottom: 40px;
      color: #00c3ff;
    }

    .about {
      max-width: 800px;
      margin: auto;
      text-align: center;
      color: #ccc;
      font-size: 18px;
    }

    .skills {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .skill {
      background: #1e1e1e;
      padding: 15px 25px;
      border-radius: 10px;
      border: 1px solid #333;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .project {
      background: #1b1b1b;
      padding: 25px;
      border-radius: 15px;
      transition: 0.3s;
    }

    .project:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 30px rgba(0, 195, 255, 0.2);
    }

    .project h3 {
      margin-bottom: 10px;
      color: #00c3ff;
    }

    .project p {
      color: #bbb;
    }

    #contact {
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #080808;
      color: #777;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 40px;
      }

      nav a {
        margin: 0 6px;
        font-size: 13px;
      }
    }
  </style>
</head>

<body>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="home">
    <h1>Hi, I'm <span>Your Name</span></h1>
    <p>Web Developer • Designer • Creator</p>

    <a href="#projects" class="button">View My Work</a>
  </header>

  <section id="about">
    <h2>About Me</h2>

    <div class="about">
      <p>
        I'm a creative person who enjoys building websites,
        designing projects, and learning new technology.
        Welcome to my portfolio!
      </p>
    </div>
  </section>

  <section id="skills">
    <h2>My Skills</h2>

    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Web Design</div>
      <div class="skill">Graphic Design</div>
    </div>
  </section>

  <section id="projects">
    <h2>My Projects</h2>

    <div class="projects">

      <div class="project">
        <h3>Project One</h3>
        <p>
          A website or project you created.
        </p>
      </div>

      <div class="project">
        <h3>Project Two</h3>
        <p>
          Another project you want to showcase.
        </p>
      </div>

      <div class="project">
        <h3>Project Three</h3>
        <p>
          Add another project here.
        </p>
      </div>

    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>

    <p>Email: your@email.com</p>
    <br>

    <a href="mailto:your@email.com" class="button">
      Email Me
    </a>
  </section>

  <footer>
    <p>© 2026 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
