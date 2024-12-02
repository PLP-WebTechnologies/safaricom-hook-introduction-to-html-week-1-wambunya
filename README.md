<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="A simple webpage example with text, images, and links.">
  <meta name="keywords" content="HTML, webpage, semantic tags, beginner">
  <meta name="author" content="Your Name">
  <title>Simple Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem 0;
      text-align: center;
    }
    nav {
      background: #333;
      color: white;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }
    img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to My Simple Webpage</h1>
  <p>A beginner-friendly HTML example</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>Hello! I'm a web development enthusiast learning how to create webpages using HTML and CSS. This simple webpage demonstrates the use of semantic tags for structure and common elements for content.</p>
</section>

<section id="gallery">
  <h2>Gallery</h2>
  <article>
    <h3>Image 1: Nature</h3>
    <img src="https://via.placeholder.com/600x400" alt="A beautiful nature scene">
    <p>This image showcases the serene beauty of nature.</p>
  </article>
  <article>
    <h3>Image 2: Cityscape</h3>
    <img src="https://via.placeholder.com/600x400" alt="A bustling cityscape">
    <p>Here's an image of a vibrant city at night.</p>
  </article>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <p>Feel free to reach out for collaboration or questions!</p>
  <ul>
    <li>Email: <a href="mailto:example@example.com">example@example.com</a></li>
    <li>LinkedIn: <a href="https://www.linkedin.com" target="_blank">My LinkedIn Profile</a></li>
    <li>GitHub: <a href="https://www.github.com" target="_blank">My GitHub</a></li>
  </ul>
</section>

<footer>
  <p>&copy; 2024 My Simple Webpage | Designed with HTML</p>
</footer>

</body>
</html>
