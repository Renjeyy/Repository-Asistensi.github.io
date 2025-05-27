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
  <h3>Area Of Expertise</h3>
  <li><strong>Deep Leaning</strong></li>
  <li><strong>Neural Networks</strong></li>
  <li><strong>Image Processing</strong></li>
  <li><strong>Differential Equations</strong></li>
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
    <li><strong>Aditya, R., Hutapea, D., Sukarno, P., & Rabani, H. F. (Ongoing).Text Modelling and Sentiment on Indonesia’s Budget Efficiency in 2025.</strong>
    <ul>
        <li>Description: I am currently conducting a research on text modeling and sentiment analysis utilizing Natural Language Processing (NLP) techniques, specifically IndoBERT and Latent Discriminant Analysis. The objective of this study was to identify the most frequently discussed topics and keywords concerning Indonesia’s budget efficiency for the year 2025.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong>Aditya, R., Hutapea, D., Sukarno, P., Al Farizi, B., & Muhammad, E. (2024). Accuracy Analysis Of Neural Network Models For Fraud Prediction In Car Insurance Claims</strong>
    <ul>
        <li>Description: I carried out an in-depth research project focused on analyzing a deep learning model specifically designed for predicting
fraudulent activities in car insurance claims. This involved exploring and evaluating their effectiveness in identifying
patterns of fraud within large datasets of claims. The goal was to enhance the accuracy of fraud detection systems and
contribute to the overall integrity of the insurance industry.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong>Aditya, R., Hutapea, D., Muhammad, E., Sukarno, P., Damara, B., Jilan, M., & Wahhab, A. (2024). Model Matematika Untuk Mengestimasi Waktu Maksimal Penerjung Payung Militer Membuka Parasut</strong> 
    <ul>
        <li>Description: Conducted a research on creating a Mathematical Model to Estimate the Maximum Time for a Soldier to Open a
Parachute.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li>A<strong>ditya, R., Hutapea, D. N., Wahhab, A., Wicaksono, M. J., Muhammad, E., & Sukarno, P. A. (2024).Penjadwalan Ruangan Kuliah di Departemen Matematika dengan Pendekatan Metode Metaheuristik</strong> 
    <ul>
      <li>Description: Conducted a research on scheduling problems at the Departement of Mathematics, FMIPA UI, using Simulated
Annealing as the metaheuristic method..</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., & Sukarno, P. A. (2023).Analisis Jaringan Sosial Facebook Untuk Menentukan Aktor Penting Menggunakan Betweenness Centrality</strong> 
    <ul>
        <li>Description: Co-authored a research paper on analyzing the social network of Facebook users using parallel computing and graph
theory.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
  </ul>
</div>

<!-- Publication Section -->
<div id="publication" class="section">
  <h2>Publication</h2>
  <ul>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., & Rusin, R. (2025).Predator-Prey Model Incorporating Self Limiting and Holling Type II and Its Application Industrial Factory Games</strong>
    <ul>
        <li>Description: (Ongoing) </li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong>Aditya, R., Salamah, S., & Rabani, H. (2024). Forecasting East Jakarta’s Pollution Using SARIMA</strong>
    <ul>
        <li>Description: I collaborated with a team to author a research paper that delves into forecasting air pollution levels in East Jakarta. This study employed the Seasonal Autoregressive Integrated Moving Average (SARIMA) model and was conducted over a five-month period, from August to December 2024. The research aimed to enhance our understanding of air quality trends in the region, providing valuable insights for policymakers and environmental agencies. This research was published on Research Gate</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong>Aditya, R., Hutapea, D. N., Sitindaon, F. A., Wahhab,A., & Sukarno, P. A. (2024).Penerapan Teori Grup dalam Permainan Rubic’s Cube berukuran 3 × 3 × 3</strong>
    <ul>
        <li>Description: I conducted an in-depth research project focused on solving a 3 × 3 × 3 Rubik’s Cube by applying the principles of group theory from abstract algebra. This study explored the mathematical structures and operations that govern the permutations of the cube’s faces, allowing for a systematic approach to finding solutions and understanding the underlying mechanics of this popular puzzle.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
    <li><strong> Aditya, R., Hutapea, D. N., Rabani, H. F., Santoso, A. S., Ilmiyah, F. F., Makarim, D. A., & Hakim, N. S. (2024).Harnessing Technology for Climate Action : LSTM Modeling of Agricultural Emissions for SDGs 13</strong>
    <ul>
        <li>Description: I conducted a detailed research project focused on predicting gas emissions utilizing Long Short-Term Memory (LSTM) neural networks applied to time series data. This approach enables the analysis of temporal dependencies in emission levels, allowing for more accurate forecasting based on historical trends and patterns in the data.</li>
        <li><a ">View Project</a></li>
      </ul>
    </li>
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
