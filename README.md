<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    /* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #0d1117;
  color: #fff;
  overflow-x: hidden;
}

/* Navbar */
header {
  padding: 20px 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 20px;
  font-weight: bold;
  color: #fff;
}

.nav-links {
  display: flex;
  list-style: none;
}

.nav-links li {
  margin-left: 30px;
}

.nav-links a {
  text-decoration: none;
  color: #fff;
  transition: 0.3s;
}

.nav-links a.active,
.nav-links a:hover {
  color: #00eaff;
}

/* Hero Section */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 100px 80px;
}

.hero-text {
  max-width: 600px;
}

.hero-text h3 {
  font-size: 22px;
  margin-bottom: 10px;
  color: #fff;
}

.hero-text h1 {
  font-size: 45px;
  margin-bottom: 10px;
  font-weight: bold;
}

.hero-text h2 {
  font-size: 26px;
  margin-bottom: 15px;
}

.hero-text h2 span {
  color: #00eaff;
}

.hero-text p {
  font-size: 16px;
  margin-bottom: 20px;
  line-height: 1.6;
  color: #c9c9c9;
}

/* Social Icons */
.social-icons {
  margin-bottom: 20px;
}

.social-icons a {
  display: inline-block;
  margin-right: 12px;
  font-size: 16px;
  color: #00eaff;
  border: 1px solid #00eaff;
  border-radius: 50%;
  padding: 8px;
  transition: 0.3s;
}

.social-icons a:hover {
  background: #00eaff;
  color: #0d1117;
}

/* Button */
.btn {
  padding: 10px 20px;
  background: #00eaff;
  border: none;
  border-radius: 25px;
  cursor: pointer;
  font-size: 16px;
  font-weight: bold;
  color: #0d1117;
  transition: 0.3s;
}

.btn:hover {
  background: #00c7d9;
}

/* Hero Image */
.hero-img img {
  width: 350px;
  height: auto;
  border-radius: 20px;
  box-shadow: 0 0 30px #00eaff;
}

  </style>
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/64d58efce2.js" crossorigin="anonymous"></script>
</head>
<body>
  <!-- Navbar -->
  <header>
    <nav>
      <div class="logo">Portfolio.</div>
      <ul class="nav-links">
        <li><a href="#" class="active">Home</a></li>
        <li><a href="">About</a></li>
        <li><a href="#">Skills</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h3>Hello, It's Me</h3>
      <h1>Ahmad Aslam</h1>
      <h2>And I'm a <span>Frontend Developer</span></h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Possimus nulla sed saepe rerum, animi expedita.</p>
      <div class="social-icons">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-github"></i></a>
        <a href="#"><i class="fab fa-linkedin-in"></i></a>
      </div>
      <button class="btn">Download CV</button>
    </div>
    <div class="hero-img">
      <img src="image.jpg" alt="profile">
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
