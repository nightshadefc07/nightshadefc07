!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Thoughts Hub</title>
  <style>
    /* Background gradient with multiple colors */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #000000, #ff6600, #1e90ff, #ff0000);
      color: #fff;
      text-align: center;
    }

    header {
      background: rgba(0,0,0,0.8);
      color: #fff;
      padding: 20px;
      border-bottom: 3px solid #ff6600;
    }

    .container {
      max-width: 800px;
      margin: 20px auto;
      background: rgba(255,255,255,0.05); /* slightly transparent */
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }

    h1, h2 {
      color: #ffcc00; /* golden yellow for headings */
    }

    p {
      color: #ffffff; /* main text white */
      font-size: 1.1rem;
      line-height: 1.5;
    }

    iframe {
      width: 100%;
      height: 360px;
      border-radius: 10px;
      margin-top: 15px;
      border: 3px solid #ff6600; /* orange border */
    }

    .social-links a {
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 15px;
      border-radius: 8px;
      transition: 0.3s;
    }

    .social-links a:nth-child(1) { background: #ff0000; color: #fff; } /* YouTube red */
    .social-links a:nth-child(2) { background: #1e90ff; color: #fff; } /* Instagram blue */
    .social-links a:nth-child(3) { background: #ff6600; color: #fff; } /* Facebook orange */
    .social-links a:nth-child(4) { background: #000000; color: #fff; } /* Twitter black */

    .social-links a:hover {
      transform: scale(1.1);
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Thoughts Hub</h1>
    <p>Sharing my thoughts and videos</p>
  </header>

  <div class="container">
    <h2>My Latest Video</h2>
    <!-- Embedded YouTube Shorts Video -->
    <iframe src="https://www.youtube.com/embed/W0eyjNEHwRw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    <h2>Social Media</h2>
    <div class="social-links">
      <a href="https://www.youtube.com/" target="_blank">YouTube</a>
      <a href="https://www.instagram.com/" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/" target="_blank">Facebook</a>
      <a href="https://twitter.com/" target="_blank">Twitter/X</a>
    </div>

    <h2>My Thoughts</h2>
    <p>Write your ideas, quotes, or updates here...</p>
  </div>
</body>
</html>
