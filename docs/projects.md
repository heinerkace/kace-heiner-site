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

  <div class="project-card" onclick="window.open('https://github.com/kaceheiner/stock-etl', '_blank')">
    <div class="project-icon">📈</div>
    <div class="project-title">Stock Portfolio ETL</div>
    <div class="project-desc">ETL pipeline to extract, transform, and load stock and client data. Automates portfolio summaries.</div>
    <div class="project-tech">Tech: Python, SQLite, pandas, matplotlib</div>
  </div>

  <div class="project-card" onclick="window.open('https://github.com/kaceheiner/window-detection', '_blank')">
    <div class="project-icon">🏠</div>
    <div class="project-title">Window Detection Prototype</div>
    <div class="project-desc">Computer vision project to detect and count windows from house images.</div>
    <div class="project-tech">Tech: Python, OpenCV, YOLOv8</div>
  </div>

  <div class="project-card" onclick="window.open('https://github.com/kaceheiner/finance-dashboard', '_blank')">
    <div class="project-icon">💰</div>
    <div class="project-title">Personal Finance Dashboard</div>
    <div class="project-desc">Cleaned and visualized financial data for personal budgeting.</div>
    <div class="project-tech">Tech: Python, SQL, Tableau</div>
  </div>

</div>
