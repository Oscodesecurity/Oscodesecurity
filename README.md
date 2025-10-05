<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oscodesecurity Profile</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
      color: #ffffff;
      line-height: 1.6;
      overflow-x: hidden;
    }

    h1, p {
      margin: 0;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    .header-img {
      width: 100%;
      max-width: 600px;
      margin: 0 auto;
      display: block;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 114, 255, 0.3);
    }

    .title {
      font-size: 2.5em;
      margin: 20px 0;
      background: linear-gradient(90deg, #00c6ff, #0072ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: fadeIn 1.5s ease-in-out;
    }

    .subtitle {
      font-size: 1.2em;
      color: #b0b0b0;
      margin-bottom: 30px;
      animation: slideUp 1s ease-in-out;
    }

    .connect-section {
      margin: 30px 0;
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .connect-section a {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .connect-section a:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0, 114, 255, 0.5);
    }

    .about-section {
      background: rgba(255, 255, 255, 0.05);
      padding: 20px;
      border-radius: 10px;
      margin: 30px 0;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      animation: fadeIn 2s ease-in-out;
    }

    .about-section p {
      font-size: 1.1em;
      color: #d0d0d0;
      max-width: 700px;
      margin: 0 auto;
    }

    .skills-section {
      margin: 40px 0;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
      gap: 15px;
      justify-items: center;
      padding: 20px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
    }

    .skills-grid img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s ease, filter 0.3s ease;
    }

    .skills-grid img:hover {
      transform: scale(1.2);
      filter: drop-shadow(0 0 10px rgba(0, 114, 255, 0.7));
    }

    .support-section {
      margin: 30px 0;
    }

    .support-section a {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .support-section a:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(255, 165, 0, 0.5);
    }

    .footer-img {
      width: 100%;
      max-width: 600px;
      margin: 20px auto;
      display: block;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 114, 255, 0.3);
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    /* Responsive Design */
    @media (max-width: 600px) {
      .title {
        font-size: 1.8em;
      }

      .subtitle {
        font-size: 1em;
      }

      .connect-section {
        gap: 10px;
      }

      .skills-grid {
        grid-template-columns: repeat(auto-fit, minmax(50px, 1fr));
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <img class="header-img" src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=200&section=header&text=Oscodesecurity&fontSize=50&fontColor=fff&animation=twinkling" alt="Header" />

    <h1 class="title">Hello World, I'm <span>Oscodesecurity</span></h1>
    <p class="subtitle"><b>FullStack Developer</b> | <b>Bug Hunter</b> | <b>Pentester</b></p>

    <!-- Connect With Me -->
    <div class="connect-section">
      <a href="https://t.me/oscodesecurity" target="_blank">
        <img src="https://img.shields.io/badge/Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
      </a>
      <a href="https://wa.me/628892128871" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
      </a>
      <a href="https://tiktok.com/@oscodesecurity" target="_blank">
        <img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" />
      </a>
      <a href="https://discord.gg/sBNC74ZY" target="_blank">
        <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
      </a>
    </div>

    <!-- About Me -->
    <div class="about-section">
      <h2>About Me</h2>
      <p>
        Perkenalkan, saya Oscodesecurity, seorang pembelajar otodidak yang mulai menjelajahi teknologi sejak usia muda.
        Saya mulai belajar pemrograman bukan melalui sekolah, melainkan dari rasa ingin tahu yang tinggi, eksperimen, dan kegigihan untuk memahami cara kerja dunia digital.
      </p>
      <p>
        Saya menghabiskan sebagian besar waktu saya menjelajahi keamanan siber dan pemrograman. Saat ini, saya fokus menciptakan alat untuk bug hunter dan pentester, sekaligus terus mengasah kemampuan saya setiap hari.
      </p>
      <p>
        Saya percaya bahwa pengetahuan bukan tentang usia atau gelar, melainkan tentang kegigihan, konsistensi, dan hasrat untuk terus belajar.
      </p>
    </div>

    <!-- My Skills -->
    <div class="skills-section">
      <h2>My Skills</h2>
      <div class="skills-grid">
        <img src="https://skillicons.dev/icons?i=html" alt="HTML" />
        <img src="https://skillicons.dev/icons?i=css" alt="CSS" />
        <img src="https://skillicons.dev/icons?i=js" alt="JavaScript" />
        <img src="https://skillicons.dev/icons?i=python" alt="Python" />
        <img src="https://skillicons.dev/icons?i=cpp" alt="C++" />
        <img src="https://skillicons.dev/icons?i=php" alt="PHP" />
        <img src="https://skillicons.dev/icons?i=laravel" alt="Laravel" />
        <img src="https://skillicons.dev/icons?i=react" alt="React" />
        <img src="https://skillicons.dev/icons?i=java" alt="Java" />
        <img src="https://skillicons.dev/icons?i=bash" alt="Bash" />
        <img src="https://skillicons.dev/icons?i=kali" alt="Kali Linux" />
        <img src="https://skillicons.dev/icons?i=figma" alt="Figma" />
      </div>
    </div>

    <!-- Support Me -->
    <div class="support-section">
      <a href="https://ko-fi.com/oscodesecurity">
        <img src="https://img.shields.io/badge/☕-Buy%20Me%20a%20Coffee-orange?style=for-the-badge" alt="Buy Me a Coffee" />
      </a>
    </div>

    <!-- Footer -->
    <img class="footer-img" src="https://capsule-render.vercel.app/api?type=waving&color=0:0072ff,100:00c6ff&height=120&section=footer" alt="Footer" />
  </div>
</body>
</html>  </a>
  <a href="https://tiktok.com/@oscodesecurity" target="_blank">
    <img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" />
  </a>
  <a href="https://discord.gg/sBNC74ZY" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
</p>

---

### About Me
Perkenalkan, saya Oscodesecurity, seorang pembelajar otodidak yang mulai menjelajahi teknologi sejak usia muda.
Saya mulai belajar pemrograman bukan melalui sekolah, melainkan dari rasa ingin tahu yang tinggi, eksperimen, dan kegigihan untuk memahami cara kerja dunia digital.

Saya menghabiskan sebagian besar waktu saya menjelajahi keamanan siber dan pemrograman. Saat ini, saya fokus menciptakan alat untuk bug hunter dan pentester, sekaligus terus mengasah kemampuan saya setiap hari.

Saya percaya bahwa pengetahuan bukan tentang usia atau gelar, melainkan tentang kegigihan, konsistensi, dan hasrat untuk terus belajar.



---

### 👨‍💻 My Skills
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,cpp,php,laravel,react,java,bash,kali,figma" />
</p>

---

### Support Me
<p align="center">
  <a href="https://ko-fi.com/oscodesecurity">
    <img src="https://img.shields.io/badge/☕-Buy%20Me%20a%20Coffee-orange?style=for-the-badge" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0072ff,100:00c6ff&height=120&section=footer" />
</p>
