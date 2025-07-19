<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SAMOSA GANG</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fff8e1;
      color: #333;
    }
    header {
      background: #ffb300;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .gallery, .videos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    img, iframe {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea, button {
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
    }
    input, textarea {
      background: #fff3e0;
    }
    button {
      background: #ffb300;
      color: white;
      cursor: pointer;
    }
    footer {
      background: #ffe082;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔥 SAMOSA GANG 🔥</h1>
    <p>Friends Forever. Memories Forever.</p>
  </header>

  <section>
    <h2>About Us</h2>
    <p>We're a legendary group of friends who believe in fun, laughter, and lots of samosas 🥟</p>
  </section>

  <section>
    <h2>Photo Gallery 📸</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Photo+1" alt="Photo 1">
      <img src="https://via.placeholder.com/300x200?text=Photo+2" alt="Photo 2">
      <img src="https://via.placeholder.com/300x200?text=Photo+3" alt="Photo 3">
    </div>
  </section>

  <section>
    <h2>Videos 🎥</h2>
    <div class="videos">
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Video 1" frameborder="0" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/3JZ_D3ELwOQ" title="Video 2" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <section>
    <h2>Join the SAMOSA GANG 🥳</h2>
    <p>Want to be part of our awesome gang? Fill out the form below and we might just let you in 😎</p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="4" placeholder="Why do you want to join us?" required></textarea>
      <button type="submit">Join Us</button>
    </form>
  </section>

  <footer>
    <p>© 2025 SAMOSA GANG. Made with ❤️</p>
  </footer>
</body>
</html>
