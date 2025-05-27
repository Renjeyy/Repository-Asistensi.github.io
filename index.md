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
I am currently pursuing my undergraduate studies in the Department of Mathematics at Universitas Indonesia, where I have engaged in a diverse and intellectually stimulating academic environment. Throughout my educational experience, I have participated in various activities that have enhanced both my mathematical expertise and essential soft skills. My areas of specialization include Deep Learning, Neural Networks, Unstructured Data Analysis, and Biomedical Image Processing.

One of my notable involvements has been with the Mathematics Department Student Association and BEM FMIPA UI 2024, where I have taken part in organizing events aimed at fostering community engagement and promoting academic excellence among students. Additionally, my participation in the Student Executive Board has afforded me the opportunity to engage in decision-making processes that influence student life and initiatives within the university.

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
    <li><strong>Tes</strong> – Menggunakan CNN untuk segmentasi citra medis.</li>
    <li><strong>Unstructured Data Classification</strong> – Text classification dengan BERT.</li>
    <li><strong>Data Visualizer Dashboard</strong> – Visualisasi interaktif menggunakan Dash & Plotly.</li>
  </ul>
</div>

<!-- Publication Section -->
<div id="publication" class="section">
  <h2>Publication</h2>
  <ul>
    <li><em>"Neural Networks for Biomedical Imaging"</em>, submitted to Journal of Medical AI, 2024.</li>
    <li><em>"Unstructured Data Analysis for Academic Profiling"</em>, FMIPA Research Day, 2023.</li>
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
