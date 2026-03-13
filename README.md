# 📊 Student Performance Prediction Dashboard

An **interactive data analytics and machine learning dashboard** built using **Python and Streamlit** to analyze and predict student academic performance.  
The application provides **visual insights into student data** and allows users to **predict GPA based on academic and behavioral factors**.

---

# 🚀 Overview

The **Student Performance Prediction Dashboard** helps educators, researchers, and students explore patterns in academic performance.  
Using **data visualization and machine learning**, the dashboard highlights relationships between study habits, attendance, and subject scores with overall GPA.

Users can interact with visual analytics and generate **real-time GPA predictions** based on input features.

---

# ✨ Features

## 📊 Data Visualization
Interactive charts to explore student performance trends:

- **GPA Distribution by Major** – Understand GPA variation across different majors.
- **Average Scores by Major** – Compare subject performance among majors.
- **Study Hours vs GPA** – Analyze how study habits influence academic performance.
- **Attendance vs GPA** – Observe the impact of attendance on GPA.
- **Correlation Heatmap** – Identify relationships between different academic variables.

---

## 🎯 GPA Prediction System

A **machine learning model** predicts student GPA using the following inputs:

- Math Score  
- Science Score  
- English Score  
- Attendance Rate  
- Study Hours per Week  

The prediction is powered by **Linear Regression from Scikit-learn**, enabling quick and interpretable results.

---

# 🛠 Tech Stack

| Category | Technologies |
|--------|-------------|
| **Programming Language** | Python |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn (Linear Regression) |
| **Visualization** | Plotly (Express & Graph Objects) |
| **Dashboard Framework** | Streamlit |

---

# 📂 Project Structure

Workshop/
│
├── Project.ipynb # Data exploration and experimentation
├── class.ipynb # Additional analysis and ML experiments
├── student_dashboard.py # Streamlit dashboard application
└── student_performance_data.csv # Dataset used for analysis and prediction


---

# ⚙️ Installation

Clone the repository and install required dependencies.

```bash
git clone https://github.com/your-username/student-performance-dashboard.git
cd student-performance-dashboard
pip install -r requirements.txt


▶️ Running the Dashboard
Run the Streamlit application:
streamlit run student_dashboard.py
The dashboard will open automatically in your browser.


📈 Future Improvements
Add advanced ML models (Random Forest, XGBoost).
Implement model evaluation metrics dashboard.
Add student performance clustering.
Integrate real-time dataset uploads.
Deploy the dashboard using Streamlit Cloud or Docker.
📌 Use Cases
Educational data analysis
Academic performance monitoring
Student behavior analysis
Predictive analytics in education
🤝 Contribution
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.



