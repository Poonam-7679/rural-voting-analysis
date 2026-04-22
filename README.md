
# 🗳️ Rural Voting Participation Analysis

## 📌 Problem Statement
Understanding voter turnout patterns in rural areas is crucial for improving democratic participation. This project analyzes factors like literacy and population to identify what drives higher or lower turnout.

## 📊 Dataset
- 6 villages with population, votes cast, literacy rate
- Created synthetic data representing real rural patterns

## ⚙️ Tech Stack
- Python (Pandas, Matplotlib, Scikit-learn)
- Jupyter Notebook
- GitHub

## 🔍 Analysis Performed
- Calculated turnout percentage for each village
- Compared high vs low participation regions
- Identified literacy as key factor

## 🤖 Machine Learning
- **Model:** Random Forest Regressor
- **Features Used:** Literacy Rate, Population
- **Target Variable:** Voter Turnout (%)
- **Performance:** R² Score = 0.85

The model predicts voter turnout based on socio-economic factors and helps identify low-participation regions.

## 💡 Key Insights
- Higher literacy rate leads to increased voter participation
- Smaller villages show more consistent turnout behavior
- Awareness plays a bigger role than population size

## 📈 Results
- Village F: Highest turnout (85.0%) - High literacy
- Village E: Lowest turnout (27.3%) - Low literacy
- Literacy rate correlates strongly with voting behavior

## 📸 Output
![Turnout Chart](turnout_chart.png)

## 🚀 Future Improvements
- Add real government dataset
- Deploy interactive dashboard
- Integrate with QR-based voting system

## 📁 How to Run
```bash
pip install pandas matplotlib scikit-learn
jupyter notebook analysis.ipynb

