<style>
.navbar {
  display: flex;
  justify-content: center;
  background-color: #f5f5f5;
  padding: 10px;
  margin-bottom: 20px;
  flex-wrap: wrap;
  position: sticky;
  top: 0;
  z-index: 100;
}
.navbar a {
  margin: 8px 15px;
  text-decoration: none;
  color: #333;
  font-weight: bold;
  cursor: pointer;
}
.navbar a:hover {
  color: #007acc;
}
.section {
  display: none;
  padding: 20px;
}
.section.active {
  display: block;
}
.content-container {
  margin-top: 20px;
}
</style>

<div class="navbar">
  <a onclick="showSection('soal')">Soal Responsi</a>
    <a onclick="showSection('tim pengajar')">Tim Pengajar Responsi</a>
  <a onclick="showSection('nilai tugas')">Nilai Tugas</a>
</div>

<!-- Soal Responsi Section -->
<div id="soal" class="section">
  <h2>Soal Responsi</h2>

  <h3>Pengantar Sains Data</h3>
  <ul>
    <li><a href="https://drive.google.com/drive/folders/13odOWAsMnDVLOL3XU6xD7itkZgR-M3Wy?usp=drive_link">Semester Reguler PTA 2023/24 (Dept Math)</a></li>
    <li><a href="https://drive.google.com/drive/folders/1p-MPrF2blbNgPMM54yzbnUs0o86llMaA?usp=drive_link">Semester Reguler ATA 2023/24 (Dept Bio)</a></li>
    <li><a href="https://drive.google.com/drive/folders/1Q6spz7MC0t2-ZC3cxL8_c630EYq0koKj?usp=drive_link">Semester Pendek PTA 2023/24 (Fakultas MIPA)</a></li>
    <li><a href="https://drive.google.com/drive/folders/1h9oBbN4FFGhRFUuFIuf_e_M7GNaBBuH5?usp=drive_link">Semester Reguler PTA 2024/25 (Dept Math Kelas A)</a></li>
    <li><a href="https://drive.google.com/drive/folders/157hsgHd1Nrds4yEBnkceWyGigolc9Yjh?usp=drive_link">Semester Reguler PTA 2024/25 (Dept Math Kelas D)</a></li>
    <li><a href="https://drive.google.com/drive/folders/17btDDdIrlcXny-B9As8VOADLcbWE4_iq?usp=drive_link">Semester Reguler PTA 2024/25 (Fakultas MIPA Kelas B)</a></li>
    <li><a href="https://drive.google.com/drive/folders/1tPVKmshtq7UoZZ3ItoMfKKua5XaL06xm?usp=drive_link">Semester Reguler PTA 2024/25 (Fakultas MIPA Kelas D)</a></li>
  </ul>

  <h3>Statistika Matematika 1</h3>
  <ul>
    <li>Semester Reguler ATA 2023/24</li>
    <ul>
        <li><a href="https://drive.google.com/drive/folders/1poO6B0jXxzDIP8cQmJrX1uY8RPmwNEVk?usp=drive_link">Paruh 1 (Pra UTS)</a></li>
        <li><a href="https://drive.google.com/drive/folders/1poWZyx6Namax3Dc1eBwfqs3PqaJf4NTi?usp=drive_link">Paruh 2 (Pasca UTS)</a></li>
    </ul>
  </ul>

  <h3>Persamaan Diferensial Biasa</h3>
  <ul>
    <li>Semester Reguler PTA 2024/25</li>
    <ul>
        <li><a href="https://drive.google.com/drive/folders/1gNHHzcsr4BCcOaMwxVfEG4E2hrLeFieX?usp=drive_link">Kontrak Responsi</a></li>
        <li><a href="https://drive.google.com/drive/folders/1dfr0CIuhKH_0ekl5S09VtNuV16sdEHbB?usp=drive_link">Pendahuluan</a></li>
        <li><a href="https://drive.google.com/drive/folders/1U-HahPv1lVrBm4x7sHk3V6CrtwxFrjkY?usp=drive_link">Masalah Nilai Awal & Bidang Fase</a></li>
        <li><a href="https://drive.google.com/drive/folders/1musWOnhZgtGhaEbHQ1SQItKz6J6BNCK_?usp=drive_link">Metode Koefisien Tak Tentu</a></li>
        <li><a href="https://drive.google.com/drive/folders/1yLeVvesjMof59OwxwCTTqp8QHOPRxSyt?usp=drive_link">Metode Variasi Parameter</a></li>
        <li><a href="https://drive.google.com/drive/folders/11OtvOKdhwF_fEX6MvPpCFZf1v6-_uW_F?usp=drive_link">Solusi PDB Dengan Pendekatan Deret</a></li>
      <li><a href="https://drive.google.com/drive/folders/189zqO3Lw4fdp3yOX8klB4vZ_gJh35CBB?usp=drive_link">Transformasi Laplace</a></li>
      <li><a href="https://drive.google.com/drive/folders/1Dg73BkBHH08OCjC_aRyPQmqwQMqi7h3P?usp=drive_link">Sistem PDB</a></li>
      <li><a href="https://drive.google.com/drive/folders/172fVBuUodEpALVt6EAYi7D9tAotjPO-C?usp=drive_link">Pendahuluan Sistem Dinamik</a></li>
      <li><a href="https://drive.google.com/drive/folders/1DYrnncy4ks5Grnnzy4ft8BfFJDZS_EPP?usp=drive_link">Solusi Tutorial Bab 1</a></li>
      <li><a href="https://drive.google.com/drive/folders/1kzOW0S3zpG_cldFs3jTIQpj_KMLqfVEn?usp=drive_link">UTS</a></li>
    </ul>
  </ul>

  <h3>Sains Data</h3>
  <ul>
    <li>Semester Reguler ATA 2024/25</li>
    <ul>
        <li><a href="https://drive.google.com/drive/folders/13jEJgI9Af_O31BZoO6L2v43KlP-ajBzK?usp=drive_link">Dasar-Dasar Pemrograman Python</a></li>
        <li><a href="https://drive.google.com/drive/folders/1tf35LIjN_VYW43KTwSevs-ccFMpPBufV?usp=drive_link">Statistika Sains Data</a></li>
        <li><a href="https://drive.google.com/drive/folders/1Krb6u0yjbAnAxc_pJk9OG5jV_6XaifUZ?usp=drive_link">Metodologi Sains Data</a></li>
        <li><a href="https://drive.google.com/drive/folders/1lRVHUftlRbTvizAcYzx6jtC6MbdMKeZt?usp=drive_link">Data Wrangling</a></li>
        <li><a href="https://drive.google.com/drive/folders/1dVxyG_FFRmwpsJFmXtBf1Fo_qf3kux2o?usp=drive_link">Supervised Learning</a></li>
        <li><a href="https://drive.google.com/drive/folders/1FBLasWTdAs6qGJpEjTIIpP97nccZUR1q?usp=drive_link">Advanced Supervised Learning</a></li>
      <li><a href="https://drive.google.com/drive/folders/1ufVxpetosqzSY_ISi405ruYtzLcLN4TC?usp=drive_link">Support Vector Machine</a></li>
      <li><a href="https://drive.google.com/drive/folders/1a3K7U4A8tEkr6lz-w4Vl-27cQ8MlpdvA?usp=drive_link">Advanced Support Vector Machine</a></li>
      <li><a href="https://drive.google.com/drive/folders/1fcavRTO1xNubRCZMU4twfxJxQ55sBROO?usp=drive_link">K-Means Clustering</a></li>
      <li><a href="https://drive.google.com/drive/folders/11XqnlKresKog9vkPPWs-uwQrqFSECKcd?usp=drive_link">Gini Index & Entropy</a></li>
      <li><a href="https://drive.google.com/drive/folders/1c-XG5sIbJy_iMWNAhxPdkon0nYKbvB-N?usp=drive_link">Piiihan Ganda UTS Sebelumnya</a></li>
      <li><a href="https://drive.google.com/drive/folders/15oDqvAjaYUlyEBRGXH-OULgWD51Y6JPA?usp=drive_link">Try Out Sains Data</a></li>
    </ul>
  </ul>

  <h3>Geometri Analitik</h3>
  <ul>
    <li>Semester Reguler ATA 2024/25</li>
    <ul>
        <li><a href="https://drive.google.com/drive/folders/14bJPrNo2yQQRm7Yn3bN3aCPLxUuuue8t?usp=drive_link">PPT Materi</a></li>
        <li><a href="https://drive.google.com/drive/folders/1kHAnwmo16MHyPvTOe5h4hZ5PGCsVAq3M?usp=drive_link">Garis dan Bidang (Abdul Wahhab)</a></li>
        <li><a href="https://drive.google.com/drive/folders/1NNVexrEBgI0sEzNAhhzEvJz2_Q8d9ZKn?usp=drive_link">Lingkaran dan Bola (Abdul Wahhab)</a></li>
        <li><a href="https://drive.google.com/drive/folders/1JmObQRegB3soXLOkDZ5r6pVCQB3zbgBy?usp=drive_link">Konik dan Kuadrik (Abdul Wahhab, Brayen Damara) </a></li>
        <li><a href="https://drive.google.com/drive/folders/1E5QSoBkpgLUwEA1GfrajnudyQZu2b2yR?usp=drive_link">Teori Umum Konik dan Kuadrik (Brayen Damara, Fritz Adelbertus)</a></li>
        <li><a href="https://drive.google.com/drive/folders/1Vo24krcSxUqiALuNIBK9gg3EE22iO9Cd?usp=drive_link">Klasifikasi Konik dan Kuadrik (Renzie Aditya)</a></li>
      <li><a href="https://drive.google.com/drive/folders/1PWHm8SJm8-0yOk0pdue7yjh1ZavQ1BsT?usp=drive_link">Transformasi Geometri & Afin (Renzie Aditya)</a></li>
      <li><a href="https://drive.google.com/drive/folders/1hTeHzZcui2ka_rNJLIykbUd335Rxvpkv?usp=drive_link">UAS (Abdul Wahhab)</a></li>
    </ul>
  </ul>
