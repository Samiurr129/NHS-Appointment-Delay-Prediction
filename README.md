# NHS Appointment Delay Prediction

## 🚀 Project Overview

This project aims to predict NHS appointment delays using **time-series forecasting models**. The goal is to **reduce patient wait times** and **optimize hospital schedules** using data-driven insights.

## 📌 Key Features

- **Data Cleaning & Preprocessing**: Handling missing values, date formatting, and outlier detection.
- **Machine Learning Models**: ARIMA, Prophet, and LSTM for delay predictions.
- **Power BI Dashboard**: Interactive visualizations for decision-making.
- **Insights & Business Impact**: Data-driven recommendations for NHS efficiency.

## 📊 Dataset

The dataset contains:

- **Date**: Appointment date
- **Hospital\_Location**: Location of the hospital
- **Delay\_Minutes**: Actual delay time (in minutes)
- **Status**: Completed, Canceled, or Rescheduled
- **Age**: Patient's age

## 🔬 Machine Learning Models Used

- **ARIMA**: Best MAE: 2.41 minutes
- **Prophet**: Forecasting trends with seasonality
- **LSTM**: Deep learning for long-term patterns

## 📈 Power BI Dashboard

- **Bar Chart**: Average delay per hospital
- **Line Chart**: Weekly trends of appointment delays
- **Pie Chart**: Status distribution (Completed, Canceled, Rescheduled)
- **Scatter Plot**: Patient age vs. appointment delay

## 🛠 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/NHS-Appointment-Delay-Prediction.git
   ```
2. **Run the Python model**:
   ```bash
   jupyter notebook NHS_Delay_Analysis.ipynb
   ```
3. **Import CSV into Power BI**:
   - Open Power BI → Get Data → CSV → Load `nhs_appointment_data.csv`
   - Create visualizations using **Bar, Line, Pie, and Scatter Charts**.

## 🔥 Business Impact

✔ Optimized appointment scheduling 🔄\
✔ Reduced patient wait times ⏳\
✔ Improved healthcare resource planning 🏥\
✔ Data-driven NHS efficiency 📊

## 🤝 Contributing

Feel free to **fork** this repository and enhance the project! For major changes, please open an **issue** first to discuss what you’d like to improve.

## 📩 Contact

For queries or collaborations, connect with me on **LinkedIn**: www.linkedin.com/in/samiur-rahman-sssaaamm29


