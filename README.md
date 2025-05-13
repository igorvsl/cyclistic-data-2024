# 🚲 Cyclistic Data Analysis 2024

Exploratory data analysis and insights generation using trip data from Cyclistic, a fictional bike-share company based in Chicago.

## 📊 Project Objective

Analyze usage patterns between **casual riders and annual members** to provide data-driven recommendations for converting casual users into members.

---

## 🗂️ About the Data

- **Source**: [Kaggle - Cyclistic Data 2024](https://www.kaggle.com/datasets/igorvsl/cyclistic-data-2024)
- **Format**: Monthly `.csv` files
- **Key fields**:
  - `ride_id`, `rideable_type`, `started_at`, `ended_at`
  - `start_station_name`, `end_station_name`
  - `member_casual`: user type

---

## 🔍 Analysis Workflow

1. **Data loading and cleaning**
2. **Metric calculations**, such as:
   - Average trip duration
   - Usage by bike type
   - Most popular days and hours
3. **User behavior comparison** (members vs. casuals)
4. **Data visualizations**
5. **Insights and business recommendations**

---

## 🧰 Tools and Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Kaggle Datasets
- Git & GitHub

---

## 📌 Key Insights

- Members mostly ride on weekdays, while casual riders prefer weekends.
- Casual users tend to take longer trips on average.
- Bike type and station preferences vary significantly by user type.

---

## 📎 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/cyclistic-data-2024.git

Install required packages:

bash
Salin
Edit
pip install -r requirements.txt
Open the notebook:

bash
Salin
Edit
jupyter notebook notebooks/cyclistic_analysis.ipynb
