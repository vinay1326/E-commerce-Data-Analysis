# E-commerce Dataset Analytics Project

---

## 📌 **Project Title**
**Data Analytics Project: E-commerce Dataset**

---

## 🛠️ **Description**
This project is a **data analytics project** utilizing **SQL, Python, Data Visualization**, and **Tableau** to analyze an **e-commerce dataset**. The goal is to:
- Extract meaningful insights.  
- Perform **data cleaning, analysis, and visualization**.  
- Share insights through an **interactive Tableau dashboard**.

---

## 📊 **Dataset Overview**
The dataset is sourced from **Kaggle** and stored in **SQLite** format with **11 tables**, including:
- `customers` → Customer information.  
- `geolocation` → Geographical coordinates.  
- `order_items` → Order details.  
- `order_payments` → Payment information.  
- `order_reviews` → Customer reviews.  
- `orders` → Order-level details, including dates.  
- `products` → Product-level details.  

---

##  **Data Analysis Process**
### 1️⃣ **Ask**
- Define business objectives.  
- Key questions:
    - Which products sell the most?
    - Which states have the highest sales?
    - What insights can we extract from RFM segmentation?

### 2️⃣ **Prepare**
- Loaded the dataset into **SQLite** using Python.  
- Reviewed the schema and table relationships.

### 3️⃣ **Process**
- **Data Cleaning:**  
    - Replaced **NULL values** in `order_delivered_date` with `order_estimated_delivery_date` using `COALESCE()`.  
    - Retained potential **outliers** after inspection.  
- **Feature Engineering:**  
    - Extracted **year** from `order_date` to analyze trends.

### 4️⃣ **Analyze**
- **Top 10 Best-Selling Products:**  
    - `health_beauty`, `watches_gifts`, `bed_bath_table`, `sports_leisure`, `computers_accessories`, `furniture_decor`, `housewares`, `cool_stuff`, `auto`, `garden_tools`.  
- **Top 10 States by Sales:**  
    - `SP` (São Paulo), `RJ` (Rio de Janeiro), `MG` (Minas Gerais), `RS` (Rio Grande do Sul), `PR` (Paraná), `SC` (Santa Catarina), `BA` (Bahia), `GO` (Goiás), `DF` (Distrito Federal), `PE` (Pernambuco).  
- **RFM Segmentation:**  
    - **"Should Not Lose" Segment:** High-value but inactive customers.  
    - **"Champion Customers":** Highly valuable and consistent buyers.  

### 5️⃣ **Share**
- Created an **interactive Tableau dashboard**:
    - Sales by product category and state.  
    - Yearly sales trends.  
    - RFM segmentation insights.  

---

## 📈 **Technologies Used**
- **SQL** → Data extraction and transformation.  
- **Python** → Data processing and analysis.  
- **Tableau** → Dashboard visualization.  
- **SQLite** → Database management.  

---



---


---

