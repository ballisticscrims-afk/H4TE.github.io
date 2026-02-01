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
  <h1>Your Clan Name</h1>
</header>

<section class="about">
  <h2>About Us</h2>
  <p>
    We are a competitive gaming team focused on teamwork,
    skill, and dominating the leaderboard.
  </p>
</section>

<section class="socials">
  <h2>Socials</h2>
  <a href="https://discord.gg/YOURLINK" target="_blank">Discord</a>
  <a href="https://twitter.com/YOURNAME" target="_blank">Twitter/X</a>
  <a href="https://youtube.com/@YOURCHANNEL" target="_blank">YouTube</a>
</section>

<section class="videos">
  <h2>Videos</h2>
  <iframe src="https://www.youtube.com/embed/VIDEOID" allowfullscreen></iframe>
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

