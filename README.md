<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    /* CSS styles go here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    
    nav ul {
      list-style-type: none;
      padding: 0;
    }
    
    nav ul li {
      display: inline;
      margin-right: 20px;
    }
    
    section {
      padding: 50px 0;
      text-align: center;
    }
    
    .content {
      max-width: 800px;
      margin: 0 auto;
    }
    
    h2 {
      font-size: 2em;
    }
    
    p {
      font-size: 1.2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  
  <section id="about">
    <div class="content">
      <h2>About Me</h2>
      <p>I am a passionate web developer with expertise in HTML, CSS, JavaScript, and various frameworks.</p>
    </div>
  </section>
  
  <section id="experience">
    <div class="content">
      <h2>Experience</h2>
      <p>I have worked on several projects as a front-end developer and have experience collaborating with teams.</p>
    </div>
  </section>
  
  <section id="projects">
    <div class="content">
      <h2>Projects</h2>
      <p>Here are some of my notable projects:</p>
      <ul>
        <li>Project 1</li>
        <li>Project 2</li>
        <li>Project 3</li>
      </ul>
    </div>
  </section>
  
  <section id="contact">
    <div class="content">
      <h2>Contact Me</h2>
      <p>You can reach out to me via email at example@example.com</p>
    </div>
  </section>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.9.1/gsap.min.js"></script>
  <script>
    // JavaScript code and GSAP animations go here
    gsap.from("header", { duration: 1, y: -50, opacity: 0, ease: "power4.out" });
    gsap.from("section", { duration: 1, y: 50, opacity: 0, stagger: 0.2, ease: "power4.out" });
  </script>
</body>
</html>
