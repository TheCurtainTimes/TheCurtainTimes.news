<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curtain Times Magazine</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Newsreader:opsz,wght@6..72,400;6..72,700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #1d1e22;
      --accent-color: #e5c07b;
      --bg-color: #ffffff;
      --font-main: 'Newsreader', serif;
      --font-title: 'Newsreader', serif;
    }

    body {
      margin: 0;
      font-family: var(--font-main);
      background-color: var(--bg-color);
      color: var(--primary-color);
      line-height: 1.6;
    }

    .banner {
      border: 6px solid #0047ab;
      overflow: hidden;
      white-space: nowrap;
      background-color: #c8102e;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      padding: 1rem 0;
    }

    .banner-text {
      position: relative;
      top: 1rem;
      font-size: 4rem;
      display: inline-block;
      padding-left: 100%;
      animation: scrollBanner 15s linear infinite;
    }

    @keyframes scrollBanner {
      0% { transform: translateX(0); }
      100% { transform: translateX(-100%); }
    }

    header {
      text-align: center;
      padding: 2rem 0 1rem;
      border-bottom: 1px solid #ccc;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 1rem;
    }

    nav a {
      text-decoration: none;
      color: var(--primary-color);
      font-weight: bold;
      font-size: 0.95rem;
    }

    .cover-image {
      display: block;
      max-width: 100%;
      margin: 2rem auto;
      border: 4px solid #0047ab;
    }

    .issue-title {
      text-align: center;
      font-size: 2rem;
      font-family: var(--font-title);
      margin: 1rem 0;
      color: var(--primary-color);
    }
  </style>
</head>
<body>
  <div class="banner">
    <div class="banner-text">The Curtain Times</div>
  </div>
  <div style="text-align: center; margin-top: 1rem;">
    <img src="red-crown.png" alt="Red Crown Icon" style="height: 60px;">
  </div>

  <header>
    <nav>
      <a href="#">Issue</a>
      <a href="#">Archive</a>
      <a href="#">Reports</a>
      <a href="#">About</a>
    </nav>
  </header>

  <img src="curtain-times-cover.png" alt="Curtain Times Cover" class="cover-image">

  <h2 class="issue-title">Issue 1 – June 9, 2025</h2>
</body>
</html>
