## Hi there 👋
<!--
**Bigbrada619** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- ⚡ Graphic Designer taking on the of Web Development and Animation
-->(https://github.com/user-attachments/files/28114401/home.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MAKE YOUR ORDERS HERE WITH BADMN KJ</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

  <header>
    <nav>
      <h1 class="logo">TOPTEN</h1>

      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-text">
      <h2>Hello, I'm</h2>
      <h1>Bigbrada</h1>
      <h3>A Creative Web Developer Graphics Designer Video Grapher Microsoft Application Freelancer</h3>
      <p>
        I design modern, responsive and attractive websites with clean UI and smooth animations.
      </p>

      <div class="buttons">
        <a href="#projects" class="btn">View Projects</a>
        <a href="#contact" class="btn2">Hire Me</a>
      </div>
    </div>

    <div class="hero-image">
      <img src="J:\phot\IMG_6986.JPG" alt="profile">
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Me</h2>
    <div class="about-container">
      <img src="J:\phot\IMG_6082.PNG" alt="about image">

      <div>
        <p>
          I am a passionate web designer and developer who loves building stylish and user-friendly websites.
          I enjoy creating modern designs, animations and responsive layouts.
        </p>

        <p>
          My goal is to become a professional full-stack developer and create amazing digital experiences.
        </p>
      </div>
    </div>
  </section>

  <section class="skills" id="skills">
    <h2>My Skills</h2>

    <div class="skill-box">
      <p>HTML</p>
      <div class="bar"><span style="width:95%"></span></div>

      <p>CSS</p>
      <div class="bar"><span style="width:90%"></span></div>

      <p>JavaScript</p>
      <div class="bar"><span style="width:80%"></span></div>

      <p>UI/UX Design</p>
      <div class="bar"><span style="width:85%"></span></div>
    </div>
  </section>

  <section class="projects" id="projects">
    <h2>My Projects</h2>

    <div class="project-container">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1172&auto=format&fit=crop" alt="project">
        <h3>Portfolio Website</h3>
        <p>A modern responsive portfolio website.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=1170&auto=format&fit=crop" alt="project">
        <h3>Restaurant Website</h3>
        <p>Beautiful restaurant landing page with menu section.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1170&auto=format&fit=crop" alt="project">
        <h3>Chat Application</h3>
        <p>Real-time messaging application design.</p>
      </div>

    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Me</h2>
    <a href="https://wa.me/256742455444" target="_blank" class="whatsapp-btn">
  Chat With Me on WhatsApp
</a>

    <form action="https://formsubmit.co/kakembojimmyjames619@gmail.com" method="POST">

  <input type="text" name="name" placeholder="Your Name" required>

  <input type="email" name="email" placeholder="Your Email" required>

  <textarea name="message" rows="6" placeholder="Your Message"></textarea>

  <button type="submit">Send Message</button>

</form>
  </section>

  <footer>
    <p>© 2026 BIGBRADA | All Rights Reserved</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
[java.js](https://github.com/user-attachments/files/28114423/java.js)
[style.css](https://github.com/user-attachments/files/28114437/style.css)
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #0f172a;
  color: white;
}

header {
  width: 100%;
  padding: 20px 8%;
  position: fixed;
  top: 0;
  left: 0;
  background: rgba(0,0,0,0.5);
  backdrop-filter: blur(10px);
  z-index: 1000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  color: #38bdf8;
  font-size: 30px;
}

nav ul {
  display: flex;
  gap: 25px;
  list-style: none;
}

nav ul li a {
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

nav ul li a:hover {
  color: #38bdf8;
}

.hero {
  min-height: 100vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 120px 8%;
  gap: 50px;
}

.hero-text h2 {
  font-size: 35px;
}

.hero-text h1 {
  font-size: 70px;
  color: #38bdf8;
}

.hero-text h3 {
  font-size: 35px;
  margin-bottom: 15px;
}

.hero-text p {
  line-height: 1.8;
  max-width: 500px;
}

.buttons {
  margin-top: 30px;
}

.btn,
.btn2 {
  padding: 12px 25px;
  text-decoration: none;
  border-radius: 30px;
  margin-right: 15px;
  transition: 0.3s;
}

.btn {
  background: #38bdf8;
  color: black;
}

.btn2 {
  border: 2px solid #38bdf8;
  color: white;
}

.btn:hover,
.btn2:hover {
  transform: scale(1.1);
}

.hero-image img {
  width: 350px;
  height: 350px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid #38bdf8;
}

section {
  padding: 100px 8%;
}

section h2 {
  text-align: center;
  font-size: 40px;
  margin-bottom: 50px;
  color: #38bdf8;
}

.about-container {
  display: flex;
  gap: 50px;
  align-items: center;
}

.about-container img {
  width: 300px;
  border-radius: 20px;
}

.about-container p {
  line-height: 1.9;
  margin-bottom: 20px;
}

.skill-box {
  max-width: 700px;
  margin: auto;
}

.skill-box p {
  margin: 15px 0;
}

.bar {
  background: #1e293b;
  height: 12px;
  border-radius: 20px;
}

.bar span {
  display: block;
  height: 100%;
  background: #38bdf8;
  border-radius: 20px;
}

.project-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.card {
  background: #1e293b;
  border-radius: 20px;
  overflow: hidden;
  transition: 0.4s;
}

.card:hover {
  transform: translateY(-10px);
}

.card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
}

.card h3 {
  padding: 20px 20px 10px;
}

.card p {
  padding: 0 20px 20px;
}

.contact form {
  max-width: 700px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

.contact input,
.contact textarea {
  padding: 15px;
  margin-bottom: 20px;
  border: none;
  border-radius: 10px;
  outline: none;
}

.contact button {
  padding: 15px;
  border: none;
  border-radius: 30px;
  background: #38bdf8;
  cursor: pointer;
  font-size: 18px;
  transition: 0.3s;
}

.contact button:hover {
  transform: scale(1.05);
}

footer {
  text-align: center;
  padding: 20px;
  background: #020617;
}

@media(max-width: 900px) {

  .hero,
  .about-container {
    flex-direction: column;
    text-align: center;
  }

  nav ul {
    display: none;
  }

  .hero-text h1 {
    font-size: 50px;
  }
}
