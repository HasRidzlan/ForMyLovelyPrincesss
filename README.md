<html lang="ms">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Support System<3</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: radial-gradient(circle, #0d1b2a, #000);
      color: #ffffff;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 80px 20px 20px;
    }
    header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      color: #7dcfff;
      animation: fadeInDown 2s ease;
    }
    .typewriter {
      font-size: 1.3em;
      text-align: center;
      padding: 20px;
      color: #f0f8ff;
      min-height: 120px;
    }
    .gallery-button {
      display: block;
      width: fit-content;
      margin: 30px auto;
      background: #1e90ff;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .gallery-button:hover {
#surpriseModal {
  position: fixed;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.7);
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 99;
}

#surpriseContent {
  background: #1e2a38;
  color: #fff;
  padding: 30px;
  max-width: 500px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 0 25px rgba(255, 255, 255, 0.2);
  animation: zoomIn 0.5s ease-out;
  font-size: 1.1em;
}

@keyframes zoomIn {
  from {
    transform: scale(0.6);
    opacity: 0;
  }
  to {
    transform: scale(1);
    opacity: 1;
  }
}

      background: #63b3ff;
    }
    .gallery {
  display: none;
  max-width: 900px;
  margin: 40px auto;
  padding: 20px;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

    .gallery img {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(255,255,255,0.2);
    }
    footer {
      text-align: center;
      margin: 60px 20px 30px;
      font-size: 0.9em;
      color: #ccc;
    }
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    .bokeh {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      background: url('https://i.ibb.co/6Jt1TGVk/background3.jpg') center/cover no-repeat;
      opacity: 0.15;
      z-index: -1;
    }
  </style>
</head>
<body>
  <div class="bokeh"></div>

  <header>
    <h1>Untuk Kamu, My Princess</h1>
  </header>

  <div class="typewriter" id="typewriterText"></div>

  <button class="gallery-button" onclick="toggleGallery()">Our Memory</button>
<button class="gallery-button" onclick="showSurprise()">I LOVE YOU SAYANG</button>


  <div class="gallery" id="gallerySection">
    <img src="https://i.ibb.co/66yZw1s/memory1.jpg" alt="Kenangan 1">
    <img src="https://i.ibb.co/NnCFjTx3/memory9.jpg" alt="Kenangan 2">
    <img src="https://i.ibb.co/PLF1jdP/memory3.jpg" alt="Kenangan 3">
    <img src="https://i.ibb.co/MDVZtNp8/memory4.jpg" alt="Kenangan 4">
    <img src="https://i.ibb.co/K1J2GGL/memory6.jpg" alt="Kenangan 5">
    <img src="https://i.ibb.co/XfQR8jNT/memory5.jpg" alt="Kenangan 6">
    <img src="https://i.ibb.co/wNhsccxs/memory7.jpg" alt="Kenangan 7">
    <img src="https://i.ibb.co/cKvCZqrH/memory8.jpg" alt="Kenangan 8">
    <img src="https://i.ibb.co/DfQxGt8n/memory2.jpg" alt="Kenangan 9">
  </div>

<section style="max-width: 600px; margin: 40px auto; background: #102135; padding: 25px; border-radius: 15px; box-shadow: 0 0 10px rgba(255,255,255,0.1);">
  <h3 style="color: #7dcfff; font-family: 'Great Vibes', cursive;">Kenangan Pahit & Manis Kita</h3>
  <p style="margin-top: 10px;">
  Orang tahu… dalam hati sayang, ada satu ruang kosong yang tak semua orang nampak.  
  Rasa kecewa, sebab tak dapat buat apa yang sayang minat sangattt
</p>

<p>
  Tapi setiap kali orang tengok mata sayang, orang nampak kekuatan yang orang sendiri tak tahu nak cari kat mana.
  Sayang tetap senyum, tetap ceria jee walaupun orang tau yang sayang sendiri terpaksa padamkan impian.
</p>

<p>
  Dan tiap kali kita jumpa, walaupun sekejap... perasaan tu datang balik,  
  macam waktu pertama kali kita jumpa dekat KL Sentral tuuu.  
  rasa gelabah tak tentu hala, lepastu senyum sorang ii lepastuuu dalam hati ni ada satu ayat jeee:
  <em>“Dialah satu-satunya.”</em>
</p>

<p>
  Kalau dunia tak bagi sayang peluang merasa semua… biar orang jadi dunia tu.  
  Biar orang ada, dan isi semua ruang yang kosong tu dengan cinta yang tak akan berhenti.
</p>
</section>

  <script>
function showSurprise() {
  document.getElementById("surpriseModal").style.display = "flex";
  launchHearts();
}

// Tutup popup bila klik di luar
window.addEventListener("click", function (e) {
  const modal = document.getElementById("surpriseModal");
  if (e.target === modal) {
    modal.style.display = "none";
  }
});

// Love emoji berterbangan
function launchHearts() {
  for (let i = 0; i < 20; i++) {
    const heart = document.createElement("div");
    heart.innerText = "❤️";
    heart.style.position = "fixed";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.top = "100vh";
    heart.style.fontSize = "24px";
    heart.style.opacity = Math.random();
    heart.style.animation = `flyUp ${2 + Math.random() * 3}s ease-out forwards`;
    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 5000);
  }
}