</div>

<div id="tim pengajar" class="section">
<h2>Tahun Ajaran PTA 2024/25</h2>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead style="background-color: #e6f0ff;">
    <tr>
      <th style="color: black; text-align: center;">No.</th>
      <th style="color: black; text-align: center;">Kode MK</th>
      <th style="color: black; text-align: center;">Kurikulum</th>
      <th style="color: black; text-align: center;">Nama Kelas</th>
      <th style="color: black; text-align: center;">Nama Dosen</th>
      <th style="color: black; text-align: center;">Asisten</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>1.</td>
      <td>SCMA602017</td>
      <td>03.01.03.01-2020</td>
      <td>Sains Data (A)</td>
      <td>Dra. Bevina Desjwiandra Handari, M.Si., Ph.D.</td>
      <td><ul>
    <li><strong>Renzie Aditya</strong></li>
    <li><strong>Pandu Adjie</strong></li></ul></td>
    </tr>
    <tr>
      <td>2.</td>
      <td>SCMA602017</td>
      <td>03.01.03.01-2020</td>
      <td>Sains Data (B)</td>
      <td>Devvi Sarwinda, M.Kom.</td>
      <td><ul>
    <li><strong>Pandu Adjie</strong></li>
    <li><strong>Renzie Aditya</strong></li></ul></td>
    </tr>
  </tbody>
