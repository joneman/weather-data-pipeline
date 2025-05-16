
# 🌍 Weather Data Processing Pipeline

## 📌 Overview
This project is designed to **ingest, clean, transform, and analyze weather data** using Python (Pandas & NumPy). The pipeline ensures data consistency, handles missing values intelligently, and generates structured output files.

---
## 🚀 **Step-by-Step Instructions to Run the Pipeline Locally**

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR_USERNAME/weather-data-pipeline.git
cd weather-data-pipeline
2️⃣ Install Dependencies
bash
pip install -r requirements.txt
3️⃣ Run the Data Processing Script
bash
python ingest_clean_transform.py
4️⃣ Outputs
After execution, the following files will be saved in the outputs/ folder:

transformed_weather_data.csv (Processed dataset)

weather_report.txt (Top 5 hottest cities)

average_temperature_chart.png (Bonus visualization)

📝 Approach & Challenges
🔹 Data Ingestion
Loaded the CSV file and checked for inconsistencies.

Standardized column formats for easier analysis.

🔹 Handling Missing Values
Applied city-specific imputation for temperature data.

Used forward-fill/backward-fill for missing dates.

Applied trend-based interpolation for missing values.

🔹 Data Transformation
Converted temperatures to Fahrenheit (F = C × 9/5 + 32).

Filtered out "Unknown" weather conditions for better accuracy.

🔹 Challenges Faced
Initial inconsistencies in date formatting.

Handling large gaps in temperature data required multiple approaches.

Cleaning and filtering "Unknown" values without biasing results.

📊 Sample Output & Visualizations
Top 5 Cities with Highest Average Temperature
City	Avg. Temperature (°C)
Tokyo	15.2
New York	12.4
London	10.8
Temperature Distribution:

⚙ Dependencies
txt
pandas
numpy
matplotlib
seaborn
scikit-learn
Install them using:

bash
pip install -r requirements.txt
🔥 Authors
Yohannes – Data Engineering Intern Candidate
