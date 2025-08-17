# 🚖 Uber Ride Data Analysis  

## 📌 Project Overview  
This project analyzes Uber ride data to uncover insights about ride behavior, cancellations, customer/driver ratings, and revenue trends.  

The analysis demonstrates skills in **data cleaning, feature engineering, exploratory data analysis (EDA), and visualization** using Python.  

---

## 📊 Dataset  
- **Source:** Kaggle 
- **Rows:** 150000
- **Columns:** 20 (Date, Time, Booking ID, Booking Status, Customer ID, Vehicle Type, Pickup Location, Drop Location, Avg VTAT, Avg CTAT, Cancelled Rides, Ratings, Payment Method, etc.)  

---

## 🛠️ Tools & Libraries  
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn / Plotly  

---

## 🔑 Features / Steps  
1. **Data Cleaning**  
   - Handled missing values  
   - Converted `Date` & `Time` into `datetime`  
   - Standardized columns  

2. **Feature Engineering**  
   - Extracted `hour`, `day_of_week`, `month`  
   - Created flags for `is_peak_hour`, `is_weekend`  
   - Grouped booking status into Completed / Cancelled / Incomplete  

3. **Exploratory Data Analysis (EDA)**  
   - Ride trends over time  
   - Cancellation patterns (customer vs driver)  
   - Ratings distribution (driver & customer)  
   - Revenue by vehicle type and location  
   - Impact of ride distance on ratings  

4. **Visualizations**  
   - Line chart: Bookings over time  
   - Heatmap: Hour of day vs Day of week (peak hours)  
   - Bar chart: Cancellation reasons  
   - Pie chart: Payment method usage  

---

## 📈 Key Insights  
- 🚗 Most bookings happen during **morning and evening commute hours (7–9 AM, 6–8 PM)**  
- ❌ **Customer cancellations** are more frequent than driver cancellations, mostly due to long wait times  
- ⭐ **Driver ratings** are generally higher than **customer ratings**  
- 💰 `<Vehicle Type>` contributes the highest revenue, while `<Another Vehicle Type>` has the most cancellations  
- 📍 Top pickup locations: `<list them if available>`  

---


## 🚀 Next Steps  
- Build a **prediction model** (ML) to forecast cancellations or ratings  
- Create a **dashboard** (Power BI / Plotly Dash) for real-time insights  

---

## 📬 Contact  
👤 **Nabin Kumar Rouniyar**  
🔗 [LinkedIn](https://www.linkedin.com/in/nabin-rouniyar-86682726a/) | [GitHub](https://github.com/Nabin68)  
