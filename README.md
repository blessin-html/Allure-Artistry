<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Welcome | Allure Artistry</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Times New Roman', Times, serif;
      background: url('https://images.unsplash.com/photo-1614891100665-3c7d68bc3b80') no-repeat center center/cover;
      height: 100vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
    }
    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 0;
    }
    .content {
      z-index: 1;
      position: relative;
      padding: 30px;
    }
    h1 {
      font-size: 3.5em;
      margin-bottom: 10px;
      color: #ffe4f0;
    }
    p {
      font-size: 1.3em;
      margin-bottom: 30px;
    }
    a.button {
      padding: 15px 30px;
      background-color: #ff69b4;
      color: white;
      text-decoration: none;
      font-size: 1.2em;
      border-radius: 8px;
    }
    a.button:hover {
      background-color: #c71585;
    }
  </style>
</head>
<body>

  <div class="overlay"></div>

  <div class="content">
    <h1>Allure Artistry</h1>
    <p>Unleash your inner beauty. Glam that speaks volumes.</p>
    <a href="index.html" class="button">Enter Website</a>
  </div>

</body>
</html>
