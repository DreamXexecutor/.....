<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dream X Eceor | Download</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet" />
  <style>
    /* Reset and base */
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0d1117, #161b22);
      color: #c9d1d9;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* Header */
    header {
      background: rgba(13,17,23,0.95);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      border-bottom: 1px solid #30363d;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    .logo {
      color: #58a6ff;
      font-weight: 700;
      font-size: 1.6rem;
      user-select: none;
    }
    nav a {
      color: #8b949e;
      margin-left: 24px;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease;
      user-select: none;
    }
    nav a:hover {
      color: #58a6ff;
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 80px 20px 40px;
      max-width: 700px;
      margin: 0 auto;
    }
    .hero h1 {
      font-size: 3.5rem;
      color: #58a6ff;
      margin-bottom: 10px;
      user-select: none;
    }
    .hero p {
      font-size: 1.2rem;
      color: #8b949e;
      user-select: none;
    }

    /* Tabs */
    .tabs {
      display: flex;
      justify-content: center;
      gap: 30px;
      border-bottom: 1px solid #30363d;
      max-width: 720px;
      margin: 0 auto;
      user-select: none;
    }
    .tab-button {
      background: none;
      border: none;
      padding: 14px 24px;
      font-size: 1rem;
      color: #8b949e;
      cursor: pointer;
      border-bottom: 3px solid transparent;
      transition: all 0.3s ease;
      font-weight: 600;
    }
    .tab-button:hover {
      color: #58a6ff;
    }
    .tab-button.active {
      color: #58a6ff;
      border-bottom: 3px solid #58a6ff;
      cursor: default;
    }

    /* Tab Content */
    .tab-content {
      display: none;
      max-width: 720px;
      margin: 40px auto 80px;
      padding: 20px;
      background: rgba(24, 27, 31, 0.85);
      border-radius: 12px;
      box-shadow: 0 0 16px #58a6ffaa;
    }
    .tab-content.active {
      display: block;
    }

    .download-section h2 {
      margin-top: 0;
      color: #58a6ff;
      user-select: none;
    }
    .download-section p {
      color: #8b949e;
      margin-bottom: 24px;
      user-select: none;
    }
    .download-button {
      display: inline-block;
      background: #58a6ff;
      color: #0d1117;
      font-weight: 700;
      text-decoration: none;
      padding: 14px 36px;
      border-radius: 8px;
      font-size: 1.1rem;
      transition: background-color 0.3s ease;
      user-select: none;
    }
    .download-button:hover {
      background: #1f6feb;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 40px 20px;
      color: #484f58;
      border-top: 1px solid #30363d;
      font-size: 0.9rem;
      user-select: none;
    }

    /* Responsive */
    @media (max-width: 480px) {
      .hero h1 {
        font-size: 2.4rem;
      }
      nav a {
        margin-left: 12px;
        font-size: 0.9rem;
      }
      .tabs {
        gap: 10px;
        flex-wrap: wrap;
      }
      .tab-button {
        padding: 10px 14px;
        font-size: 0.9rem;
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
  <h1>Download Dream X Eceor</h1>
  <p>The most advanced Roblox utility tool — pick your download below.</p>
</section>

<div class="tabs" role="tablist" aria-label="Download Options">
  <button class="tab-button active" role="tab" aria-selected="true" aria-controls="direct" id="tab-direct">Direct Download</button>
  <button class="tab-button" role="tab" aria-selected="false" aria-controls="mirror" id="tab-mirror">Mirror Download</button>
  <button class="tab-button" role="tab" aria-selected="false" aria-controls="github" id="tab-github">GitHub Source</button>
</div>

<div id="direct" class="tab-content active" role="tabpanel" aria-labelledby="tab-direct">
  <div class="download-section">
    <h2>Direct Download</h2>
    <p>Fastest way to get Dream X Eceor on your system. One click setup.</p>
    <a href="#" class="download-button" target="_blank" rel="noopener">Download Now</a>
  </div>
</div>

<div id="mirror" class="tab-content" role="tabpanel" aria-labelledby="tab-mirror">
  <div class="download-section">
    <h2>Mirror Download</h2>
    <p>Use this option if the primary link is slow or blocked in your region.</p>
    <a href="#" class="download-button" target="_blank" rel="noopener">Download from Mirror</a>
  </div>
</div>

<div id="github" class="tab-content" role="tabpanel" aria-labelledby="tab-github">
  <div class="download-section">
    <h2>GitHub Repository</h2>
    <p>Explore the source code or contribute on GitHub.</p>
    <a href="https://github.com/" target="_blank" rel="noopener" class="download-button">View on GitHub</a>
  </div>
</div>

<footer>
  &copy; 2025 Dream X Eceor. Not affiliated with Roblox Corporation.
</footer>

<script>
  const tabs = document.querySelectorAll('.tab-button');
  const panels = document.querySelectorAll('.tab-content');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      // Deactivate all tabs & panels
      tabs.forEach(t => {
        t.classList.remove('active');
        t.setAttribute('aria-selected', 'false');
      });
      panels.forEach(panel => panel.classList.remove('active'));

      // Activate clicked tab & corresponding panel
      tab.classList.add('active');
      tab.setAttribute('aria-selected', 'true');
      const panelId = tab.getAttribute('aria-controls');
      document.getElementById(panelId).classList.add('active');
    });
  });
</script>

</body>
</html>
