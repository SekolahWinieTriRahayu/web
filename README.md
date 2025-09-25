<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">

  <title>SMK Negeri 79</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #ffeef5;
      color: #333;
    }
    header {
      background: #ffb6c1;
      padding: 20px;
      text-align: center;
      color: white;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      background: #ff9bb3;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px;
    }
    section h2 {
      text-align: center;
      color: #d6336c;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card h3 {
      margin: 10px 0;
      color: #ff4d6d;
    }
    .card p {
      color: #555;
    }
    /* khusus kartu siswa */
    .student-card {
      border: 2px solid #ffb6c1;
      transition: transform 0.3s;
    }
    .student-card:hover {
      transform: scale(1.05);
    }
    /* form login */
    form {
      max-width: 400px;
      margin: auto;
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    form input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    form button {
      background: #ff4d6d;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1em;
    }
    form button:hover {
      background: #d6336c;
    }
    footer {
      background: #ff9bb3;
      text-align: center;
      padding: 15px;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SMK Negeri 79</h1>
    <p>Sekolah Unggul, Berprestasi, dan Berkarakter</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#profil">Profil</a>
    <a href="#siswa">Nama Siswa</a>
    <a href="#kejurusan">Kejurusan</a>
    <a href="#berita">Berita</a>
    <a href="#login">Login</a>
  </nav>

  <!-- Home -->
  <section id="home">
    <h2>Selamat Datang di SMK Negeri 79</h2>
    <p style="text-align:center;">SMK Negeri 79 hadir sebagai sekolah dengan berbagai jurusan unggulan yang siap mencetak generasi berprestasi.</p>
  </section>

  <!-- Profil -->
  <section id="profil">
    <h2>Profil Sekolah</h2>
    <p style="text-align:center;">SMK Negeri 79 berdiri sejak tahun 2020 dengan visi mencetak lulusan yang berkompeten, kreatif, serta mampu bersaing di dunia industri maupun akademik.</p>
  </section>

  <!-- Nama Siswa -->
  <section id="siswa">
    <h2>Nama Siswa</h2>
    <div class="grid">
      <div class="card student-card">
        <h3>👩‍💻 Aulia Rahman</h3>
        <p>Kelas: XI RPL 1</p>
      </div>
      <div class="card student-card">
        <h3>🎨 Nanda Putri</h3>
        <p>Kelas: X MM 2</p>
      </div>
      <div class="card student-card">
        <h3>🖥️ Rizky Saputra</h3>
        <p>Kelas: XII TKJ 1</p>
      </div>
      <div class="card student-card">
        <h3>📚 Dewi Lestari</h3>
        <p>Kelas: XI BDP 1</p>
      </div>
    </div>
  </section>

  <!-- Kejurusan -->
  <section id="kejurusan">
    <h2>Kejurusan</h2>
    <div class="grid">
      <div class="card">
        <h3>RPL</h3>
        <p>Rekayasa Perangkat Lunak</p>
      </div>
      <div class="card">
        <h3>TKJ</h3>
        <p>Teknik Komputer dan Jaringan</p>
      </div>
      <div class="card">
        <h3>MM</h3>
        <p>Multimedia</p>
      </div>
      <div class="card">
        <h3>BDP</h3>
        <p>Bisnis Daring dan Pemasaran</p>
      </div>
    </div>
  </section>

  <!-- Berita -->
  <section id="berita">
    <h2>Berita Terbaru</h2>
    <div class="grid">
      <div class="card">
        <h3>Lomba Karya Ilmiah</h3>
        <p>Siswa SMK 79 berhasil meraih juara 1 lomba karya ilmiah tingkat provinsi 🎉</p>
      </div>
      <div class="card">
        <h3>Ekstrakurikuler Seni</h3>
        <p>Pentas seni tahunan SMK 79 sukses memukau penonton ✨</p>
      </div>
      <div class="card">
        <h3>SMK 79 Diresmikan</h3>
        <p>SMK Negeri 79 resmi berdiri pada tahun 2020 dan kini menjadi sekolah favorit dengan berbagai jurusan unggulan 🌟</p>
      </div>
    </div>
  </section>

  <!-- Login -->
  <section id="login">
    <h2>Login</h2>
    <form>
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <button type="submit">Login</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 SMK Negeri 79 | Semua Hak Dilindungi</p>
  
</body>
</html>
