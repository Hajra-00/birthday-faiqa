<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Faiqa!</title>
  <style>
    body {
      background: linear-gradient(135deg, #ffe6f0, #e6f7ff);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding: 50px;
      color: #333;
      overflow-x: hidden;
    }
    h1 {
      font-size: 3em;
      color: #ff4081;
    }
    p {
      max-width: 600px;
      margin: 20px auto;
      font-size: 1.2em;
      line-height: 1.6;
    }
    .heart {
      color: red;
      font-size: 2em;
    }
    .footer {
      margin-top: 40px;
      font-style: italic;
      color: #777;
    }
  </style>
</head>
<body>
  <h1>Happy Birthday, Faiqa! 🎉</h1>
  <p>
    On this special day, I just want to remind you how incredibly lucky I am to have you in my life.
    I love you more deeply than words can express — you're not just special, you're my everything. 💖
  </p>
  <p class="heart">❤</p>
  <div class="footer">With all my love, always and forever.</div>

  <!-- Confetti Script -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
  <script>
    function throwConfetti() {
      confetti({
        particleCount: 100,
        spread: 70,
        origin: { y: 0.6 }
      });
    }
    setInterval(throwConfetti, 3000);
    throwConfetti();
  </script>

  <!-- YouTube Embed -->
  <iframe width="0" height="0" src="https://www.youtube.com/embed/NfH2A0GQ4CM?autoplay=1&loop=1&playlist=NfH2A0GQ4CM" 
        title="YouTube video player" frameborder="0" allow="autoplay" allowfullscreen></iframe>
</body>
</html>
