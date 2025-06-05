# 🇮🇳 India's Air Quality Prediction System

A time series forecasting project to predict India's air quality using real-world data from 2017 to 2022. The system leverages Python's data science stack and Facebook Prophet to provide accurate AQI (Air Quality Index) forecasts and trend analysis.

## 🔍 Overview

This project aims to analyze and forecast air pollution trends across Indian cities. Using historical air quality data, we clean, analyze, visualize, and predict future air pollution levels using the Prophet library by Meta. The predictions help understand seasonal patterns and inform proactive pollution control measures.

## 🎯 Features

- Historical AQI analysis for multiple cities across India.
- Time series forecasting using Facebook Prophet.
- Visual representation of predicted AQI with trend and seasonality components.
- Interactive and static visualizations for insights.
- Reproducible code for end-to-end AQI prediction pipeline.

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Plotly
  - Facebook Prophet (fbprophet)
  - Jupyter Notebook

## 📂 Project Structure
Indias-air-quality-prediction-system/
├── dataset/ # Raw and cleaned air quality data
├── air_quality_analysis.ipynb # Jupyter notebook for full analysis and prediction
├── forecast_output.png # Sample output graph
├── README.md # Project documentation


## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.x installed, along with the required libraries:

```bash
pip install pandas numpy matplotlib plotly prophet jupyter
```
Note: For some environments, you may need to install prophet as pip install prophet instead of fbprophet.

1. Clone the Repositary:
   ```bash
   git clone https://github.com/Chetansonawane7/Indias-air-quality-prediction-system.git
2. Navigate to the Project Folder:
   ```bash
   cd Indias-air-quality-prediction-system
3. Open and Run the Notebook:
   ```bash
   jupyter notebook air_quality_analysis.ipynb

🧠 How It Works
Load and clean the raw AQI dataset from Kaggle.

Preprocess data for Prophet: format datetime columns, handle missing values.

Use Facebook Prophet to model trends, seasonality, and holidays.

Plot forecasts and evaluate model performance.

💡 Use Cases
Academic or research projects focused on environmental data.

Public health insights and air pollution monitoring.

Policy guidance for pollution control initiatives.

🤝 Contributing
Contributions are welcome!

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -m 'Add your feature').

Push to the branch (git push origin feature/your-feature).

Open a Pull Request.

📄 License
This project is licensed under the MIT License.

📬 Contact
For queries or collaboration, feel free to reach out at: sonawanechetan847@gmail.com
