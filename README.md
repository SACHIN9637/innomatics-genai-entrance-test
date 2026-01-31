# Innomatics GenAI Entrance Test

## 📌 Overview
This repository contains my submission for the **Innomatics Research Labs – Advanced GenAI Internship Entrance Test**.  
The project focuses on **end-to-end data integration and analysis** by combining multiple real-world data formats and deriving meaningful insights using Python.

---

## 📂 Datasets Used
The project uses three different datasets to simulate real-world systems:

1. **orders.csv**  
   - Transactional order-level data  

2. **users.json**  
   - User master data including membership details  

3. **restaurants.sql**  
   - Restaurant master data containing cuisine and rating information  

---

## 🔄 Data Integration Process
- Loaded data from **CSV**, **JSON**, and **SQL** formats
- Performed **LEFT JOIN operations** to retain all orders
- Join keys used:
  - `user_id` → Orders ↔ Users
  - `restaurant_id` → Orders ↔ Restaurants
- Created a single consolidated dataset:
  - **final_food_delivery_dataset.csv**

---

## 📊 Analysis Performed
The final dataset was used to analyze:
- Order trends and revenue distribution
- Gold vs Regular membership behavior
- City-wise and cuisine-wise performance
- Average order value and high-rating restaurant performance
- Seasonal trends using quarterly revenue analysis

All Multiple Choice Questions (MCQs) and Numerical Questions were answered **strictly based on the final merged dataset**.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **SQLite**
- **Google Colab**

---



## 📁 Project Structure
├── orders.csv
├── users.json
├── restaurants.sql
├── final_food_delivery_dataset.csv
├── Food_Delivery_Hackathon.ipynb
└── README.md
