<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>shaxfx_18</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom, #111827, #000);
      color: white;
    }
    header {
      background: url('https://images.unsplash.com/photo-1612831455542-314ce4fa1312?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      text-align: center;
      padding: 100px 20px;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 64px;
      color: gold;
    }
    header h2 {
      font-size: 36px;
      font-weight: bold;
      margin-top: 10px;
    }
    header p {
      margin-top: 20px;
      font-size: 18px;
      color: #d1d5db;
    }
    .buttons {
      margin-top: 30px;
    }
    .buttons button {
      padding: 12px 24px;
      margin: 0 10px;
      background: gold;
      border: none;
      font-weight: bold;
      cursor: pointer;
      border-radius: 6px;
      transition: all 0.3s;
    }
    .buttons button:hover {
      background: #facc15;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .section-title {
      font-size: 36px;
      margin-bottom: 40px;
    }
    .quote-box {
      background: #1f2937;
      border-radius: 10px;
      padding: 40px;
      max-width: 800px;
      margin: 0 auto 30px;
    }
    .quote-box p {
      font-size: 20px;
      font-style: italic;
    }
    .quote-box span {
      display: block;
      margin-top: 20px;
      font-weight: bold;
      color: gold;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1100px;
      margin: 0 auto;
    }
    .card {
      background: #111827;
      padding: 30px;
      border-radius: 10px;
      border: 1px solid #374151;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      border-color: gold;
    }
    .card h3 {
      color: gold;
      margin-bottom: 10px;
    }
    .card p {
      color: #d1d5db;
    }
    footer {
      text-align: center;
      padding: 40px;
      background: #000;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <header>
    <h1>shaxfx_18</h1>
    <h2>Trading &bull; Self-Development &bull; Discipline</h2>
    <p>Master the markets through disciplined trading, continuous learning, and personal growth</p>
    <div class="buttons">
      <button onclick="alert('Coming soon!')">Explore Knowledge</button>
      <button onclick="alert('Coming soon!')">Daily Wisdom</button>
    </div>
  </header>

  <section>
    <h2 class="section-title">Words of <span style="color: gold;">Wisdom</span></h2>
    <div class="quote-box">
      <p>"The stock market is filled with individuals who know the price of everything, but the value of nothing."</p>
      <span>&mdash; Philip Fisher</span>
    </div>
  </section>

  <section>
    <h2 class="section-title">Sources of <span style="color: gold;">Knowledge</span></h2>
    <div class="cards">
      <div class="card">
        <h3>Trading Fundamentals</h3>
        <p>Master the basics of technical analysis, risk management, and market psychology</p>
      </div>
      <div class="card">
        <h3>Psychology & Discipline</h3>
        <p>Develop mental strength and emotional control for consistent trading success</p>
      </div>
      <div class="card">
        <h3>Market Analysis</h3>
        <p>Advanced strategies for reading market trends and making informed decisions</p>
      </div>
      <div class="card">
        <h3>Risk Management</h3>
        <p>Protect your capital with proven risk management techniques and position sizing</p>
      </div>
      <div class="card">
        <h3>Personal Development</h3>
        <p>Build habits, mindset, and skills that extend beyond trading into life success</p>
      </div>
      <div class="card">
        <h3>Video Library</h3>
        <p>Comprehensive video courses and tutorials for visual learners</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 shaxfx_18. All rights reserved.
  </footer>
</body>
</html>
