<h1 align="center">🏨 Hotel Reservation Cancellation Analysis</h1>
<p align="center">
  A comprehensive data analysis project examining hotel booking cancellation patterns and providing strategic recommendations to optimize revenue and reduce cancellation rates.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" />
  <img src="https://img.shields.io/badge/Status-Complete-success.svg" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
  <img src="https://img.shields.io/badge/Analysis-EDA-orange.svg" />
</p>

---

## 🧠 Project Description

This project analyzes hotel reservation data from **City Hotel** and **Resort Hotel** between 2015 and 2017 to understand the factors contributing to booking cancellations. With a **37% cancellation rate** (~46,000 out of 119,000 bookings), the analysis uncovers actionable insights aimed at reducing cancellations and boosting revenue.

---

## 📌 Features

- 📊 Exploratory Data Analysis (EDA)
- 📈 Visualizations with Seaborn and Matplotlib
- 🧼 Data cleaning and preprocessing
- 📉 Correlation analysis between cancellation and pricing/lead time
- 🌍 Country-wise and seasonal cancellation analysis
- 🧠 Strategic business recommendations

---
---

## 🖼️ Dashboard Preview

Below is a snapshot of the interactive dashboard generated during the analysis:

<p align="center">
  <img src="Screenshot 140529.png" alt="Hotel Booking Dashboard" width="700"/>
</p>

## 📁 Dataset

- **Source**: [Hotel Booking Demand on Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Time Period**: 2015–2017
- **Total Bookings**: ~119,000
- **Columns**:
  - `hotel`, `is_canceled`, `lead_time`, `arrival_date`, `adr`, `market_segment`, `country`, `booking_changes`, etc.

> ⚠️ The dataset is **not included** in the repository due to size/privacy. You can download it from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plots
- **Jupyter Notebook** – Interactive analysis

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have:
- Python 3.8+ installed
- pip (Python package installer)
- Jupyter Notebook (recommended)

### 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/hotel-cancellation-analysis.git

# Navigate into the project folder
cd hotel-cancellation-analysis

# (Optional) Create and activate a virtual environment
python -m venv hotel_analysis_env

# Windows
hotel_analysis_env\Scripts\activate

# macOS/Linux
source hotel_analysis_env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the analysis
jupyter notebook
# or
python hotel_analysis.py
