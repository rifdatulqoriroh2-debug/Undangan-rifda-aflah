# Undangan-rifda-aflah
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Undangan Pernikahan Rifda & Aflah</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: #fafafa;
      color: #333;
      text-align: center;
    }
    header {
      background: url('https://source.unsplash.com/1600x900/?wedding,flower') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
      font-family: "Great Vibes", cursive;
    }
    header p {
      font-size: 1.2em;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .couple {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .couple img {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #eee;
    }
    .names {
      font-size: 2em;
      font-family: "Great Vibes", cursive;
      margin: 10px 0;
    }
    .details {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }
    .date {
      font-size: 1.3em;
      margin: 10px 0;
      font-weight: bold;
      color: #8b5e34;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      background: #eab308;
      color: #fff;
      border-radius: 25px;
      text-decoration: none;
      margin-top: 15px;
      font-weight: bold;
    }
    .countdown {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .countdown div {
      background: #fff;
      padding: 15px 20px;
      border-radius: 10px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    .countdown span {
      display: block;
      font-size: 2em;
      font-weight: bold;
      color: #8b5e34;
    }
    /* Galeri */
    .slideshow-container {
      position: relative;
      max-width: 100%;
      margin: auto;
    }
    .slides {
      display: none;
    }
    .slides img {
      width: 100%;
      border-radius: 15px;
      max-height: 500px;
      object-fit: cover;
    }
    .prev, .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      padding: 12px;
      margin-top: -22px;
      color: white;
      font-weight: bold;
      font-size: 18px;
      transition: 0.3s;
      border-radius: 0 3px 3px 0;
      user-select: none;
      background: rgba(0,0,0,0.4);
    }
    .next {
      right: 0;
      border-radius: 3px 0 0 3px;
    }
    .prev:hover, .next:hover {
      background-color: rgba(0,0,0,0.8);
    }
    .dot-container {
      text-align: center;
      margin-top: 15px;
    }
    .dot {
      cursor: pointer;
      height: 12px;
      width: 12px;
      margin: 0 5px;
      background-color: #bbb;
      border-radius: 50%;
      display: inline-block;
      transition: background-color 0.6s ease;
    }
    .active, .dot:hover {
      background-color: #eab308;
    }
    footer {
      background: #222;
      color: #ddd;
      padding: 20px;
      margin-top: 50px;
    }
    /* Musik */
    #music-control {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #eab308;
      color: #fff;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 20px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    /* RSVP */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    input, select, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1em;
    }
    button[type="submit"] {
      background: #8b5e34;
      color: #fff;
      border: none;
      padding: 12px;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
    }
    button[type="submit"]:hover {
      background: #eab308;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <h1>Undangan Pernikahan</h1>
    <p>Dengan penuh kebahagiaan kami mengundang Anda</p>
  </header>

  <section class="couple">
    <div>
      <img src="https://source.unsplash.com/200x200/?bride" alt="Pengantin Wanita">
      <p class="names">Rifdatul Qoriroh (Rifda)</p>
      <p>Putri dari Bapak Imam Chudori & Ibu Siti Aliyah</p>
      <p>Alamat: Dusun Kepel, Desa Ampel, Kec. Wuluhan</p>
    </div>
    <p style="font-size: 1.5em;">&amp;</p>
    <div>
      <img src="https://source.unsplash.com/200x200/?groom" alt="Pengantin Pria">
      <p class="names">Nur Aflah Muzakka (Aflah)</p>
      <p>Putra dari Bapak Kholis S. Ag & Ibu Amaliyah Ulfa</p>
      <p>Alamat: Dusun Krajan Lor, Desa Gumelar, Kec. Balung</p>
    </div>
  </section>

  <section class="details">
    <h2>Akad Nikah</h2>
    <p class="date">Sabtu, 8 November 2025</p>
    <p>Pukul 10.00 WIB</p>
    <p>Bertempat di rumah mempelai wanita</p>
  </section>

  <section class="details">
    <h2>Resepsi</h2>
    <p class="date">Sabtu, 8 November 2025</p>
    <p>Pukul 15.00 WIB - Selesai</p>
    <p>Bertempat di rumah mempelai wanita</p>
    <a href="https://maps.google.com" target="_blank" class="button">Lihat Lokasi</a>
  </section>

  <section class="details">
    <h2>Menuju Hari Bahagia</h2>
    <div class="countdown" id="countdown">
      <div><span id="days">0</span>Hari</div>
      <div><span id="hours">0</span>Jam</div>
      <div><span id="minutes">0</span>Menit</div>
      <div><span id="seconds">0</span>Detik</div>
    </div>
  </section>

  <section class="details">
    <h2>Galeri Foto</h2>
    <div class="slideshow-container">
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?wedding,couple" alt="Foto 1">
      </div>
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?love,couple" alt="Foto 2">
      </div>
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?romantic,couple" alt="Foto 3">
      </div>
      <a class="prev" onclick="plusSlides(-1)">❮</a>
      <a class="next" onclick="plusSlides(1)">❯</a>
    </div>
    <div class="dot-container">
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
      <span class="dot" onclick="currentSlide(3)"></span>
    </div>
  </section>

  <section class="details">
    <h2>RSVP</h2>
    <p>Silakan konfirmasi kehadiran Anda:</p>
    <form action="https://docs.google.com/forms/d/e/FORM_ID/formResponse" method="POST" target="_blank">
      <input type="text" name="entry.123456" placeholder="Nama Anda" required>
      <input type="number" name="entry.654321" placeholder="Jumlah Tamu" min="1" required>
      <select name="entry.987654" required>
        <option value="">Konfirmasi Kehadiran</option>
        <option value="Hadir">Hadir</option>
        <option value="Tidak Hadir">Tidak Hadir</option>
      </select>
      <textarea name="entry.111111" placeholder="Ucapan & Doa" rows="3"></textarea>
      <button type="submit">Kirim</button>
    </form>
    <p style="font-size: 0.9em; color: #777;">*Data akan otomatis tersimpan ke Google Sheets</p>
  </section>

  <footer>
    <p>© 2025 Rifda & Aflah</p>
  </footer>

  <!-- Musik -->
  <audio id="bg-music" loop>
    <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mpeg">
    Browser Anda tidak mendukung audio.
  </audio>
  <button id="music-control">▶</button>

  <script>
    // Countdown Timer
    const weddingDate = new Date("Nov 8, 2025 10:00:00").getTime();
    const x = setInterval(function() {
      const now = new Date().getTime();
      const distance = weddingDate - now;

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      document.getElementById("days").innerText = days;
      document.getElementById("hours").innerText = hours;
      document.getElementById("minutes").innerText = minutes;
      document.getElementById("seconds").innerText = seconds;

      if (distance < 0) {
        clearInterval(x);
        document.getElementById("countdown").innerHTML = "<h3>Hari Bahagia Telah Tiba!</h3>";
      }
    }, 1000);

    // Musik Play/Pause
    const music = document.getElementById("bg-music");
    const musicBtn = document.getElementById("music-control");

    let isPlaying = false;
    musicBtn.addEventListener("click", () => {
      if (isPlaying) {
        music.pause();
        musicBtn.textContent = "▶";
      } else {
        music.play();
        musicBtn.textContent = "⏸";
      }
      isPlaying = !isPlaying;
    });

    document.body.addEventListener("click", () => {
      if (!isPlaying) {
        music.play();
        musicBtn.textContent = "⏸";
        isPlaying = true;
      }
    }, { once: true });

    // Slideshow
    let slideIndex = 0;
    showSlides();

    function showSlides() {
      let i;
      let slides = document.getElementsByClassName("slides");
      let dots = document.getElementsByClassName("dot");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
      }
      slides[slideIndex-1].style.display = "block";
      dots[slideIndex-1].className += " active";
      setTimeout(showSlides, 4000);
    }

    function plusSlides(n) {
      slideIndex += n - 1;
      showSlides();
    }

    function currentSlide(n) {
      slideIndex = n - 1;
      showSlides();
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Undangan Pernikahan Rifda & Aflah</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: #fafafa;
      color: #333;
      text-align: center;
    }
    header {
      background: url('https://source.unsplash.com/1600x900/?wedding,flower') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
      font-family: "Great Vibes", cursive;
    }
    header p {
      font-size: 1.2em;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .couple {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .couple img {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #eee;
    }
    .names {
      font-size: 2em;
      font-family: "Great Vibes", cursive;
      margin: 10px 0;
    }
    .details {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }
    .date {
      font-size: 1.3em;
      margin: 10px 0;
      font-weight: bold;
      color: #8b5e34;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      background: #eab308;
      color: #fff;
      border-radius: 25px;
      text-decoration: none;
      margin-top: 15px;
      font-weight: bold;
    }
    .countdown {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .countdown div {
      background: #fff;
      padding: 15px 20px;
      border-radius: 10px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    .countdown span {
      display: block;
      font-size: 2em;
      font-weight: bold;
      color: #8b5e34;
    }
    /* Galeri */
    .slideshow-container {
      position: relative;
      max-width: 100%;
      margin: auto;
    }
    .slides {
      display: none;
    }
    .slides img {
      width: 100%;
      border-radius: 15px;
      max-height: 500px;
      object-fit: cover;
    }
    .prev, .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      padding: 12px;
      margin-top: -22px;
      color: white;
      font-weight: bold;
      font-size: 18px;
      transition: 0.3s;
      border-radius: 0 3px 3px 0;
      user-select: none;
      background: rgba(0,0,0,0.4);
    }
    .next {
      right: 0;
      border-radius: 3px 0 0 3px;
    }
    .prev:hover, .next:hover {
      background-color: rgba(0,0,0,0.8);
    }
    .dot-container {
      text-align: center;
      margin-top: 15px;
    }
    .dot {
      cursor: pointer;
      height: 12px;
      width: 12px;
      margin: 0 5px;
      background-color: #bbb;
      border-radius: 50%;
      display: inline-block;
      transition: background-color 0.6s ease;
    }
    .active, .dot:hover {
      background-color: #eab308;
    }
    footer {
      background: #222;
      color: #ddd;
      padding: 20px;
      margin-top: 50px;
    }
    /* Musik */
    #music-control {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #eab308;
      color: #fff;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 20px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    /* RSVP */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    input, select, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1em;
    }
    button[type="submit"] {
      background: #8b5e34;
      color: #fff;
      border: none;
      padding: 12px;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
    }
    button[type="submit"]:hover {
      background: #eab308;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <h1>Undangan Pernikahan</h1>
    <p>Dengan penuh kebahagiaan kami mengundang Anda</p>
  </header>

  <section class="couple">
    <div>
      <img src="https://source.unsplash.com/200x200/?bride" alt="Pengantin Wanita">
      <p class="names">Rifdatul Qoriroh (Rifda)</p>
      <p>Putri dari Bapak Imam Chudori & Ibu Siti Aliyah</p>
      <p>Alamat: Dusun Kepel, Desa Ampel, Kec. Wuluhan</p>
    </div>
    <p style="font-size: 1.5em;">&amp;</p>
    <div>
      <img src="https://source.unsplash.com/200x200/?groom" alt="Pengantin Pria">
      <p class="names">Nur Aflah Muzakka (Aflah)</p>
      <p>Putra dari Bapak Kholis S. Ag & Ibu Amaliyah Ulfa</p>
      <p>Alamat: Dusun Krajan Lor, Desa Gumelar, Kec. Balung</p>
    </div>
  </section>

  <section class="details">
    <h2>Akad Nikah</h2>
    <p class="date">Sabtu, 8 November 2025</p>
    <p>Pukul 10.00 WIB</p>
    <p>Bertempat di rumah mempelai wanita</p>
  </section>

  <section class="details">
    <h2>Resepsi</h2>
    <p class="date">Sabtu, 8 November 2025</p>
    <p>Pukul 15.00 WIB - Selesai</p>
    <p>Bertempat di rumah mempelai wanita</p>
    <a href="https://maps.google.com" target="_blank" class="button">Lihat Lokasi</a>
  </section>

  <section class="details">
    <h2>Menuju Hari Bahagia</h2>
    <div class="countdown" id="countdown">
      <div><span id="days">0</span>Hari</div>
      <div><span id="hours">0</span>Jam</div>
      <div><span id="minutes">0</span>Menit</div>
      <div><span id="seconds">0</span>Detik</div>
    </div>
  </section>

  <section class="details">
    <h2>Galeri Foto</h2>
    <div class="slideshow-container">
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?wedding,couple" alt="Foto 1">
      </div>
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?love,couple" alt="Foto 2">
      </div>
      <div class="slides fade">
        <img src="https://source.unsplash.com/900x500/?romantic,couple" alt="Foto 3">
      </div>
      <a class="prev" onclick="plusSlides(-1)">❮</a>
      <a class="next" onclick="plusSlides(1)">❯</a>
    </div>
    <div class="dot-container">
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
      <span class="dot" onclick="currentSlide(3)"></span>
    </div>
  </section>

  <section class="details">
    <h2>RSVP</h2>
    <p>Silakan konfirmasi kehadiran Anda:</p>
    <form action="https://docs.google.com/forms/d/e/FORM_ID/formResponse" method="POST" target="_blank">
      <input type="text" name="entry.123456" placeholder="Nama Anda" required>
      <input type="number" name="entry.654321" placeholder="Jumlah Tamu" min="1" required>
      <select name="entry.987654" required>
        <option value="">Konfirmasi Kehadiran</option>
        <option value="Hadir">Hadir</option>
        <option value="Tidak Hadir">Tidak Hadir</option>
      </select>
      <textarea name="entry.111111" placeholder="Ucapan & Doa" rows="3"></textarea>
      <button type="submit">Kirim</button>
    </form>
    <p style="font-size: 0.9em; color: #777;">*Data akan otomatis tersimpan ke Google Sheets</p>
  </section>

  <footer>
    <p>© 2025 Rifda & Aflah</p>
  </footer>

  <!-- Musik -->
  <audio id="bg-music" loop>
    <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mpeg">
    Browser Anda tidak mendukung audio.
  </audio>
  <button id="music-control">▶</button>

  <script>
    // Countdown Timer
    const weddingDate = new Date("Nov 8, 2025 10:00:00").getTime();
    const x = setInterval(function() {
      const now = new Date().getTime();
      const distance = weddingDate - now;

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      document.getElementById("days").innerText = days;
      document.getElementById("hours").innerText = hours;
      document.getElementById("minutes").innerText = minutes;
      document.getElementById("seconds").innerText = seconds;

      if (distance < 0) {
        clearInterval(x);
        document.getElementById("countdown").innerHTML = "<h3>Hari Bahagia Telah Tiba!</h3>";
      }
    }, 1000);

    // Musik Play/Pause
    const music = document.getElementById("bg-music");
    const musicBtn = document.getElementById("music-control");

    let isPlaying = false;
    musicBtn.addEventListener("click", () => {
      if (isPlaying) {
        music.pause();
        musicBtn.textContent = "▶";
      } else {
        music.play();
        musicBtn.textContent = "⏸";
      }
      isPlaying = !isPlaying;
    });

    document.body.addEventListener("click", () => {
      if (!isPlaying) {
        music.play();
        musicBtn.textContent = "⏸";
        isPlaying = true;
      }
    }, { once: true });

    // Slideshow
    let slideIndex = 0;
    showSlides();

    function showSlides() {
      let i;
      let slides = document.getElementsByClassName("slides");
      let dots = document.getElementsByClassName("dot");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
      }
      slides[slideIndex-1].style.display = "block";
      dots[slideIndex-1].className += " active";
      setTimeout(showSlides, 4000);
    }

    function plusSlides(n) {
      slideIndex += n - 1;
      showSlides();
    }

    function currentSlide(n) {
      slideIndex = n - 1;
      showSlides();
    }
  </script>
</body>
</html>
