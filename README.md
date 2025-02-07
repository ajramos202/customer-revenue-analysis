# Sales Data Analysis & Visualization

## 📌 Project Overview
This project generates a **synthetic sales dataset** using Python and the Faker library to simulate real-world sales data. The dataset is then analyzed to extract insights on customer behavior, product performance, and revenue trends. Visualizations are created using **Matplotlib** and **Seaborn** to showcase key findings.

## 🛠️ Technologies Used
- **Python** (Data Processing & Analysis)
- **pandas** (Data Manipulation)
- **Faker** (Synthetic Data Generation)
- **Matplotlib & Seaborn** (Data Visualization)
- **NumPy** (Numerical Operations)

## 📊 Dataset Description
The dataset includes the following columns:
- **Order_ID** – Unique identifier for each order
- **Customer** – Randomly generated customer name
- **Product** – One of five electronic products (Laptop, Phone, Tablet, Monitor, Desktop)
- **Quantity** – Number of units purchased
- **Price** – Randomized price between $100 - $1000
- **Discount_Applied** – Random discount (up to 20%)
- **Shipping_Address** – Fake customer shipping address
- **Shipping_Cost** – Random cost between $10 - $50
- **Total_Cost** – Final price after applying discount and adding shipping
- **Purchase_Date** – Random purchase date from the last decade
- **New_Customer** – Indicates whether the customer is new or returning
- **Payment_Method** – Payment method used (Credit Card, PayPal, Cash on Delivery)
- **Order_Status** – Order status (Pending, Processing, Shipped, Delivered, Cancelled)
- **Customer_Satisfaction** – Customer rating (Excellent, Very Good, Good, Fair, Poor)

## 🔍 Insights & Visualizations
This project explores several key questions, such as:
1. **Who spends more per order: new or returning customers?**
2. **Which products generate the highest revenue?**
3. **What is the most used payment method?**
4. **Is there a correlation between discount applied and total spending?**
5. **What is the overall customer satisfaction rating?**

### Example Visualizations:
- **Total Revenue by Product** (Bar Chart)
- **New vs. Returning Customers** (Pie Chart)
- **Impact of Discounts on Sales** (Box Plot)

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sales-data-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sales-data-analysis
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script to generate the dataset and insights:
   ```bash
   python sales_analysis.py
   ```

## 📌 Future Improvements
- Expand dataset with more realistic sales features
- Integrate SQL for querying sales data
- Apply machine learning models for sales predictions

## 📬 Contact
If you have any questions, feel free to reach out!
- **LinkedIn**: [Amanda Ramos](https://www.linkedin.com/in/ajramos202/)

