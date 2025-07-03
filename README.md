<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ulang Tahun Ceril Sigma 🎉</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(to bottom, #ffe6e6, #fff0f5);
      text-align: center;
      color: #d63389;
    }
    h1 {
      font-size: 2.5em;
      margin-top: 50px;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 20px auto;
      padding: 0 20px;
    }
    .cake {
      font-size: 5em;
      margin: 30px 0;
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>

  <div class="cake">🎂🎉</div>
  <h1>Selamat Ulang Tahun, Ceril Sigma!</h1>
  <p>
    Selamat ulang tahun Ceril Sigma! Semoga hari ini dan tahun-tahun mendatang dipenuhi tawa, kebahagiaan, dan keberhasilan di setiap langkahmu. Panjang umur, sehat selalu, dan jangan pernah berhenti menjadi versi terbaik dari dirimu sendiri. Mari kita rayakan dengan meriah! 🥳✨
  </p>

  <!-- Music -->
  <audio id="birthday-music" src="https://www.soundjay.com/human/sounds/birthday-happy-birthday-to-you.mp3 " autoplay loop></audio>

  <!-- Confetti -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti @1.6.0/dist/confetti.browser.min.js"></script>
  <script>
    // Efek confetti
    function launchConfetti() {
      confetti({
        particleCount: 150,
        spread: 70,
        origin: { y: 0.6 },
        colors: ['#ff4081', '#fbc02d', '#8e24aa', '#00e676']
      });
    }

    // Jalankan saat halaman dimuat
    window.onload = () => {
      launchConfetti();
    };
  </script>

</body>
</html>
