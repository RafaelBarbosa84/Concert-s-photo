<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Concert Photo Gallery</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      text-align: center;
      padding: 2rem 1rem;
      background: #222;
    }
    h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Concert Photos</h1>
    <p>A collection of moments captured live</p>
  </header>
  <main class="gallery">
    <!-- Replace the src URLs below with your photo paths or upload links -->
    <img src="photos/photo1.jpg" alt="Concert 1" />
    <img src="photos/photo2.jpg" alt="Concert 2" />
    <img src="photos/photo3.jpg" alt="Concert 3" />
    <img src="photos/photo4.jpg" alt="Concert 4" />
  </main>
  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body>
</html>
