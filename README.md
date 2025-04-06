<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GLORY Stack</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: "Segoe UI", sans-serif;
    }

    body {
      margin: 0;
      padding: 2rem;
      background: #e0e5ec;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }

    .section {
      background: #e0e5ec;
      border-radius: 20px;
      box-shadow: 8px 8px 16px #b8b9be, -8px -8px 16px #ffffff;
      padding: 2rem;
      margin: 1rem 0;
      width: 90%;
      max-width: 900px;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .badge {
      padding: 0.8rem 1.2rem;
      border-radius: 12px;
      font-size: 1rem;
      font-weight: 600;
      color: white;
      background: #4e4e4e;
      box-shadow: inset 2px 2px 6px rgba(255,255,255,0.2), inset -2px -2px 6px rgba(0,0,0,0.2);
      transition: transform 0.2s ease;
    }

    .badge:hover {
      transform: scale(1.05);
    }

    .socials {
      display: flex;
      gap: 1.5rem;
      justify-content: center;
      margin-top: 1.5rem;
    }

    .socials a {
      text-decoration: none;
    }

    .social-btn {
      padding: 0.9rem 1.5rem;
      border-radius: 14px;
      font-weight: bold;
      font-size: 1rem;
      background: #e0e5ec;
      color: #333;
      box-shadow: 6px 6px 12px #b8b9be, -6px -6px 12px #ffffff;
      transition: all 0.2s ease;
    }

    .social-btn:hover {
      transform: scale(1.07);
      background: #d2d7dd;
    }

    @media (max-width: 600px) {
      .badge {
        font-size: 0.9rem;
      }
      .social-btn {
        padding: 0.7rem 1.2rem;
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>
  <h1>🚀 My Tech Stack</h1>

  <div class="section">
    <h2>🧠 Languages</h2>
    <div class="badges">
      <div class="badge" style="background:#3776AB;">Python</div>
      <div class="badge" style="background:#0175C2;">Dart</div>
      <div class="badge" style="background:#00ADD8;">Go</div>
    </div>
  </div>

  <div class="section">
    <h2>🎨 UI/UX</h2>
    <div class="badges">
      <div class="badge">UI/UX</div>
    </div>
  </div>

  <div class="section">
    <h2>🧱 Framework</h2>
    <div class="badges">
      <div class="badge" style="background:#02569B;">Flutter</div>
    </div>
  </div>

  <div class="section">
    <h2>🗄️ Databases</h2>
    <div class="badges">
      <div class="badge" style="background:#4479A1;">MySQL</div>
      <div class="badge" style="background:#336791;">PostgreSQL</div>
    </div>
  </div>

  <div class="section">
    <h2>⚙️ DevOps & CI/CD</h2>
    <div class="badges">
      <div class="badge" style="background:#FCC624; color:black;">Linux</div>
      <div class="badge" style="background:#4EAA25;">Bash</div>
      <div class="badge" style="background:#2496ED;">Docker</div>
      <div class="badge" style="background:#FC6D26;">GitLab CI</div>
      <div class="badge" style="background:#2088FF;">GitHub Actions</div>
      <div class="badge" style="background:#1563FF;">Vagrant</div>
      <div class="badge" style="background:#000000;">Packer</div>
      <div class="badge" style="background:#EE0000;">Ansible</div>
    </div>
  </div>

  <div class="section">
    <h2>📈 Monitoring</h2>
    <div class="badges">
      <div class="badge" style="background:#E6522C;">Prometheus</div>
    </div>
  </div>

  <div class="section">
    <h2>📬 Contact Me</h2>
    <div class="socials">
      <a href="https://t.me/your_username" target="_blank" class="social-btn">Telegram</a>
      <a href="mailto:your@email.com" target="_blank" class="social-btn">Email</a>
      <a href="https://linkedin.com/in/your_profile" target="_blank" class="social-btn">LinkedIn</a>
    </div>
  </div>
</body>
</html>
