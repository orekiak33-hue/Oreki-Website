<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NextLevel Gaming</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      color: #e0e0e0;
      background: radial-gradient(circle at 20% 20%, #111 0%, #000 100%);
      overflow-x: hidden;
    }
    header {
      background: rgba(15, 15, 15, 0.9);
      backdrop-filter: blur(10px);
      position: fixed; top: 0; left: 0; width: 100%;
      display: flex; justify-content: space-between; align-items: center;
      padding: 20px 40px; z-index: 10;
    }
    header h1 {
      font-family: 'Orbitron', sans-serif;
      color: #00ffe0;
      font-size: 24px;
    }
    nav a {
      color: #e0e0e0;
      margin: 0 15px;
      text-decoration: none;
      text-transform: uppercase;
      font-size: 14px;
    }
    nav a:hover {
      color: #00ffe0;
    }
    .hero {
      height: 100vh;
      background: linear-gradient(180deg, rgba(0,0,0,0.8), rgba(10,10,10,1)), url('https://images.unsplash.com/photo-1612023887497-28ad01f043d9?auto=format&fit=crop&w=1200&q=80') center/cover no-repeat;
      display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center;
      color: #fff; padding: 0 20px;
    }
    .hero h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      text-shadow: 0 0 15px #00ffe0;
    }
    .hero p {
      color: #ccc; font-size: 1.2rem; margin: 20px 0;
    }
    .hero button {
      background: #00ffe0; color: #000; border: none;
      padding: 12px 28px; border-radius: 30px;
      font-weight: bold; cursor: pointer; transition: 0.3s;
    }
    .hero button:hover { background: #00c2a8; }

    .section { padding: 100px 20px; text-align: center; }
    .section h3 {
      font-family: 'Orbitron', sans-serif;
      color: #00ffe0; font-size: 2rem; margin-bottom: 40px;
    }
    .cards { display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; }
    .card {
      background: rgba(30,30,30,0.7);
      border: 1px solid #222; border-radius: 15px;
      width: 300px; padding: 25px; transition: 0.3s;
    }
    .card:hover { transform: scale(1.05); border-color: #00ffe0; }
    .card img { width: 100%; border-radius: 10px; }
    .card h4 { margin-top: 15px; color: #00ffe0; }
    .card p { color: #aaa; font-size: 0.9rem; margin-top: 10px; }

    footer {
      background: #0a0a0a;
      text-align: center; padding: 30px 10px;
      color: #666; font-size: 0.9rem;
      border-top: 1px solid #111;
    }
  </style>
</head>
<body>
  <header>
    <h1>NextLevel Gaming</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#games">Games</a>
      <a href="#community">Community</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Play. Compete. Conquer.</h2>
    <p>Your destination for the latest in esports and gaming culture.</p>
    <button>Join the Arena</button>
  </section>

  <section class="section" id="games">
    <h3>Top Trending Games</h3>
    <div class="cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1580128637470-fdbd3a958bcd?auto=format&fit=crop&w=1000&q=80" alt="Game1">
        <h4>Valorant</h4>
        <p>Experience next-level tactical gameplay with stunning visuals and pro-level strategy.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1606112219348-204d7d8b94ee?auto=format&fit=crop&w=1000&q=80" alt="Game2">
        <h4>CyberStrike</h4>
        <p>Futuristic arena battles set in neon-lit megacities. Get ready for chaos and glory!</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1610077779217-117a55afb43a?auto=format&fit=crop&w=1000&q=80" alt="Game3">
        <h4>Legends Arena</h4>
        <p>RPG meets battle royale in an intense showdown for ultimate dominance.</p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 NextLevel Gaming — Designed with AI & passion for gamers.
  </footer>
</body>
</html>
