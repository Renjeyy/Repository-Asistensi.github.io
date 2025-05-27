<style>
.navbar {
  display: flex;
  justify-content: center;
  background-color: #f5f5f5;
  padding: 10px;
  margin-bottom: 20px;
  flex-wrap: wrap;
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
}
.section.active {
  display: block;
}
</style>

<div class="navbar">
  <a onclick="showSection('cover')">Cover</a>
  <a onclick="showSection('soal')">Soal Responsi</a>
  <a onclick="showSection('teaching')">Teaching</a>
  <a onclick="showSection('project')">Project</a>
  <a onclick="showSection('publication')">Publication</a>
</div>

<!-- Cover Section -->
<div id="cover" class="section active">
  <h2>Cover</h2>
  <h3>Introduction</h3>
  <p>
I am currently pursuing my undergraduate studies in the Department of Mathematics at Universitas Indonesia, where I have engaged in a diverse and intellectually stimulating academic environment. Throughout my educational experience, I have participated in various activities that have enhanced both my mathematical expertise and essential soft skills. My areas of specialization include Deep Learning, Neural Networks, Unstructured Data Analysis, and Biomedical Image Processing. </p>
<p>
One of my notable involvements has been with the Mathematics Department Student Association and BEM FMIPA UI 2024, where I have taken part in organizing events aimed at fostering community engagement and promoting academic excellence among students. Additionally, my participation in the Student Executive Board has afforded me the opportunity to engage in decision-making processes that influence student life and initiatives within the university.</p>
<p>
Furthermore, I have served as a teaching assistant for several courses, including Ordinary Differential Equations, Data Science, Analytical Geometry, and Introduction to Data Science. In this capacity, I have had the privilege of guiding my peers in their academic endeavors by providing support during lectures, facilitating discussion groups, and assisting with coursework. These experiences have significantly contributed to my academic and professional development, allowing me to refine my leadership, communication, and teamwork skills, which I believe are essential for my future pursuits in the field of mathematics.
  </p>
</div>

<!-- Soal Responsi Section -->
<div id="soal" class="section">
  <h2>Soal Responsi</h2>

  <h3>Persamaan Diferensial Biasa</h3>
  <ul>
    <li><a href="#">Soal 1</a></li>
    <li><a href="#">Soal 2</a></li>
  </ul>

  <h3>Pengantar Data Science</h3>
  <ul>
    <li><a href="#">Soal 1</a></li>
  </ul>

  <h3>Sains Data</h3>
  <ul>
    <li><a href="#">Soal 1</a></li>
  </ul>
</div>

<!-- Teaching Section -->
<div id="teaching" class="section">
  <h2>Teaching</h2>
  <p>
    (Insert Tabel)
  </p>
</div>

<!-- Project Section -->
<div id="project" class="section">
  <h2>Project</h2>
  <ul>
    <li><strong>Aditya, R., Hutapea, D., Sukarno, P., & Rabani, H. F. (Ongoing). Text Modelling and Sentiment on Indonesia’s Budget Efficiency in 2025.</strong></li>
    <li><strong>Aditya, R., Hutapea, D., Sukarno, P., Al Farizi, B., & Muhammad, E. (2024). Accuracy Analysis Of Neural Network Models For Fraud Prediction In Car Insurance Claims</strong></li>
    <li><strong>Aditya, R., Hutapea, D., Muhammad, E., Sukarno, P., Damara, B., Jilan, M., & Wahhab, A. (2024). Model Matematika Untuk Mengestimasi Waktu Maksimal Penerjung Payung Militer Membuka Parasut</strong> </li>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., Wahhab, A., Wicaksono, M. J., Muhammad, E., & Sukarno, P. A. (2024). Penjadwalan Ruangan Kuliah di Departemen Matematika dengan Pendekatan Metode Metaheuristik</strong> </li>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., & Sukarno, P. A. (2023). Analisis Jaringan Sosial Facebook Untuk Menentukan Aktor Penting Menggunakan Betweenness Centrality</strong> </li>
  </ul>
</div>

<!-- Publication Section -->
<div id="publication" class="section">
  <h2>Publication</h2>
  <ul>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., & Rusin, R. (2025). Predator-Prey Model Incorporating Self Limiting and Holling Type II and Its Application Industrial Factory Games</strong></li>
    <li><strong>Aditya, R., Salamah, S., & Rabani, H. (2024). Forecasting East Jakarta’s Pollution Using SARIMA</strong></li>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., Wahhab,A., & Sukarno, P. A. (2024). Penerapan Teori Grup dalam Permainan Rubic’s Cube berukuran 3 × 3 × 3</strong></li>
    <li><strong>Aditya, R., Hutapea, D. N., Rabani, H. F., Santoso, A. S., Ilmiyah, F. F., Makarim, D. A., & Hakim, N. S. (2024). Harnessing Technology for Climate Action : LSTM Modeling of Agricultural Emissions for SDGs 13</strong></li>
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
