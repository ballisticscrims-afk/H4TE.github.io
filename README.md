# H4TE.github.io
H4TE Ballistics 
index.html
style.css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>H4TE</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <img src="logo.png" class="logo" alt="Clan Logo">
  <h1>H4TEEU</h1>
</header>

<section class="about">
  <h2>About Us</h2>
  <p>
 H4TE GAMING is a competitive esports organization built on skill, discipline, and the relentless drive to win. We bring together elite players, creators, and competitors who thrive under pressure and dominate on the biggest stages. From ranked ladders to tournaments, H4TE GAMING represents passion, precision, and pure competition.
  </p>
</section>

<section class="socials">
  <h2>Socials</h2>
  <a href="https://discord.gg/hateeu" target="_blank">Discord</a>
  <a href="https://youtube.com/@H4TEEU" target="_blank">YouTube</a>
  <a href="https://www.tiktok.com/@h4teballistic" target="_blank">TikTok</a>
</section>

<section class="videos">
  <h2>Videos</h2>
  <iframe src="https://www.youtube.com/watch?v=oR283snO-sg" allowfullscreen></iframe>
</section>

<section class="roster">
  <h2>Player Roster</h2>
  <div class="player">Player1 – IGL</div>
  <div class="player">Player2 – Fragger</div>
  <div class="player">Player3 – Support</div>
</section>

<footer>
  <p>© 2026 Your Clan Name</p>
</footer>

</body>
</html>

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: url("background.jpg") no-repeat center center fixed;
  background-size: cover;
  color: white;
  text-align: center;
}

header {
  background: rgba(0,0,0,0.7);
  padding: 20px;
}

.logo {
  width: 120px;
}

section {
  background: rgba(0,0,0,0.6);
  margin: 20px;
  padding: 20px;
  border-radius: 10px;
}

.socials a {
  margin: 10px;
  color: #00ffcc;
  text-decoration: none;
  font-size: 18px;
}

iframe {
  width: 80%;
  height: 315px;
}

.player {
  margin: 10px;
  font-weight: bold;
}

