# Roblox
Trying 
<div class="navbar">
  <div class="logo">GameWorld</div>
  <div class="nav-links">
    <span>Home</span>
    <span>Games</span>
    <span>Avatar</span>
  </div>
  <button class="login-btn">Login</button>
</div>

<div class="hero">
  <div>
    <h1>Welcome to GameWorld</h1>
    <p>Play amazing games and explore new worlds.</p>
    <button class="play-btn">Explore Games</button>
  </div>
</div>

<h2>Popular Games</h2>

<div class="games">
  <div class="game-card">
    <div class="game-image">🎮</div>
    <h3>Murder Mystery</h3>
    <p>Play with your friends!</p>
    <button>Play</button>
  </div>

  <div class="game-card">
    <div class="game-image">⚔️</div>
    <h3>Battle Arena</h3>
    <p>Fight and become the champion.</p>
    <button>Play</button>
  </div>

  <div class="game-card">
    <div class="game-image">🏝️</div>
    <h3>Island Adventure</h3>
    <p>Explore a mysterious island.</p>
    <button>Play</button>
  </div>
</div>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

body {
  background: #f2f2f2;
  color: #222;
}

.navbar {
  height: 60px;
  background: #ffffff;
  display: flex;
  align-items: center;
  padding: 0 20px;
  gap: 30px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.logo {
  font-size: 22px;
  font-weight: bold;
}

.nav-links {
  display: flex;
  gap: 20px;
  flex: 1;
}

.nav-links span {
  cursor: pointer;
}

.login-btn,
.play-btn,
.game-card button {
  border: none;
  background: #222;
  color: white;
  padding: 10px 18px;
  border-radius: 6px;
  cursor: pointer;
}

.hero {
  margin: 20px;
  padding: 60px 30px;
  border-radius: 12px;
  background: linear-gradient(135deg, #444, #111);
  color: white;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 10px;
}

.hero p {
  margin-bottom: 20px;
}

.play-btn {
  background: white;
  color: #111;
}

h2 {
  margin: 25px 20px 15px;
}

.games {
  display: flex;
  gap: 20px;
  padding: 0 20px 30px;
  flex-wrap: wrap;
}

.game-card {
  background: white;
  width: 250px;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

.game-image {
  height: 130px;
  background: #ddd;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 50px;
  margin-bottom: 12px;
}

.game-card h3 {
  margin-bottom: 7px;
}

.game-card p {
  color: #666;
  margin-bottom: 15px;
}
