# amanplayzzyt <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AMANPLAYZZYT | Gaming World</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #000;
      color: #00ffff;
      overflow-x: hidden;
    }

    header {
      background: rgba(0, 0, 0, 0.8);
      padding: 20px 50px;
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #00ffff66;
      backdrop-filter: blur(6px);
      animation: slideDown 1s ease;
    }

    header h1 {
      color: #00ffff;
      font-size: 30px;
      text-shadow: 0 0 20px #00ffff;
      letter-spacing: 3px;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from { text-shadow: 0 0 10px #00ffff; }
      to { text-shadow: 0 0 25px #00ffff, 0 0 35px #00ccff; }
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 25px;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #00ffff;
      text-shadow: 0 0 10px #00ffff;
    }

    section {
      padding: 80px 50px;
      text-align: center;
      animation: fadeIn 1s ease forwards;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .home {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: radial-gradient(circle at center, #001a1a, #000);
      animation: fadeIn 2s ease;
    }

    .home h2 {
      font-size: 55px;
      color: #00ffff;
      text-shadow: 0 0 25px #00ffff;
      animation: neonPulse 3s infinite alternate;
    }

    @keyframes neonPulse {
      from { text-shadow: 0 0 15px #00ffff; }
      to { text-shadow: 0 0 35px #00ffff, 0 0 50px #00ccff; }
    }

    .home p {
      font-size: 20px;
      margin-top: 10px;
      color: #ccc;
      animation: fadeIn 2s ease;
    }

    .about, .gallery, .contact {
      background: #010a10;
      border-top: 1px solid #00ffff33;
      border-bottom: 1px solid #00ffff33;
    }

    .about p {
      max-width: 800px;
      margin: 20px auto;
      color: #bbb;
      font-size: 18px;
      line-height: 1.7;
      animation: fadeIn 2s ease;
    }

    .youtube a {
      display: inline-block;
      background: #00ffff;
      color: #000;
      padding: 15px 35px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
      transition: 0.4s;
      animation: fadeIn 2s ease;
    }

    .youtube a:hover {
      background: #00cccc;
      box-shadow: 0 0 20px #00ffff;
      transform: scale(1.1);
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 40px;
      padding: 0 30px;
      animation: fadeIn 2s ease;
    }

    .gallery-grid img {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 0 15px #00ffff55;
      transition: 0.4s;
    }

    .gallery-grid img:hover {
      transform: scale(1.08);
      box-shadow: 0 0 35px #00ffff;
    }

    footer {
      background: #000;
      padding: 30px 0;
      text-align: center;
      color: #00ffff;
      border-top: 1px solid #00ffff33;
      animation: fadeIn 2s ease;
    }

    .social a {
      color: #00ffff;
      margin: 0 15px;
      font-size: 22px;
      text-decoration: none;
      transition: 0.3s;
    }

    .social a:hover {
      color: #fff;
      text-shadow: 0 0 15px #00ffff;
    }

    @keyframes slideDown {
      from { transform: translateY(-60px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>AMANPLAYZZYT</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#youtube">YouTube</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="home">
    <h2>Welcome to AMANPLAYZZYT</h2>
    <p>Enter the neon world of BGMI battles, montages & gaming vibes ⚡</p>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Hey there! I’m <b>Aman</b> — a passionate gamer and content creator from India.  
      I create BGMI montages, short clips, and intense 1v1 TDM fights.  
      Join me on my journey to become one of the best BGMI players in the community!  
      <br><br>
      🎮 <b>BGMI ID:</b> 55617168823
    </p>
  </section>

  <section id="youtube" class="youtube">
    <h2>Watch My Channel</h2>
    <a href="https://www.youtube.com/@Amanplayzzyt-t7z" target="_blank">🎮 Visit My Channel</a>
  </section>

  <section id="gallery" class="gallery">
    <h2>Gaming Gallery</h2>
    <div class="gallery-grid">
      <img src="https://via.placeholder.com/400x250?text=BGMI+1v1" alt="BGMI Fight" />
      <img src="https://via.placeholder.com/400x250?text=Victory+Moment" alt="Victory" />
      <img src="https://via.placeholder.com/400x250?text=Montage+Clip" alt="Montage" />
      <img src="https://via.placeholder.com/400x250?text=Squad+Win" alt="Squad Win" />
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Let’s connect and grow together!</p>
    <div class="social">
      <a href="https://www.youtube.com/@Amanplayzzyt-t7z" target="_blank">YouTube</a>
      <a href="#">Instagram</a>
      <a href="#">Discord</a>
    </div>
  </section>

  <footer>
    <p>© 2025 AMANPLAYZZYT | Designed with 💙 by Aman</p>
  </footer>
</body>
</html>
