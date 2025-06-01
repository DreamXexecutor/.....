<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dream X Eceor</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(145deg, #0f0f0f, #1c1c1c);
      color: white;
      overflow-x: hidden;
    }

    header {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #00ffe5;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #00ffe5;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: url('https://www.transparenttextures.com/patterns/dark-mosaic.png');
    }

    .hero h1 {
      font-size: 48px;
      color: #00ffe5;
    }

    .hero p {
      font-size: 18px;
      margin-top: 10px;
      color: #ccc;
    }

    .cta {
      margin-top: 30px;
    }

    .cta a {
      background: #00ffe5;
      color: black;
      padding: 14px 28px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 10px;
      transition: background 0.3s;
    }

    .cta a:hover {
      background: #00d4bf;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 60px 40px;
    }

    .feature-card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 30px;
      backdrop-filter: blur(10px);
      text-align: center;
      transition: transform 0.3s;
    }

    .feature-card:hover {
      transform: translateY(-10px);
    }

    .feature-card h3 {
      color: #00ffe5;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      background: #0a0a0a;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: #777;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">Dream X Eceor</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Features</a>
    <a href="#">Discord</a>
    <a href="#">Script</a>
  </nav>
</header>

<section class="hero">
  <h1>Unleash the Power of Dream X Eceor</h1>
  <p>The most advanced Roblox toolset — built for dominance.</p>
  <div class="cta">
    <a href="#">Join Discord</a>
    <a href="#" style="margin-left: 10px;">Get Script</a>
  </div>
</section>

<section class="features">
  <div class="feature-card">
    <h3>⚔️ Full PvP AI</h3>
    <p>Auto combat, prediction, and evasion. Crush enemies automatically.</p>
  </div>
  <div class="feature-card">
    <h3>🎯 Aimbot & ESP</h3>
    <p>Target with precision. Full visual overlays and FOV controls.</p>
  </div>
  <div class="feature-card">
    <h3>🚀 Movement Engine</h3>
    <p>TP Walk, Ghost Mode, Infinite Jump, Float and more.</p>
  </div>
  <div class="feature-card">
    <h3>🧠 Clean UI</h3>
    <p>Modern, smooth, intuitive interface with full customization.</p>
  </div>
</section>

<footer>
  &copy; 2025 Dream X Eceor. Not affiliated with Roblox Corp.
</footer>

</body>
</html>