</table>

<h2>Semester Pendek 2024/25</h2>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead style="background-color: #e6f0ff;">
    <tr>
      <th style="color: black; text-align: center;">No.</th>
      <th style="color: black; text-align: center;">Kode MK</th>
      <th style="color: black; text-align: center;">Kurikulum</th>
      <th style="color: black; text-align: center;">Nama Kelas</th>
      <th style="color: black; text-align: center;">Nama Dosen</th>
      <th style="color: black; text-align: center;">Asisten</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>1.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD Layanan (A)</td>
      <td>Devvi Sarwinda, M.kom.</td>
      <td>Renzie Aditya</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD Layanan (B)</td>
      <td>Mila Novita, S.Si., M.Si.</td>
      <td>Renzie Aditya</td>
    </tr>
  </tbody>
</table>

</div>

<div id="nilai tugas" class="section">
<h2>Tahun Ajaran PTA 2024/25</h2>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead style="background-color: #e6f0ff;">
    <tr>
      <th style="color: black; text-align: center;">No.</th>
      <th style="color: black; text-align: center;">Kode MK</th>
      <th style="color: black; text-align: center;">Kurikulum</th>
      <th style="color: black; text-align: center;">Nama Kelas</th>
      <th style="color: black; text-align: center;">Nama Dosen</th>
      <th style="color: black; text-align: center;">Status</th>
      <th style="color: black; text-align: center;">Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>1.</td>
      <td>SCMA602017</td>
      <td>03.01.03.01-2020</td>
      <td>Sains Data (A)</td>
      <td>Dra. Bevina Desjwiandra Handari, M.Si., Ph.D.</td>
      <td>Published</td>
      <td><a href="Saindat-Kelas-A.html">detail</a></td>
    </tr>
    <tr>
      <td>2.</td>
      <td>SCMA602017</td>
      <td>03.01.03.01-2020</td>
      <td>Sains Data (B)</td>
      <td>Devvi Sarwinda, M.Kom.</td>
      <td>Published</td>
      <td><a href="Saindat-Kelas-B.html">detail</a></td>
    </tr>
  </tbody>
