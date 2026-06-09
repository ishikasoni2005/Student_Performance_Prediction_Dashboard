# 📊 Student Performance Prediction Dashboard

An **interactive data analytics and ML dashboard** built with Python and Streamlit to analyze and predict student academic performance.

Helps educators, researchers, and students explore patterns in academic data — visualizing relationships between study habits, attendance, subject scores, and overall GPA, with real-time GPA prediction.

---

## ✨ Features

### 📊 Data Visualization
- **GPA Distribution by Major** — GPA variation across different majors
- **Average Scores by Major** — Subject performance comparison across majors
- **Study Hours vs GPA** — Impact of study habits on academic performance
- **Attendance vs GPA** — Relationship between attendance and GPA
- **Correlation Heatmap** — Relationships between all academic variables

### 🎯 GPA Prediction
ML model predicts student GPA based on:
- Math Score, Science Score, English Score
- Attendance Rate
- Study Hours per Week

Powered by **Linear Regression (Scikit-learn)** for quick, interpretable predictions.

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Dashboard | Streamlit |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn (Linear Regression) |
| Visualization | Plotly (Express & Graph Objects) |

---

## 📂 Project Structure

```
student-performance-dashboard/
│
├── student_dashboard.py          # Main Streamlit application
├── student_performance_data.csv  # Dataset
├── Project.ipynb                 # Data exploration & experimentation
├── class.ipynb                   # Additional ML experiments
└── requirements.txt
```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/student-performance-dashboard.git
cd student-performance-dashboard
pip install -r requirements.txt
```

Run the dashboard:

```bash
streamlit run student_dashboard.py
```

Opens automatically in your browser.

---

## 🔮 Future Improvements

- [ ] Advanced ML models (Random Forest, XGBoost)
- [ ] Model evaluation metrics dashboard
- [ ] Student performance clustering
- [ ] Real-time dataset upload support
- [ ] Deploy via Streamlit Cloud or Docker

---

## 📌 Use Cases

- Educational data analysis
- Academic performance monitoring
- Student behavior analysis
- Predictive analytics in education
