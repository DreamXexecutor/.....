<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dream X Eceor - Downloads</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(145deg, #0f0f0f, #1c1c1c);
      color: white;
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
      padding: 60px 20px;
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

    .tabs {
      display: flex;
      justify-content: center;
      margin-top: 40px;
      border-bottom: 1px solid #333;
    }

    .tab-button {
      background: none;
      border: none;
      color: white;
      padding: 14px 20px;
      cursor: pointer;
      font-size: 16px;
      transition: color 0.3s ease;
    }

    .tab-button.active {
      border-bottom: 2px solid #00ffe5;
      color: #00ffe5;
    }

    .tab-content {
      display: none;
      padding: 20px;
      max-width: 800px;
      margin: 0 auto;
    }

    .tab-content.active {
      display: block;
    }

    .download-section {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 10px;
      padding: 20px;
      margin-top: 20px;
    }

    .download-section h2 {
      color: #00ffe5;
    }

    .download-section p {
      color: #ccc;
    }

    .download-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #00ffe5;
      color: black;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .download-button:hover {
      background-color: #00d4bf;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      background: #0a0a0a;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: #777;
      margin-top: 40px;
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
  <h1>Download Dream X Eceor</h1>
  <p>Select your preferred method to get started</p>
</section>

<div class="tabs">
  <button class="tab-button active" data-tab="tab1">Direct Download</button>
  <button class="tab-button" data-tab="tab2">Mirror Download</button>
  <button class="tab-button" data-tab="tab3">GitHub</button>
</div>

<div id="tab1" class="tab-content active">
  <div class="download-section">
    <h2>Direct Download</h2>
    <p>Get the latest version of Dream X Eceor directly from our servers.</p>
    <a href="#" class="download-button">Download Now</a>
  </div>
</div>

<div id="tab2" class="tab-content">
  <div class="download-section">
    <h2>Mirror Download</h2>
    <p>Download from our mirror site if the direct link is slow or unavailable.</p>
    <a href="#" class="download-button">Download from Mirror</a>
  </div>
</div>

<div id="tab3" class="tab-content">
  <div class="download-section">
    <h2>GitHub Repository</h2>
    <p>Access the source code and contribute to the project on GitHub.</p>
    <a href="#" class="download-button">View on GitHub</a>
  </div>
</div>

<footer>
  &copy; 2025 Dream X Eceor. Not affiliated with Roblox Corp.
</footer>

<script>
  const tabButtons = document.querySelectorAll('.tab-button');
  const tabContents = document.querySelectorAll('.tab-content');

  tabButtons.forEach(button => {
    button.addEventListener('click', () => {
      const target = button.getAttribute('data-tab');

      tabButtons.forEach(btn => btn.classList.remove('active'));
      tabContents.forEach(content => content.classList.remove('active'));

      button.classList.add('active');
      document.getElementById(target).classList.add('active');
    });
  });
</script>

</body>
</html>
