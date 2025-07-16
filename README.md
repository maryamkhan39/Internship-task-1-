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
