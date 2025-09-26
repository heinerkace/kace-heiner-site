<style>
.projects-container {
  display: flex;
  flex-direction: column; /* vertical stacking */
  gap: 25px;
  align-items: flex-start;
}

.project-card {
  background-color: #2b2b2b; /* dark card background */
  border-radius: 15px;
  padding: 25px;
  width: 90%; /* wider cards */
  max-width: 800px;
  text-align: left;
  box-shadow: 0 4px 6px rgba(0,0,0,0.5);
  transition: transform 0.3s, box-shadow 0.3s, background-color 0.3s;
  cursor: pointer;
  color: #e0e0e0; /* light text for readability */
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 15px rgba(0,0,0,0.7);
  background-color: #3a3a3a; /* slightly lighter on hover */
}

.project-icon {
  font-size: 40px;
  margin-bottom: 15px;
  color: #4CAF50; /* keep icons colorful */
}

.project-title {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 8px;
}

.project-desc {
  font-size: 15px;
  color: #ccc;
  margin-bottom: 8px;
}

.project-tech {
  font-size: 13px;
  color: #aaa;
  font-style: italic;
}
</style>

<div class="projects-container">

  <div class="project-card" onclick="window.open('https://github.com/heinerkace/stock-portfolio-etl', '_blank')">
    <div class="project-icon">📈</div>
    <div class="project-title">Stock Portfolio ETL</div>
    <div class="project-desc">ETL pipeline to extract, transform, and load stock and client data. Automates portfolio summaries.</div>
    <div class="project-tech">Tech: Python, SQLite, pandas, matplotlib</div>
  </div>

  <div class="project-card" onclick="window.open('https://github.com/heinerkace/GoodStart/blob/main/BasketballNeuralNetwork.ipynb', '_blank')">
    <div class="project-icon">🏀</div>
    <div class="project-title">Basketball Neural Network</div>
    <div class="project-desc">Python MLPRegressor Neural Network for player classification.</div>
    <div class="project-tech">Tech: Python, MLPRegressor, ML</div>
  </div>

  <div class="project-card" onclick="window.open('https://github.com/heinerkace/GoodStart/blob/main/RegressionModel.ipynb', '_blank')">
    <div class="project-icon">💰</div>
    <div class="project-title">Ecommerce Analytics</div>
    <div class="project-desc">Regression Model to predict yearly spend.</div>
    <div class="project-tech">Tech: Python, MatPlotLib, Seaborn</div>
  </div>

</div>
