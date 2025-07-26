# Nila-gaming
My first public HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Free Fire Profile - Neko</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: url('https://i.ibb.co/8dtkcdf/bg.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 30px;
      background-color: rgba(0, 0, 0, 0.7);
      border-radius: 12px;
      margin-top: 50px;
    }

    .profile-header {
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .avatar {
      width: 100px;
      border-radius: 12px;
    }

    .profile-info h2 {
      margin: 0;
      font-size: 24px;
    }

    .profile-info p {
      margin: 5px 0;
    }

    .stats {
      margin-top: 20px;
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .stat-box {
      flex: 1 1 30%;
      background: #222;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }

    .stat-box h3 {
      margin: 0;
      color: #ffcc00;
    }

    .footer {
      margin-top: 30px;
      font-size: 14px;
      text-align: center;
    }

    .footer a {
      color: #ff0050;
      text-decoration: none;
      font-weight: bold;
    }

    .footer img {
      height: 16px;
      vertical-align: middle;
      margin-right: 5px;
    }

    @media (max-width: 600px) {
      .profile-header {
        flex-direction: column;
        align-items: flex-start;
      }

      .avatar {
        width: 80px;
      }

      .stat-box {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile-header">
      <img class="avatar" src="https://i.ibb.co/jZg3zvC/avatar.jpg" alt="Avatar">
      <div class="profile-info">
        <h2>Neko (猫)</h2>
        <p>🌍 Country: Bangladesh</p>
        <p>UID: 1245705621</p>
        <p>Level: 76</p>
        <p>👍 Likes: 23,212</p>
      </div>
    </div>

    <div class="stats">
      <div class="stat-box">
        <h3>RANKED</h3>
        <p>Season 46</p>
        <p>Matches: 5313</p>
      </div>
      <div class="stat-box">
        <h3>Heroic Emblem</h3>
        <p>231 🏆</p>
      </div>
      <div class="stat-box">
        <h3>Rusher</h3>
        <p>Level 76</p>
      </div>
    </div>

    <div class="footer">
      <a href="https://www.tiktok.com/@tn_nila_gaming" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/TikTok_logo.svg" alt="TikTok">
        TikTok: @tn_nila_gaming
      </a>
    </div>
  </div>
</body>
</html>![Screenshot_2025-07-26-11-15-06-849_com dts freefireth](https://github.com/user-attachments/assets/5229dd8a-bf65-475a-89df-91e0087c19d5)
