<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhishek Pandey | Data Scientist & Analyst</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #141e30, #243b55);
      color: #f8f8f8;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 4rem 1rem 2rem;
      background: #0f2027;
    }
    header h1 {
      font-size: 3.5rem;
      color: #38bdf8;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.2rem;
      color: #cfd9df;
    }
    section {
      padding: 3rem 5%;
      animation: fadeIn 1.5s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-size: 2rem;
      color: #ffd369;
    }
    .skills, .projects, .connect {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: rgba(255,255,255,0.07);
      border: 1px solid rgba(255,255,255,0.15);
      border-radius: 16px;
      padding: 1.5rem;
      transition: all 0.3s;
      backdrop-filter: blur(10px);
    }
    .card:hover {
      transform: translateY(-5px) scale(1.02);
      box-shadow: 0 0 15px rgba(255,255,255,0.1);
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.5rem;
      background: #ff6b81;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    .btn:hover {
      background: #ff4757;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      font-size: 0.9rem;
      background: #0a0f1e;
      color: #bbb;
    }
  </style>
</head>
<body>
  <header>
    <h1><i class="fas fa-laptop-code"></i> Abhishek Pandey</h1>
    <p>Data Scientist | Data Analyst | ML Engineer | AI Enthusiast</p>
  </header>

  <section>
    <h2>🚀 Expertise & Skills</h2>
    <div class="skills">
      <div class="card">Exploratory Data Analysis (EDA)</div>
      <div class="card">Data Visualization (Seaborn, Plotly, Power BI, Tableau)</div>
      <div class="card">Supervised Learning (Regression, Classification)</div>
      <div class="card">Unsupervised Learning (Clustering, PCA, Dimensionality Reduction)</div>
      <div class="card">Deep Learning (TensorFlow & PyTorch)</div>
      <div class="card">Model Training & Evaluation Metrics</div>
      <div class="card">Model Deployment (Flask, Streamlit, Docker, CI/CD)</div>
      <div class="card">SQL, NoSQL, MongoDB, Redis</div>
    </div>
  </section>

  <section>
    <h2>📂 Featured Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>🎬 Netflix Hybrid Recommender</h3>
        <p>Combines NLP, collaborative & content filtering for smarter recommendations.</p>
        <a href="https://github.com/Iammanan07/HYBRID-MOVIE-RECOMMENDER-" class="btn">GitHub Repo</a>
      </div>
      <div class="card">
        <h3>📈 Weather Prediction System</h3>
        <p>Time series regression model with live weather data predictions.</p>
        <a href="https://github.com/Iammanan07/weather-prediction-system-" class="btn">GitHub Repo</a>
      </div>
      <div class="card">
        <h3>✈️ Aviation Accident EDA</h3>
        <p>Pattern analysis & visualization from global aviation crash data.</p>
        <a href="https://github.com/Iammanan07/Aviaation-accident-Analysis-EDA-" class="btn">GitHub Repo</a>
      </div>
      <div class="card">
        <h3>👥 Customer Segmentation</h3>
        <p>KMeans & PCA for business user profiling.</p>
        <a href="https://github.com/Iammanan07/Customer-segmentation-Using-K-means-Clustering" class="btn">GitHub Repo</a>
      </div>
    </div>
  </section>

  <section>
    <h2>🔗 Connect with Me</h2>
    <div class="connect">
      <div class="card"><a href="mailto:Pandeymanan637@gmail.com"><i class="fas fa-envelope"></i> Email</a></div>
      <div class="card"><a href="https://www.linkedin.com/in/abhishek-pandey-voBGb/"><i class="fab fa-linkedin"></i> LinkedIn</a></div>
      <div class="card"><a href="https://shorturl.at/mGZoO"><i class="fab fa-medium"></i> Medium Articles</a></div>
    </div>
  </section>

  <footer>
    🚀 Always building. Always learning. Made with ❤️ by Abhishek Pandey
    <br/>
    👀 Profile Views Badge | 🌐 Live GitHub Skyline | ⚡ Add yours here
  </footer>
</body>
</html>
