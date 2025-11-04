index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Retro Bowl & Classic Games</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Retro Bowl & Classic Games</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Top Games</a>
      <a href="#">New</a>
      <a href="#">About</a>
    </nav>
  </header>

  <main>
    <section class="featured">
      <h2>Featured Game: Retro Bowl</h2>
      <div class="game-frame">
        <!-- This iframe embeds Retro Bowl (use a public playable link) -->
        <iframe 
          src="https://retro-bowl.io/" 
          title="Retro Bowl"
          frameborder="0"
          allowfullscreen>
        </iframe>
      </div>
    </section>

    <section class="game-grid">
      <h2>More Retro Classics</h2>
      <div class="grid">
        <div class="game">
          <img src="https://placehold.co/200x120" alt="Tetris">
          <h3>Tetris</h3>
        </div>
        <div class="game">
          <img src="https://placehold.co/200x120" alt="Pac-Man">
          <h3>Pac-Man</h3>
        </div>
        <div class="game">
          <img src="https://placehold.co/200x120" alt="Space Invaders">
          <h3>Space Invaders</h3>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Retro Games Hub | Built for fun 🎮</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
