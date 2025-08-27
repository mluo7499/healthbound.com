<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Healthbound Family Practice</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 50px;
    }

    h1 {
      font-size: 60px;
      display: inline-block;
      border-bottom: 3px solid #ccc;
      padding-bottom: 10px;
    }

    p.saying {
      font-size: 20px;
      font-style: italic;
      margin-top: 20px;
    }

    .circles {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 80px;
      margin-top: 40px;
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

    .circle.left { margin-left: -20px; }
    .circle.right { margin-right: -20px; }

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
  </style>
</head>
<body>

  <h1>🏥 Healthbound</h1>
  <p class="saying">“Caring for you, every step of the way”</p>

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

</body>
</html>
