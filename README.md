# pondok-pesantren-darul-muqomah
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Website resmi Pondok Pesantren Darul Muqomah Sumedang Sari. Pelajari visi, misi, peraturan, dan kegiatan kami." />
  <meta name="keywords" content="Pondok Pesantren, Darul Muqomah, Pesantren Qurani, OKU Timur, Sumedang Sari">
  <meta name="author" content="Pondok Pesantren Darul Muqomah Sumedang Sari">
  <title>Pondok Pesantren Darul Muqomah Sumedang Sari | Pesantren Qur’ani Berprestasi</title>

  <style>
    body {
      font-family: "Arial", sans-serif;
      margin: 0; padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background-color: #1982eb;
      color: #ffffff;
      padding: 20px 30px;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    header img { height: 100px; vertical-align: middle; margin-right: 15px; }
    header h1 { margin: 10px 0; font-size: 2.5rem; font-weight: bold; }

    nav {
      background-color: #004d40;
      padding: 15px 30px;
      position: relative;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    nav ul {
      list-style: none; padding-left: 0; margin: 0;
      display: flex; gap: 25px; flex-wrap: wrap; justify-content: center;
    }
    nav li { font-weight: bold; font-size: 1.1rem; }
    nav a { color: #ffffff; text-decoration: none; transition: color 0.3s; padding: 5px 10px; border-radius: 4px; }
    nav a:hover { color: #b2dfdb; background-color: rgba(255,255,255,0.1); }
    #menu-toggle {
      display: none; background: none; border: none;
      color: white; font-size: 28px; cursor: pointer;
      position: absolute; top: 15px; right: 30px;
    }
    @media(max-width: 700px) {
      nav ul { flex-direction: column; display: none; background-color: #004d40; border-radius: 8px; margin-top: 15px; padding: 15px 0; }
      nav ul.show { display: flex; }
      #menu-toggle { display: block; }
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 30px;
      background: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    h2 { color: #004d40; text-align: center; font-size: 2rem; margin-bottom: 20px; }

    ul.misi-list { list-style-type: disc; margin-left: 30px; font-size: 1.1rem; }

    iframe, video { width: 100%; aspect-ratio: 16/9; border-radius: 10px; border: none; }

    footer {
      background-color: #027df8;
      color: #0808fc;
      padding: 50px 30px;
      text-align: center;
      position: relative;
      overflow: hidden;
      box-shadow: 0 -2px 4px rgba(0,0,0,0.1);
    }
    footer p, footer a { color: #ffffff; text-decoration: none; margin: 10px 0; font-size: 1.1rem; }
    footer a:hover { color: #b2dfdb; text-decoration: underline; }

    .social-footer {
      margin-top: 30px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .social-footer a {
      display: inline-block;
      transition: transform 0.4s, filter 0.4s;
    }
    .social-footer a:hover {
      transform: translateY(-8px) scale(1.2);
      filter: drop-shadow(0 0 6px #fff);
    }
    .social-icon { width: 40px; height: 40px; }

    /* WhatsApp Floating */
    .whatsapp-float {
      position: fixed; bottom: 30px; right: 30px;
      background: #25d366; width: 60px; height: 60px;
      border-radius: 50%; text-align: center; font-size: 32px;
      color: white; line-height: 60px; z-index: 1000;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }
    .whatsapp-float:hover { transform: scale(1.1); }

    .back-to-top {
      position: fixed; bottom: 100px; right: 30px;
      background: #004d40; color: white; border-radius: 50%;
      text-align: center; width: 50px; height: 50px; font-size: 24px;
      line-height: 50px; text-decoration: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: background 0.3s, transform 0.3s;
    }
    .back-to-top:hover { background: #00695c; transform: scale(1.1); }

    /* Form Pendaftaran */
    #pendaftaran { background: linear-gradient(to bottom right, #f9f9f9, #e8f5e8); padding: 50px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
    .form-input { width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 8px; margin: 10px 0 20px 0; font-size: 16px; transition: 0.3s; }
    .form-input:focus { border-color: #004d40; box-shadow: 0 0 8px rgba(0, 77, 64, 0.3); outline: none; }
    .form-btn { background-color: #25d366; color: white; border: none; width: 100%; padding: 15px; border-radius: 8px; font-size: 18px; font-weight: bold; cursor: pointer; transition: 0.3s; }
    .form-btn:hover { background-color: #1ebe5d; transform: scale(1.05); }
  </style>
</head>

<body>

<header>
  <img src="logo-removebg-preview.png" alt="Logo Pondok Pesantren Darul Muqomah" />
  <h1>PONDOK PESANTREN DARUL MUQOMAH</h1>
  <h1>دَارُ الْمُقَامَةِ سُومِيدَانْغ سَارِي</h1>
</header>

<nav>
  <button id="menu-toggle">☰</button>
  <ul id="nav-list">
    <li><a href="#beranda">Beranda</a></li>
    <li><a href="#prestasi">Prestasi</a></li>
    <li><a href="#kegiatan">Kegiatan</a></li>
    <li><a href="e:\projeck web\ppdm\galeri pondok pesantren daarul muqomah.png">Galeri</a></li>
    <li><a href="#pendaftaran">Pendaftaran</a></li>
    <li><a href="https://ppdarulmuqomah.blogspot.com/">Profil Pondok</a></li>
    <li><a href="#visi-misi">Visi Misi</a></li>
  </ul>
</nav>

<div class="container" id="beranda" style="text-align: center; padding: 50px;">
  <h2>KEGIATAN PONDOK PESANTREN DARUL MUQOMAH DI ACARA 17 AGUSTUS</h2>
  <video controls poster="poster.jpg">
    <source src="vidio.mp4" type="video/mp4">
    Browser Anda tidak mendukung pemutaran video.
  </video>
</div>

<div class="container" id="visi-misi">
  <h2>Visi</h2>
  <p>“Membentuk Pribadi Qur’ani, Berprestasi, Berakhlakul Karimah, Bersosial Tinggi, Serta Berkhidmah Kepada Agama, Nusa Bangsa dan Bernilaikan Aswaja (Ahli Sunah Waljamaah).”</p>

  <h2>Misi</h2>
  <ul class="misi-list">
    <li>Menyelenggarakan Program Kegiatan Berbasis Pembelajaran Al-Qur’an.</li>
    <li>Mempersiapkan Generasi Qur’ani yang Memiliki Pemahaman Mendalam Tentang Al-Qur’an dan Mampu Mengaplikasikannya dalam Kehidupan Sehari-hari.</li>
    <li>Membangun Kepribadian Santri dengan Menanamkan Dasar Aqidah, Kesadaran Kepribadian, dan Bersosial Tinggi.</li>
    <li>Menumbuhkan Sifat Toleransi, Jiwa Ukhuwah, serta Tanggung Jawab dan Semangat Kemandirian.</li>
    <li>Menyiapkan Kader Santri yang Ikhlas, Terampil, dan Memiliki Ghiroh Islamiyah Berdasarkan Aswaja, Memiliki Etos Juang yang Tinggi, serta Mampu Berperan Aktif Sebagai Perekat Umat dengan Semangat Cinta Tanah Air dan Almamater.</li>
  </ul>
</div>

<div class="container" id="pendaftaran">
  <h2 style="text-align:center; color:#004d40;">📝 Pendaftaran Santri Baru</h2>
  <p style="text-align:center; font-size:18px; color:#555; max-width:700px; margin:auto;">
    Silakan isi formulir di bawah ini untuk mendaftar sebagai santri Pondok Pesantren <strong>Darul Muqomah Sumedang Sari</strong>.
    Setelah diisi, tekan tombol <b>Kirim ke WhatsApp</b> untuk mengirim data ke admin.
  </p>

  <form id="formPendaftaran" style="max-width:650px; margin:40px auto; text-align:left;">
    <label>Nama Lengkap:</label><br>
    <input type="text" id="nama" required placeholder="Masukkan nama lengkap" class="form-input"><br>

    <label>Jenis Kelamin:</label><br>
    <select id="jk" required class="form-input">
      <option value="">Pilih Jenis Kelamin</option>
      <option value="Laki-laki">Laki-laki</option>
      <option value="Perempuan">Perempuan</option>
    </select><br>

    <label>Tempat, Tanggal Lahir:</label><br>
    <input type="text" id="ttl" required placeholder="Contoh: Sumedang, 10 Mei 2010" class="form-input"><br>

    <label>Alamat Lengkap:</label><br>
    <textarea id="alamat" required placeholder="Masukkan alamat lengkap" rows="3" class="form-input"></textarea><br>

    <label>Asal Sekolah:</label><br>
    <input type="text" id="sekolah" required placeholder="Masukkan asal sekolah" class="form-input"><br>

    <label>Nomor HP/WhatsApp Orang Tua:</label><br>
    <input type="tel" id="wa" required placeholder="Contoh: 082279671805" class="form-input"><br>

    <button type="button" onclick="kirimWA()" class="form-btn">📩 Kirim ke WhatsApp Admin</button>
  </form>
</div>

<!-- Back to Top & WhatsApp Float -->
<a href="#beranda" class="back-to-top">↑</a>
<a href="https://wa.me/6282279671805" target="_blank" class="whatsapp-float">📱</a>

<footer>
  <div class="footer-container" style="text-align:center;">
    <p class="alamat-footer">Jl. Lintas Sumedang Sari, Buay Madang Timur, OKU Timur 32161</p>
    <p class="telepon-footer">Telepon: 085783172412</p>
    <p class="wa-footer">WhatsApp: <a href="https://wa.me/6282279671805" target="_blank">+6282279671805 (Admin)</a></p>
    <p class="email-footer">Email: <a href="mailto:darulmuqomah@gmail.com">darulmuqomah@gmail.com</a></p>

    <div class="social-footer">
      <a href="https://www.instagram.com/darulmuqomahsumedangsari" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" class="social-icon">
      </a>
      <a href="https://youtube.com/@ponpesdarulmuqomahsumedang8568" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube" class="social-icon">
      </a>
      <a href="https://www.tiktok.com/@pp.darulmuqomah.putra" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/Tiktok_icon.svg" alt="TikTok" class="social-icon">
      </a>
      <a href="https://wa.me/6282279671805" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" class="social-icon">
      </a>
    </div>
  </div>
</footer>

<script>
  // Toggle menu mobile
  const menuToggle = document.getElementById('menu-toggle');
  const navList = document.getElementById('nav-list');
  menuToggle.addEventListener('click', () => { navList.classList.toggle('show'); });

  // Smooth scroll for anchor links
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
          e.preventDefault();
          document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
      });
  });

  // Kirim WA
  function kirimWA() {
    const nama = document.getElementById('nama').value;
    const jk = document.getElementById('jk').value;
    const ttl = document.getElementById('ttl').value;
    const alamat = document.getElementById('alamat').value;
    const sekolah = document.getElementById('sekolah').value;
    const wa = document.getElementById('wa').value;

    if(!nama || !jk || !ttl || !alamat || !sekolah || !wa) {
      alert("Harap lengkapi semua data!");
      return;
    }

    const pesan = `📝 Pendaftaran Santri Baru\n\nNama: ${nama}\nJenis Kelamin: ${jk}\nTTL: ${ttl}\nAlamat: ${alamat}\nAsal Sekolah: ${sekolah}\nNo. HP/WA: ${wa}`;
    const urlWA = `https://wa.me/6282279671805?text=${encodeURIComponent(pesan)}`;
    window.open(urlWA, '_blank');
  }
</script>

</body>
</html>