# Zomato Analytics Dashboard

## 📊 Project Overview

The **Zomato Analytics Dashboard** is a data visualization project built to provide insights into food delivery performance, restaurant reviews, and customer preferences. This dashboard is intended to help stakeholders identify trends, optimize delivery operations, and improve customer satisfaction.

## 📝 Features

- Track order and delivery performance.
- Monitor restaurant reviews and customer ratings.
- Understand customer behavior and preferences.
- Visualize data using interactive charts.
- Use filters for flexible and targeted analysis.

## 🎯 Objectives

- Analyze total orders, delivery time, and order value.
- Evaluate customer satisfaction using review ratings.
- Determine cuisine popularity and discount usage.
- Empower teams with data-driven decision-making tools.

## 📈 Key Performance Indicators (KPIs)

- **Total Orders**
- **Average Delivery Time**
- **Average Order Value (AOV)**
- **Customer Satisfaction (Rating)**
- **Discount Utilization Rate**

## 📊 Visualizations

- **Total Orders Trend** (Line Chart)
- **Delivery Time Analysis** (Bar Chart)
- **Top Restaurants** (Horizontal Bar Chart)
- **Customer Ratings Distribution** (Pie/Bar Chart)
- **Cuisine Popularity** (Bar Chart)

## 🔍 Filters

- Date Range
- City/Location
- Cuisine Type
- Rating Range
- Discount Applied

## 🗂️ Datasets

- `orders.csv`: Order ID, Customer Name, Location, Restaurant Name, Cuisine, Order Date, Delivery Time, Order Amount, etc.
- `restaurants.csv`: Restaurant Name, Location, Ratings, Reviews, Cuisine.
- `reviews.csv`: Review Text, Ratings, Review Date, Customer Feedback.

## 🛠 Functional Requirements

| View | Description | Required Columns |
|------|-------------|------------------|
| Total Orders KPI | Displays total orders | Order_ID |
| Average Delivery Time KPI | Avg delivery time | Delivery_Time_Minutes, Order_ID |
| Average Order Value KPI | Avg order value | Order_Amount, Order_ID |
| Customer Satisfaction KPI | Avg customer rating | Rating, Review_Date |
| Discount Utilization KPI | % of discounted orders | Is_Discount_Applied, Order_ID |
| Total Orders Trend | Line chart | Order_Date, Order_ID, Customer_Location |
| Delivery Time | Bar chart by city | Delivery_Time_Minutes, Customer_Location |
| Top Restaurants | Revenue-based bar chart | Restaurant_Name, Order_Amount, Restaurant_Location |
| Ratings Distribution | Pie/bar chart | Rating, Order_ID |
| Cuisine Popularity | Bar chart | Cuisine, Order_ID |

## ⚙️ Non-Functional Requirements

- **Performance:** Dashboards load within 5 seconds (for ≤50,000 rows).
- **Usability:** Easy-to-use interface for all users.
- **Scalability:** Supports datasets up to 1 million rows.

## 👥 Stakeholders

- Business Analysts
- Operations Team
- Marketing Team
- Restaurant Owners

## 📅 Timeline

| Phase | Date Range |
|-------|------------|
| Requirement Gathering | [Insert Date Range] |
| Development | [Insert Date Range] |
| Testing & Feedback | [Insert Date Range] |
| Deployment | [Insert Date] |

## 🚨 Risks and Mitigation

| Risk | Mitigation |
|------|------------|
| Data inconsistency | Implement validation rules |
| Performance issues | Optimize Power BI model |
| Scope creep | Freeze requirements pre-dev |

## ✅ Approvals

| Name | Role | Approval Date |
|------|------|---------------|
| [Your Name] | Project Manager | [Insert Date] |
| [Name] | Business Analyst | [Insert Date] |
| [Name] | Stakeholder | [Insert Date] |

## 📎 Tools Used

- **Power BI** for dashboard creation
- **Excel / CSV** files as data sources
- **Python** or **SQL** (optional) for preprocessing

---

## 📬 Contact

For any questions or feedback, feel free to reach out at priyeshkumar554@gmail.com.

