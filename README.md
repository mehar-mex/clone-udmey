<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Udemy Clone</title>

  <!-- Internal CSS for layout and styling -->
  <style>
    /* Reset and base styles */
    body {
      margin: 0;
      font-family: sans-serif;
      background: #f4f4f4;
    }

    /* Header section */
    header, footer {
      background: #5624d0;       /* Udemy's purple tone */
      color: #fff;
      text-align: center;
      padding: 1em;
    }

    /* Navigation links */
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
    }

    /* Hero/banner section */
    .hero {
      text-align: center;
      padding: 2em;
      background: #eee;
    }

    /* Course container */
    .courses {
      display: grid;
      gap: 1em;
      padding: 2em;
      max-width: 1000px;
      margin: auto;
    }

    /* Each course card */
    .card {
      background: #fff;
      padding: 1em;
      border-radius: 8px;
      box-shadow: 0 2px 5px #ccc;
    }

    .card img {
      width: 100%;
      border-radius: 5px;
    }

    .card h4 {
      margin: 0.5em 0 0.2em;
    }

    .card span {
      color: #5624d0;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <!-- Header with site title and nav links -->
  <header>
    <h1>MyUdemy</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Courses</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <!-- Hero section with a message -->
  <section class="hero">
    <h2>Learn Anywhere, Anytime</h2>
    <p>Top courses to boost your career.</p>
  </section>

  <!-- Static list of course cards -->
  <section class="courses">
    <div class="card">
      <img src="https://via.placeholder.com/300x150" alt="Course" />
      <h4>HTML & CSS Crash Course</h4>
      <p>Instructor: Alex</p>
      <span>$9.99</span>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x150" alt="Course" />
      <h4>JavaScript Basics</h4>
      <p>Instructor: Sara</p>
      <span>$14.99</span>
    </div>
  </section>

  <!-- Footer with copyright -->
  <footer>
    <p>&copy; 2025 MyUdemy</p>
  </footer>

</body>
</html>

