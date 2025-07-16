

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Remote Internship Program</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Remote Internship Program</h1>
      <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Apply</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <h2>Join Our Remote Internship Program!</h2>
    <p>Learn by working on real projects.</p>
    <a href="#" class="btn">Apply Now</a>
  </section>

  <section class="about">
    <div class="container">
      <h3>About the Program</h3>
      <p>Our remote internships offer hands-on experience, mentorship, and flexibility. Build real-world skills from anywhere.</p>
    </div>
  </section>

  <section class="benefits">
    <div class="container">
      <h3>Why Join?</h3>
      <ul>
        <li>✅ Flexible Hours</li>
        <li>✅ Real Projects</li>
        <li>✅ Certificate on Completion</li>
      </ul>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>📧 Contact us: internship@example.com</p>
      <p>© 2025 Remote Internship Program. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>


---

✅ style.css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px;
}

header {
  background-color: #003366;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  font-size: 24px;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #fff;
  margin-right: 20px;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background-color: #e0f0ff;
  text-align: center;
  padding: 60px 20px;
}

.hero h2 {
  font-size: 32px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  background-color: #003366;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 4px;
  font-weight: bold;
}

.about, .benefits {
  background-color: #fff;
  margin-top: 30px;
  padding: 40px 20px;
  text-align: center;
}

.benefits ul {
  list-style: none;
  padding: 0;
  margin-top: 15px;
}

.benefits li {
  font-size: 18px;
  margin: 10px 0;
}

footer {
  background-color: #003366;
  color: #fff;
  text-align: center;
  padding: 20px 0;
  margin-top: 30px;
}

/* Responsive */
@media (max-width: 600px) {
  header .container,
  .about .container,
  .benefits .container,
  footer .container {
    padding: 10px;
    text-align: center;
  }

  nav a {
    display: block;
    margin: 5px 0;
  }

  .hero h2 {
    font-size: 24px;
  }

  .hero p {
    font-size: 16px;
  }
}




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Profile Card</title>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    integrity="sha512-papazx6L7zF5T3g1ViL3N6lm5YzMi27v9SRQkFexjZ5XbFHQ+d9YYL5WUw7GLV+Z3Whu37QqWtv7K/dHzROk7A=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: #f2f2f2;
      padding: 20px;
    }

    .card {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
      padding: 30px 20px;
      max-width: 350px;
      width: 100%;
      text-align: center;
    }

    .card img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
      border: 3px solid #ddd;
    }

    .card h2 {
      font-size: 22px;
      color: #333;
    }

    .card p.title {
      font-size: 16px;
      color: #777;
      margin-bottom: 10px;
    }

    .card p.bio {
      font-size: 14px;
      color: #555;
      margin: 10px 0 20px;
    }

    .social-icons a {
      margin: 0 10px;
      color: #555;
      font-size: 20px;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #0077b5; /* LinkedIn blue */
    }

    .social-icons a.github:hover {
      color: #333;
    }

    @media (max-width: 480px) {
      .card {
        padding: 20px 15px;
      }

      .card img {
        width: 100px;
        height: 100px;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://via.placeholder.com/120" alt="Profile Picture" />
    <h2>Ali Raza</h2>
    <p class="title">Front-End Developer</p>
    <p class="bio">Passionate about crafting responsive websites and intuitive user interfaces. Always learning and growing in the world of web development.</p>
    <div class="social-icons">
      <a href="#" target="_blank" title="LinkedIn">
        <i class="fab fa-linkedin"></i>
      </a>
      <a href="#" target="_blank" class="github" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
    </div>
  </div>
</body>
</html># Internship-task-1-
Html css internship task 
