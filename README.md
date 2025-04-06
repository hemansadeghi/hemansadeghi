<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GLORY Dev Stack</title>
  <style>
    body {
      background-color: #1e1f26;
      font-family: 'Segoe UI', sans-serif;
      color: #eaeaea;
      padding: 2rem;
    }

    h2 {
      font-size: 1.6rem;
      margin-top: 2rem;
    }

    .badge-container {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 1rem;
    }

    .badge {
      display: flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.6rem 1.2rem;
      border-radius: 2rem;
      background: #1e1f26;
      box-shadow: 6px 6px 12px #141518,
                  -6px -6px 12px #2a2b34;
      font-weight: 600;
      font-size: 1rem;
      transition: all 0.2s ease;
      border: none;
      cursor: default;
    }

    .badge:hover {
      box-shadow: inset 4px 4px 8px #141518,
                  inset -4px -4px 8px #2a2b34;
    }

    .telegram   { background-color: #2aabee; color: white; }
    .gmail      { background-color: #dd4b39; color: white; }
    .linkedin   { background-color: #0077b5; color: white; }

    .python     { background-color: #306998; color: white; }
    .dart       { background-color: #0175c2; color: white; }
    .go         { background-color: #00add8; color: white; }

    .flutter    { background-color: #02569b; color: white; }
    .mysql      { background-color: #00758f; color: white; }
    .postgres   { background-color: #336791; color: white; }

    .linux      { background-color: #fdd835; color: black; }
    .bash       { background-color: #4caf50; color: white; }
    .docker     { background-color: #0db7ed; color: white; }
    .gitlab     { background-color: #fc6d26; color: white; }
    .github     { background-color: #24292e; color: white; }
    .vagrant    { background-color: #1563ff; color: white; }
    .packer     { background-color: #333; color: white; }
    .ansible    { background-color: #ee0000; color: white; }

    .prometheus { background-color: #e6522c; color: white; }
  </style>
</head>
<body>

  <h2>Languages:</h2>
  <div class="badge-container">
    <div class="badge python">🐍 Python</div>
    <div class="badge dart">🎯 Dart</div>
    <div class="badge go">💨 Go</div>
  </div>

  <h2>UI/UX:</h2>
  <div class="badge-container">
    <div class="badge" style="background: #111;">🖌️ UI/UX</div>
  </div>

  <h2>Frameworks:</h2>
  <div class="badge-container">
    <div class="badge flutter">🧩 Flutter</div>
  </div>

  <h2>Databases:</h2>
  <div class="badge-container">
    <div class="badge mysql">🛢️ MySQL</div>
    <div class="badge postgres">🗃️ PostgreSQL</div>
  </div>

  <h2>DevOps & CI/CD:</h2>
  <div class="badge-container">
    <div class="badge linux">🐧 Linux</div>
    <div class="badge bash">💻 Bash</div>
    <div class="badge docker">🐳 Docker</div>
    <div class="badge gitlab">🦊 GitLab CI</div>
    <div class="badge github">📦 GitHub Actions</div>
    <div class="badge vagrant">📦 Vagrant</div>
    <div class="badge packer">📦 Packer</div>
    <div class="badge ansible">🛠️ Ansible</div>
  </div>

  <h2>Monitoring:</h2>
  <div class="badge-container">
    <div class="badge prometheus">📊 Prometheus</div>
  </div>

  <h2>Contact Options 📞</h2>
  <div class="badge-container">
    <div class="badge telegram">📨 Telegram</div>
    <div class="badge gmail">📧 Gmail</div>
    <div class="badge linkedin">💼 LinkedIn</div>
  </div>

</body>
</html>
