# maskuplinktr
maskup link
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Maskup Link Sayfası</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #121212;
    color: #f0f0f0;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    min-height: 100vh;
  }
  .container {
    max-width: 400px;
    width: 90%;
    text-align: center;
    padding: 20px;
  }
  .profile-pic {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 15px auto;
    border: 3px solid #f0f0f0;
    background: #222;
  }
  h1 {
    margin-bottom: 5px;
  }
  p.bio {
    font-size: 1rem;
    margin-bottom: 25px;
    color: #ccc;
  }
  .links {
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  .link-btn {
    background: #1DB954;
    color: #121212;
    font-weight: 700;
    padding: 14px 0;
    border-radius: 30px;
    text-decoration: none;
    font-size: 1.1rem;
    transition: background 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }
  .link-btn:hover {
    background: #17a54a;
  }
  .icon {
    width: 24px;
    height: 24px;
    fill: #121212;
  }
  @media (min-width: 600px) {
    body {
      background: #000;
    }
    .container {
      max-width: 600px;
      width: 90%;
      padding: 40px;
      background: #1a1a1a;
      border-radius: 12px;
      box-shadow: 0 0 15px #0f0;
    }
    .links {
      flex-direction: row;
      justify-content: center;
    }
    .link-btn {
      flex: 1;
      max-width: 180px;
      font-size: 1.2rem;
      padding: 18px 0;
    }
  }
</style>
</head>
<body>
  <div class="container">
    <img class="profile-pic" src="https://i.imgur.com/6VBx3io.png" alt="Maskup Logo" />
    <h1>Maskup</h1>
    <p class="bio">Müzik ve içerik yolculuğuma hoş geldin! 🎧</p>

    <div class="links">
      <a href="https://www.instagram.com/maskup.mp3?igsh=dnlrazF4Z2FuZTZj&utm_source=qr" target="_blank" class="link-btn" aria-label="Instagram">
        <svg class="icon" viewBox="0 0 24 24"><path d="M7.75 2h8.5A5.75 5.75 0 0122 7.75v8.5A5.75 5.75 0 0116.25 22h-8.5A5.75 5.75 0 012 16.25v-8.5A5.75 5.75 0 017.75 2zm6.25 2.5a1.25 1.25 0 100 2.5 1.25 1.25 0 000-2.5zm-4.25 1.25a4.25 4.25 0 100 8.5 4.25 4.25 0 000-8.5zM12 9a3 3 0 110 6 3 3 0 010-6z"/></svg>
        Instagram
      </a>
      <a href="https://www.tiktok.com/@maskup.mp3?_t=ZM-8xhsIAwFt38&_r=1" target="_blank" class="link-btn" aria-label="TikTok" style="background:#000000; color:#fff;">
        <svg class="icon" viewBox="0 0 24 24" fill="#fff"><path d="M12 2.04v15.22a3.75 3.75 0 11-3.75-3.75v-1.04h-3.5V6.5h3.5v-.25a6 6 0 005.25 5.95v2.59a6.75 6.75 0 11-6.75-6.75z"/></svg>
        TikTok
      </a>
      <a href="https://youtube.com/@maskup6441?si=_jIZSatIW31L5Lg9" target="_blank" class="link-btn" aria-label="YouTube" style="background:#FF0000; color:#fff;">
        <svg class="icon" viewBox="0 0 24 24" fill="#fff"><path d="M10 15l5.19-3L10 9v6zM22 6a2 2 0 00-1.41-1.41C19.45 4 12 4 12 4s-7.45 0-8.59.59A2 2 0 002 6v12a2 2 0 001.41 1.41C4.55 20 12 20 12 20s7.45 0 8.59-.59A2 2 0 0022 18V6z"/></svg>
        YouTube
      </a>
    </div>
  </div>
</body>
</html>
