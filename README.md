# 🏋️ Fitness & Health Data Analytics

A Python-based data analytics project that explores fitness, health, and lifestyle patterns using **Pandas, NumPy, Matplotlib, and Seaborn**.

The project analyzes workout habits, calories burned, daily steps, BMI, heart rate, sleep, hydration, fitness levels, and activity trends.

## 🎯 Objectives

* Clean and preprocess fitness data
* Perform exploratory data analysis (EDA)
* Analyze workout and calorie patterns
* Calculate and classify BMI
* Analyze heart rate, sleep, hydration, and daily activity
* Compare fitness levels, age groups, and cities
* Perform statistical and correlation analysis
* Create data visualizations
* Develop a custom Fitness Score and user ranking
* Analyze activity trends over time

## 🗂️ Dataset

The dataset contains **520 cleaned activity records** with information including:

* Age, gender, height, and weight
* Workout type and duration
* Calories burned
* Steps and heart rate
* Sleep and water intake
* Daily calorie intake
* Workout frequency
* Fitness level
* City and activity date

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Analysis Performed

The project covers:

* User & workout analysis
* Calorie analysis
* BMI analysis
* Heart-rate analysis
* Sleep & recovery analysis
* Water intake analysis
* Steps & daily activity
* Fitness-level analysis
* City & age-group analysis
* Advanced filtering
* Statistical analysis
* Correlation analysis
* Date-based trend analysis

## 🏆 Fitness Performance Ranking

A custom **Fitness Score (0–100)** is calculated using:

* Calories Burned
* Steps
* Workout Duration
* Workout Frequency
* Sleep Hours

Users are ranked according to their average Fitness Score.

## 📈 Visualizations

The project generates **12 visualizations**, including:

* Workout distribution
* Calories by workout type
* Steps distribution
* BMI distribution
* Calories by fitness level
* Sleep by fitness level
* Heart-rate distribution
* Calories vs. workout duration
* Steps vs. calories
* Fitness-level distribution
* Age-group distribution
* Correlation heatmap

All charts are available in the `charts/` directory.

## 📁 Project Structure

```text
Fitness_Health_Data_Analytics/
│
├── Fitness_Health_Analytics.ipynb
├── fitness_health_dataset.csv
├── cleaned_fitness_health_data.csv
├── analyzed_fitness_health_data.csv
├── README.md
│
├── charts/
│   └── 12 visualization files
│
└── results/
    ├── fitness_summary.csv
    ├── fitness_performance_ranking.csv
    ├── monthly_activity_analysis.csv
    ├── day_of_week_analysis.csv
    └── summary_report.txt
```

## ▶️ How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the notebook:

```bash
jupyter notebook
```

Then run `Fitness_Health_Analytics.ipynb` sequentially.

## 📦 Outputs

The project produces:

* Cleaned and analyzed datasets
* 12 data visualizations
* Fitness performance rankings
* Statistical and correlation results
* Monthly and date-based analysis
* Summary reports

---

**Built with Python for practical fitness and health data analytics.**
