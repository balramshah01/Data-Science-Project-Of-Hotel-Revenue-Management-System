# 🏨 Hotel Revenue Management System

---

## 📄 Project Report (Google Sheets)
[![View Report](https://img.shields.io/badge/Google%20Sheets-View%20Report-brightgreen?style=for-the-badge&logo=google-sheets)](https://docs.google.com/spreadsheets/d/1g8DgmksUS14JKIfz7mcBXZr_1OhQry77/edit?usp=sharing&ouid=113295682545698250826&rtpof=true&sd=true)


An interactive **Streamlit-based dashboard** for visualizing hotel booking trends and predicting revenue using Machine Learning (XGBoost). This project empowers hoteliers and analysts to make smarter, data-driven decisions with real-time insights.

---

## 🚀 Live App

👉 [Launch the Hotel Revenue WebApp]( https://balramshah-hotel-webapp.streamlit.app)

---


## 📌 Project Summary

This dashboard was developed as part of an internship at **HCL Technologies**. It allows users to:

- Visualize hotel booking data through interactive charts
- Track KPIs like revenue, lead time, ADR, and cancellations
- Input booking details to **predict expected revenue** using an ML model
- Download filtered data for further analysis

---

## 📷 Screenshots

### 📊 Dashboard Overview
![Screenshot 2025-04-28 154022](https://github.com/user-attachments/assets/b11f6dc9-c92a-49fa-8248-28834c34c1d6)


### 🧮 Prediction Section
![Screenshot 2025-04-28 154704](https://github.com/user-attachments/assets/1a3a735d-7aea-4414-b806-c89ce3f2db2f)

---

## 💡 Features

- ✅ **Streamlit-powered** user interface
- 📈 Interactive charts using **Plotly** and **Seaborn**
- 🧠 Revenue prediction via **XGBoost ML model**
- 🎛️ Filters by arrival date, customer type, market segment, and more
- 📥 CSV download option for filtered datasets

---

## 🔍 Machine Learning Model

- Trained using the cleaned hotel dataset
- Features include:
  - Lead time
  - Room type
  - Customer type
  - Market segment
  - Booking changes and special requests
- Model Used: `XGBoost Regressor`
- File: `xgb_hotel_model.pkl`

---