</table>
<ul>
    <li><strong>Empty</strong> artinya nilai tersebut belum dikoreksi</li>
    <li><strong>Not published</strong> artinya nilai tersebut sudah ada tetapi belum dipublikasikan di web</li>
    <li><strong>Published (Tugas x)</strong> artinya nilai tugas x sudah dipublikasikan di web</li>
    <li><strong>Published</strong> artinya semua nilai tugas sudah dipublikasikan di web</li>
</ul>

<h2>Semester Pendek 2024/25</h2>
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead style="background-color: #e6f0ff;">
    <tr>
      <th style="color: black; text-align: center;">No.</th>
      <th style="color: black; text-align: center;">Kode MK</th>
      <th style="color: black; text-align: center;">Kurikulum</th>
      <th style="color: black; text-align: center;">Nama Kelas</th>
      <th style="color: black; text-align: center;">Nama Dosen</th>
      <th style="color: black; text-align: center;">Status</th>
      <th style="color: black; text-align: center;">Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>1.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD (Layanan A)</td>
      <td>Devvi Sarwinda, M.Kom.</td>
      <td>Published</td>
      <td><a href="">detail</a></td>
    </tr>
    <tr>
      <td>2.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD (Layanan B)</td>
      <td>Mila Novita, S.Si., M.Si.</td>
      <td>Published</td>
      <td><a href="PSD-SP-B.html">detail</a></td>
    </tr>
  </tbody>
</table>
<ul>
    <li><strong>Empty</strong> artinya nilai tersebut belum dikoreksi</li>
    <li><strong>Not published</strong> artinya nilai tersebut sudah ada tetapi belum dipublikasikan di web</li>
    <li><strong>Published (Tugas x)</strong> artinya nilai tugas x sudah dipublikasikan di web</li>
    <li><strong>Published</strong> artinya semua nilai tugas sudah dipublikasikan di web</li>
</ul>

<h2>Semester Reguler 2025/26</h2>
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead style="background-color: #e6f0ff;">
    <tr>
      <th style="color: black; text-align: center;">No.</th>
      <th style="color: black; text-align: center;">Kode MK</th>
      <th style="color: black; text-align: center;">Kurikulum</th>
      <th style="color: black; text-align: center;">Nama Kelas</th>
      <th style="color: black; text-align: center;">Nama Dosen</th>
      <th style="color: black; text-align: center;">Status</th>
      <th style="color: black; text-align: center;">Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>SCMA602013</td>
      <td>04.01.03.01-2024</td>
      <td>PDB (B)</td>
      <td>Rahmi Rusin, S.Si., M.Sc., Ph.D.</td>
      <td>Empty</td>
      <td><a href="">detail</a></td>
    </tr>
    <tr>
      <td>1.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD MIPA (A)</td>
      <td>Fida Fathiyah Addini, M.Si.</td>
      <td>Empty</td>
      <td><a href="">detail</a></td>
    </tr>
    <tr>
      <td>2.</td>
      <td>SCST601001</td>
      <td>04.01.03.01-2024</td>
      <td>PSD (Layanan B)</td>
      <td>Sindy Devila, M.Si.</td>
      <td>Empty</td>
      <td><a href="">detail</a></td>
    </tr>
  </tbody>
</table>
<ul>
    <li><strong>Empty</strong> artinya nilai tersebut belum dikoreksi</li>
    <li><strong>Not published</strong> artinya nilai tersebut sudah ada tetapi belum dipublikasikan di web</li>
    <li><strong>Published (Tugas x)</strong> artinya nilai tugas x sudah dipublikasikan di web</li>
    <li><strong>Published</strong> artinya semua nilai tugas sudah dipublikasikan di web</li>
</ul>

</div>



<script>
function showSection(sectionId) {
  document.querySelectorAll('.section').forEach(sec => {
    sec.classList.remove('active');
  });
  document.getElementById(sectionId).classList.add('active');
}
</script>
