<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Healthbound Family Practice</title>
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      background-color: #a9cd9f;
      filter: saturate(1.3);
      font-family: Arial, sans-serif;
      text-align: center;
    }

    .container {
      min-height: 100%;
      padding: 50px 0;
      box-sizing: border-box;
    }

    h1 {
      font-size: 60px;
      margin-bottom: 10px;
    }

    p.saying {
      font-size: 20px;
      font-style: italic;
      margin-bottom: 20px;
    }

    .image-line {
      margin: 0 auto 40px;
      width: 60%;
    }

    .image-line img {
      width: 100%;
      height: auto;
      display: block;
    }

    .circles {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 80px;
    }

    .circle {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      background-color: #89a34b;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }

    .circle span.title {
      font-size: 18px;
      font-weight: bold;
    }

    .circle span.info {
      font-size: 14px;
      margin-top: 5px;
    }

    .circle span.emoji {
      font-size: 60px;
    }

    .circle.left { margin-left: -20px; }
    .circle.right { margin-right: -20px; }
  </style>
</head>
<body>

  <div class="container">
    <h1>🏥 Healthbound</h1>
    <p class="saying">“Your loacl clinic to go to”</p>

    <div class="image-line">
      <img src="https://static.okweb.com.au/zone/data/-1412115387_healthbound/admin/image/headphoto_rpro.jpg" alt="Healthbound line">
    </div>

    <div class="circles">
      <!-- Call Us Circle -->
      <div class="circle left">
        <span class="emoji">📞</span>
        <span class="title">Call Us!</span>
        <span class="info">(03) 1234 5678</span>
      </div>

      <!-- Come To Us Circle -->
      <div class="circle right">
        <span class="emoji">🏥</span>
        <span class="title">Come To Us!</span>
        <span class="info">144 East Boundary Road</span>
      </div>
    </div>
  </div>

</body>
</html>
