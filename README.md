<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Ayan Raza | Graphic Designer</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Ayan Raza</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Hi, I'm Ayan Raza</h2>
    <p>A creative Graphic Designer who loves turning ideas into visuals.</p>
    <a href="projects.html" class="btn">View My Work</a>
  </section>

  <footer>© 2025 Ayan Raza | All rights reserved.</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>About | Ayan Raza</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Ayan Raza</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <h2>About Me</h2>
    <p>Hello! I'm Ayan Raza, a passionate Graphic Designer from India. I specialize in logo design, branding, and creative visuals that help brands stand out.</p>
  </section>

  <footer>© 2025 Ayan Raza | All rights reserved.</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Projects | Ayan Raza</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Ayan Raza</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <h2>My Projects</h2>
    <div class="project-grid">
      <div class="project">
        <img src="https://via.placeholder.com/300" alt="Project 1">
        <h3>Logo Design 1</h3>
        <p>Brand logo for a startup company.</p>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300" alt="Project 2">
        <h3>Poster Design</h3>
        <p>Event poster created for a music festival.</p>
      </div>
    </div>
  </section>

  <footer>© 2025 Ayan Raza | All rights reserved.</footer>
</body>
</html><!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Contact | Ayan Raza</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Ayan Raza</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="projects.html">Projects</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:razagraphic321@gmail,com">ayanraza@example.com</a></p>
    <p>Instagram: <a href="https://instagram.com/" target="_blank">raza_graphic321</a></p>
  </section>

  <footer>© 2025 Ayan Raza | All rights reserved.</footer>
</body>
</html>
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  background-color: #f8f8f8;
  color: #333;
}

header {
  background-color: #111;
  color: #fff;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
}

nav a:hover {
  color: #ff6f61;
}

.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(to right, #ff6f61, #ff9a76);
  color: white;
}

.btn {
  background: white;
  color: #ff6f61;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
}

.content {
  max-width: 900px;
  margin: 50px auto;
  padding: 20px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.project img {
  width: 100%;
  border-radius: 10px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #111;
  color: white;
  margin-top: 50px;
}

