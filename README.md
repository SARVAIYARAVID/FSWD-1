# FSWD-1
ASSIGNMENT-1 QUESTION-2

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Spotify - Web Player: Music for everyone</title>
    <link rel="stylesheet" href="SPOTIFY CLONE.CSS" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
      integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="icon" href="logo.png" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div class="main">
      <div class="sidebar">
        <div class="nav">
          <div class="nav-option" style="opacity: 1">
            <i class="fa-solid fa-house"></i>
            <a href="#">Home</a>
          </div>
          <div class="nav-option">
            <i class="fa-solid fa-magnifying-glass"></i>
            <a href="#">Search</a>
          </div>
        </div>
        <div class="library">
          <div class="options">
            <div class="library-option nav-option">
              <img src="library_icon.png" />
              <a href="#">Your Library</a>
            </div>
            <div class="icons">
              <i class="fa-solid fa-plus"></i>

              <i class="fa-solid fa-arrow-right"></i>
            </div>
          </div>
          <div class="library-boxes">
            <div class="box">
              <p class="box-p1">Create your first playlist</p>
              <p class="box-p2">It's easy,we'll help you</p>
              <button class="badge">Create playlist</button>
            </div>
            <div class="box">
              <p class="box-p1">Let's find some podcasts to follow</p>
              <p class="box-p2">We'll keep you updated on new episodes</p>
              <button class="badge">Browse podcasts</button>
            </div>
          </div>
        </div>
      </div>
      <div class="main_content">
        <!-- main_content -->
        <div class="sticky-nav">
          <div class="sticky-nav-icons">
            <img src="backward_icon.png" />
            <img src="forward_icon.png" class="hide" />
          </div>
          <div class="sticky-nav-option">
            <button class="badge nav-item hide">Explore premium</button>

            <button class="badge nav-item dark-badge">
              <i class="fa-solid fa-download" style="margin-right: 5px"></i
              >Install App
            </button>
            <i class="fa-solid fa-user nav-item"></i>
          </div>
        </div>
        <div class="cards">
          <h2>Recently played</h2>
          <div class="cards-container">
            <div class="card">
              <img src="card1img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>
          </div>
          <h2>Trending now near you</h2>
          <div class="cards-container">
            <div class="card">
              <img src="card2img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>

            <div class="card">
              <img src="card3img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>

            <div class="card">
              <img src="card4img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>

            <div class="card">
              <img src="card3img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>

            <div class="card">
              <img src="card4img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>
          </div>
          <h2>Feature Charts</h2>
          <div class="cards-container">
            <div class="card">
              <img src="card5img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>
            <div class="card">
              <img src="card6img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>
            <div class="card">
              <img src="card1img.jpeg" class="card-image" />

              <p class="card-title">Top 50-Global</p>
              <p class="card-information">
                Your daily update of the most played...
              </p>
            </div>
          </div>
        </div>
        <div class="footer">
          <div class="line"></div>
        </div>
      </div>
      <div class="music_player">
        <!-- music_player -->
         <div class="album">
          <img src="album_picture.jpeg" class="album-picture">
          <div class="album-info">
            <p class="title" style="opacity: 1;">Daylight</p>
            <p class="artist-name">David Kushner</p>


          </div>

         </div>
         <div class="player">
          <div class="player-controls">
            <img src="player_icon1.png" class="player-controls-icon">
            <img src="player_icon2.png" class="player-controls-icon">
            <img src="player_icon3.png" class="player-controls-icon" style="opacity: 1; height: 2rem;">
            <img src="player_icon4.png" class="player-controls-icon">
            <img src="player_icon5.png" class="player-controls-icon">
          </div>
          <div class="playback-bar">
            <span class="current-time">00:00</span>
            <input type="range" class="progress-bar" min="0" max="100" step="1">
            <span class="total-time">3:33</span>
          </div>
         </div>
         <div class="controls">
          <img src="controls_icon1.png" class="controls-icon" style="height: 2rem;">
          <img src="controls_icon2.png" class="controls-icon">
          <img src="controls_icon3.png" class="controls-icon">
          <img src="controls_icon4.png" class="controls-icon">
          <img src="controls_icon5.png" class="controls-icon" style="height: 2rem;">
          <input type="range" class="controls" min="0" max="100" step="1">
         </div>
      </div>
    </div>
  </body>
</html>
