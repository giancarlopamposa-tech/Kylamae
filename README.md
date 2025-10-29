<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For My Love 💖</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: "Poppins", sans-serif; }
    body {
      background: linear-gradient(135deg, #ffe6f0, #fff0f6, #fff8e7);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: 40px 20px;
      animation: fadeIn 1.5s ease;
    }
    @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 12px;
      text-align: center;
      color: #d63384;
    }
    p.subtitle {
      font-size: 1rem;
      color: #777;
      text-align: center;
      margin-bottom: 30px;
    }
    .note {
      background: white;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.1);
      max-width: 600px;
      text-align: center;
      margin-bottom: 40px;
    }
    .note p {
      line-height: 1.6;
      color: #444;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
      max-width: 900px;
      width: 100%;
    }
    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 20px rgba(0,0,0,0.12);
    }
    footer {
      margin-top: 30px;
      color: #888;
      font-size: 0.9rem;
      text-align: center;
    }
    audio {
      margin-top: 25px;
    }
  </style>
</head>
<body>
  <h1>For My Love 💖</h1>
  <p class="subtitle">A small gift made with all my heart</p>

  <div class="note">
    <p>
      You are my favorite person — my sunshine in every morning and the peace in every night.
      This small page is a reminder that you are loved, every single day.
    </p>
  </div>

  <div class="gallery">
    <img src="https://i.imgur.com/1.jpg" alt="Photo 1">
    <img src="https://i.imgur.com/2.jpg" alt="Photo 2">
    <img src="https://i.imgur.com/3.jpg" alt="Photo 3">
    <img src="https://i.imgur.com/4.jpg" alt="Photo 4">
  </div>

  <audio controls autoplay loop>
    <source src="https://www.example.com/song.mp3" type="audio/mpeg">
  </audio>

  <footer>Made with ❤️ by You</footer>
</body>
</html>
