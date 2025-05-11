<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/> 
  <link rel="stylesheet" href="britday.css" />
</head>
<body>
  <div class="container">
    <div class="envelope" onclick="openEnvelope()">
      <div class="flap"></div>
      <div class="body"></div>
      <div class="text">Klik untuk buka</div>
    </div>
    <div class="card hidden" id="card">
      <h1>🎉 Selamat Ulang Tahun 🎉</h1>
      <h2>Zulfaa Rosada yang ke-19 Tahun</h2>
      <p>Kamu sudah hebat sejauh ini 💖 Semangatt yahh de!</p>
    </div>
    <div class="balloons" id="balloons">
      <div class="balloon pink"></div>
      <div class="balloon purple"></div>
      <div class="balloon yellow"></div>
    </div>
  </div>
  <script>
    function openEnvelope() {
      document.querySelector('.envelope').classList.add('opened');
      document.getElementById('card').classList.remove('hidden');
      document.getElementById('balloons').classList.add('show');
    }
  </script>
</body>
</html>
