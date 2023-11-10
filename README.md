<!DOCTYPE html>
<html>
<meta charset='UTF-8' />
<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport' />
<meta content='IE=edge' http-equiv='X-UA-Compatible' />

<link rel="icon" type="image/svg+xml" href="https://feeldreams.github.io/main-icon.png">
<link rel="apple-touch-icon" href="https://feeldreams.github.io/main-icon.png">
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
<script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link rel="stylesheet" href="https://feeldreams.github.io/punyasesuatu/production/style.css">
<script src="https://unpkg.com/scrollreveal"></script>

<head>
  <title>Untukmu - Script HTML buat Kamu</title>
  <meta name="description" content="@feelthisray - Script by Feeldream Repl Co">

  <!-- 
    Script ini dibuat
    oleh Feeldream.id ^_^


    Buat yang Masih
    Bingung Editnya
    DM ke IG @rayyarrr ya!
  -->

</head>

<body>

  <div class="overlay">
    <!-- Tampilan Loading Awal -->
    <div class="loading-message">Hai kamu!<br>Tunggu dulu ya..</div>

    <!-- Tampilan Tombol Awal -->
    <div id="loveIn" class="blocklove">
      <label class="lovein">&#10084;</label>
      <p id="ket">Sentuh LOVEnya!</p>
    </div>
  </div>

  <!-- Ganti Audio di dalam src="" ya! 
       Kalian bisa menguploadnya ke
       https://jukehost.co.uk/ -->
  <audio src="https://feeldreams.github.io/punyasesuatu/karenabersamamu.mp3" id="linkmp3" class="sembunyi"></audio>

  <!-- Konten Pertama -->
  <section class="first" id="inisection">
    <div class="wp">
      <!-- Ganti Background Pertama di dalam src="" ya -->
      <img src="https://feeldreams.github.io/punyasesuatu/1.jfif" />
    </div>
    <div id="first_stiker" class="stiker">
      <!-- Ganti Stiker Pertama di dalam src="" ya -->
      <img src="https://feeldreams.github.io/peachlove.gif" id="inistiker1" />
      <!-- Ganti Stiker Kedua di dalam src="" ya -->
      <img src="https://feeldreams.github.io/peachbunga2.gif" id="inistiker2" class="sembunyi" />
    </div>

    <!-- Teks Konten Pertama, 
         gunakan <br> untuk baris baru -->
    <h1 id="teks1" class="scaleUp itim">Hai Neng! 😍</h1>
    <h1 id="teks2" class="sembunyi">Untuk Sayangku</h1>
    <p id="teks3" class="scaleIn transition">Aku ada pesan buat kamu...<br><br><span class="text-xl">👉👈</span></p>

    <div id="sentuh" class="menu">
      <h1 class="scaleUp itim med">Sentuh LOVEnya</h1>
      <a class='tombol' onclick="funSentuh()">
        <svg id="svgheart" xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'>
          <g transform='translate(2.550170, 3.550158)'>
            <path
              d='M0.371729633,8.89614246 C-0.701270367,5.54614246 0.553729633,1.38114246 4.07072963,0.249142462 C5.92072963,-0.347857538 8.20372963,0.150142462 9.50072963,1.93914246 C10.7237296,0.0841424625 13.0727296,-0.343857538 14.9207296,0.249142462 C18.4367296,1.38114246 19.6987296,5.54614246 18.6267296,8.89614246 C16.9567296,14.2061425 11.1297296,16.9721425 9.50072963,16.9721425 C7.87272963,16.9721425 2.09772963,14.2681425 0.371729633,8.89614246 Z'>
            </path>
            <path d='M13.23843,4.013842 C14.44543,4.137842 15.20043,5.094842 15.15543,6.435842'></path>
          </g>
        </svg>
      </a>
      <svg class='line' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'>
        <g transform='translate(5.000000, 8.500000)'>
          <path d='M14,0 C14,0 9.856,7 7,7 C4.145,7 0,0 0,0'></path>
        </g>
      </svg>
    </div>
  </section>
  <!-- Penutup Konten Pertama -->

  <!-- Konten Kedua -->
  <section>
    <div class="wp">
      <!-- Ganti Background Kedua di dalam src="" ya -->
      <img src="https://feeldreams.github.io/punyasesuatu/2.jfif" />
    </div>
    <div class="stiker hide" id="teks4">
      <!-- Ganti Stiker Konten Kedua di dalam src="" ya -->
      <img src="https://feeldreams.github.io/peach3.gif" />
    </div>

    <!-- Teks Konten Kedua -->
    <h1 class="scaleUp itim med">Neng Rima Ahadiah</h1>
    <h1 class="scaleUp itim med">Semangat menjadi MoT DAD 💗🥰</h1>

    <div id="scroll-container" class="blocktext txt transition scale0">
      <!-- Teks Animasi Konten Kedua,
           gunakan <br> untuk baris baru -->
      <p id="textsec2" class="anm itim text-lg">Jaga Kesehatan<br>Jangan lupa makan<br>Jangan lupa Sholat<br>Jangan Macem-macem ya
        <br><br><b>AKU <b class="putih merah">SAYANG</b> BANGET<br>SAMA <b>KAMUUU</b> </b>
      </p>
    </div>
  </section>
  <!-- Penutup Konten Kedua -->

  <script src="https://feeldreams.github.io/punyasesuatu/production/script.js"></script>
  
</body>

</html>