const flyUpKeyframes = `
@keyframes flyUp {
  to {
    transform: translateY(-120vh) rotate(360deg);
    opacity: 0;
  }
}
`;
const styleSheet = document.createElement("style");
styleSheet.innerText = flyUpKeyframes;
document.head.appendChild(styleSheet);

const text = [
  "Sayang,",
  "Orang tahu orang bukan yang paling sempurna... tapi setiap kekurangan yang orang ada, orang cuba tebus dengan cinta yang tak pernah kurang untuk sayang.",
  "Sayang macam Wi-Fi—bila jauh, hidup orang loading lama sangat.",
  "Kalau orang ada 1 sen setiap kali fikir pasal sayang, orang dah beli KFC setiap hari (tapi sayang tetap menu utama )",
  "Orang buat website ni sebab nak sayang tahu: sayang ni luar biasa... macam Milo kurang air, pekat dan melekat ",
  "Terima kasih sebab sentiasa ada walaupun perangai orang kadang macam Windows kena update tak habis-habis ",
  "Cinta orang kat sayang? Macam charger ori—tak boleh diganti. "
];

    let i = 0;
    let j = 0;
    let currentText = '';
    let isDeleting = false;

    function type() {
      if (i < text.length) {
        if (!isDeleting && j <= text[i].length) {
          currentText = text[i].substring(0, j++);
        } else if (isDeleting && j >= 0) {
          currentText = text[i].substring(0, j--);
        }

        document.getElementById('typewriterText').innerHTML = currentText;

        let speed = isDeleting ? 40 : 80;

        if (!isDeleting && j === text[i].length) {
          isDeleting = true;
          speed = 1600;
        } else if (isDeleting && j === 0) {
          isDeleting = false;
          i++;
        }

        setTimeout(type, speed);
      }
    }

    function toggleGallery() {
      const gallery = document.getElementById('gallerySection');
      gallery.style.display = gallery.style.display === 'grid' ? 'none' : 'grid';
    }

    window.onload = () => {
      type();
    };
  </script>
<div id="surpriseModal" style="display:none;">
  <div id="surpriseContent">
    <h2>ikhlas dari hati...</h2>
 <p>
  Takde satu hari pun orang tak fikir pasal sayang. Tapi orang tahu, kadang orang tak cukup baik untuk sayang.
</p>
<p>
  Orang banyak kurang, banyak salah… tapi satu benda yang orang tak pernah kurang tauu tak rasa sayang ni.
</p>
<p>
  Kalau satu hari nanti sayang dah tak rasa orang ni cukup… tolong jangan lupa, orang pernah sayang sayang sehabis yang orang mampu.
</p>

  </div>
</div>

 <footer>
    Dicipta khas untuk sayang, dari seseorang yang sangat menghargai setiap saat 💙
  </footer>

</body>
</html>
