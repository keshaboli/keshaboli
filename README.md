<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Keshab Oli | Software Engineer</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
      color: #ffffff;
      overflow-x: hidden;
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
      text-align: center;
    }
    h1 {
      font-size: 3rem;
      color: #00ffff;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from {
        text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff;
      }
      to {
        text-shadow: 0 0 20px #00ffee, 0 0 30px #00ffee, 0 0 40px #00ffee;
      }
    }
    .typewriter {
      overflow: hidden;
      border-right: .15em solid #00ffff;
      white-space: nowrap;
      margin: 0 auto;
      letter-spacing: .15em;
      animation: typing 3s steps(40, end), blink-caret .75s step-end infinite;
      max-width: 100%;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink-caret {
      from, to { border-color: transparent }
      50% { border-color: #00ffff; }
    }
    .tech-icons img {
      margin: 0.5rem;
      width: 40px;
      filter: drop-shadow(0 0 5px #00ffff);
    }
    .socials a {
      margin: 0.5rem;
      text-decoration: none;
      color: #00ffff;
      font-size: 1.2rem;
      transition: color 0.3s ease-in-out;
    }
    .socials a:hover {
      color: #ffffff;
    }
    .footer {
      margin-top: 2rem;
      font-size: 0.9rem;
      opacity: 0.7;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Keshab Oli</h1>
    <div class="typewriter">Full-Stack Developer | React | Next.js | DRF | FastAPI | Spring Boot</div>
    <p>Crafting scalable and intelligent software systems 🚀</p>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
    </div>
    <div class="socials">
      <a href="https://keshaboli.com.np" target="_blank">🌐 Website</a>
      <a href="https://www.linkedin.com/in/keshab-oli-0a7441313/" target="_blank">🔗 LinkedIn</a>
      <a href="https://x.com/KrishBean" target="_blank">🐦 Twitter</a>
      <a href="https://www.instagram.com/krishbean.py/" target="_blank">📸 Instagram</a>
      <a href="https://www.youtube.com/@krishbeanAI" target="_blank">▶ YouTube</a>
      <a href="https://tiktok.com/@KrishBean" target="_blank">🎵 TikTok</a>
    </div>
    <div class="footer">
      <p>📍 Kathmandu, Nepal | 📧 hello@keshaboli.com.np | 📱 +977 9858091405</p>
    </div>
  </div>
</body>
</html>
