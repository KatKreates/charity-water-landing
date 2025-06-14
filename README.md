<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity Water - Landing Page</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Proxima+Nova:wght@400;700&display=swap');

    body {
      margin: 0;
      font-family: 'Proxima Nova', Arial, sans-serif;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: url('https://via.placeholder.com/1200x600') center/cover no-repeat;
      color: #fff;
      padding: 100px 20px;
      text-align: center;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.4);
    }
    header h1 {
      font-size: 2.5rem;
      position: relative;
      z-index: 1;
    }
    header p {
      font-size: 1.2rem;
      position: relative;
      z-index: 1;
    }
    header .images {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      gap: 15px;
      position: relative;
      z-index: 1;
    }
    header .images img {
      width: 150px;
      height: auto;
      border-radius: 8px;
    }
    .impact-stories {
      background: #77A8BB;
      padding: 50px 20px;
    }
    .impact-stories h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2.2rem;
    }
    .story {
      max-width: 900px;
      margin: 0 auto 30px;
    }
    .story img {
      width: 100%;
      border-radius: 10px;
    }
    .story p {
      margin-top: 15px;
      font-size: 1.1rem;
    }
    .donate {
      background: #33477D;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }
    .donate h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }
    .amounts button {
      background: #FFC907;
      border: none;
      padding: 12px 20px;
      margin: 5px;
      cursor: pointer;
      border-radius: 5px;
      font-weight: bold;
      font-size: 1.1rem;
    }
    .money-action {
      background: #FFC907;
      padding: 50px 20px;
      text-align: center;
    }
    .money-action h2 {
      margin-bottom: 30px;
      font-size: 2.2rem;
    }
    .money-action img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
    }
    .map {
      background: #FFF7E1;
      color: #333;
      padding: 60px 20px;
      text-align: center;
    }
    .map h2 {
      font-size: 2.2rem;
      margin-bottom: 20px;
    }
    .map img {
      width: 100%;
      max-width: 800px;
      border-radius: 8px;
    }
    .map p {
      margin-top: 15px;
      font-size: 1.1rem;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 10px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>1 in 10 people are without clean water</h1>
    <p>You can provide clean water sources for communities in need</p>
    <div class="images">
      <img src="https://via.placeholder.com/150" alt="Placeholder Image 1">
      <img src="https://via.placeholder.com/150" alt="Placeholder Image 2">
    </div>
  </header>

  <section class="impact-stories">
    <h2>Impact Stories</h2>

    <div class="story">
      <img src="https://via.placeholder.com/800x400" alt="Umu's Story">
      <p><strong>Meet Umu</strong> — Thanks to a solar-powered water system, Umu no longer spends hours collecting unsafe water. She now runs her own hair business and teaches hygiene in her village.</p>
    </div>

    <div class="story">
      <img src="https://via.placeholder.com/800x400" alt="Natalia's Story">
      <p><strong>Meet Natalia</strong> — At just 15, Natalia became the President of her village's water committee in Mozambique, made possible by water donors. She leads her community with pride and purpose.</p>
    </div>
  </section>

  <section class="donate">
    <h2>Choose an amount to give</h2>
    <div class="amounts">
      <button>$10 USD/mo</button>
      <button>$20 USD/mo</button>
      <button>$40 USD/mo</button>
      <button>$100 USD/mo</button>
    </div>
    <p>100% of donations go directly to water projects</p>
  </section>

  <section class="money-action">
    <h2>Your Money in Action</h2>
    <img src="https://via.placeholder.com/300" alt="Clean Water">
    <img src="https://via.placeholder.com/300" alt="Happy Child">
    <img src="https://via.placeholder.com/300" alt="Well Construction">
  </section>

  <section class="map">
    <h2>See Our Global Impact</h2>
    <img src="https://via.placeholder.com/800x400" alt="Impact Map">
    <p>20,297,336 people served • 186,000 water projects • 29 countries</p>
  </section>

  <footer>
    &copy; 2025 charity: water | All rights reserved
  </footer>

</body>
</html>
