Seattle Airbnb Tableau Dashboard

• Project Overview

This project analyzes the "Seattle Airbnb Open Data" using "Microsoft Excel" for data cleaning and "Tableau" for interactive dashboard creation. The dashboard provides insights into listing prices, availability, neighborhood performance, and review trends to help users better understand the Seattle Airbnb market.

---

• Project Structure

── Dataset
• Listings.xlsx
• Calendar.xlsx
• Reviews.xlsx

── Images
── README.md
── Seattle Airbnb Dashboard.twbx

---

• Tools Used

- Microsoft Excel (Data Cleaning)
- Tableau Desktop (Data Visualization)
- Git & GitHub (Version Control)

---

• Datasets Used

The project uses three datasets from the Seattle Airbnb Open Dataset - https://www.kaggle.com/datasets/airbnb/seattle.

1. Listings

Contains information about Airbnb listings such as price, property type, host details, location, and review scores.

2. Calendar

Contains daily availability and pricing information for each listing.

3. Reviews

Contains guest reviews, review dates, reviewer information, and comments.

---

• Data Cleaning

Data cleaning was performed in **Microsoft Excel** before importing the datasets into Tableau.

• Listings Dataset

The following cleaning steps were performed:

- Removed unnecessary URL and image columns.
- Cleaned currency columns by removing "$" and commas.
- Converted price-related columns to numeric format.
- Formatted date columns.
- Checked for duplicate listing IDs.
- Saved the cleaned dataset as **Listings.xlsx**.

---

• Calendar Dataset

The following cleaning steps were performed:

- Removed "$" symbols from the Price column.
- Converted the Price column to numeric format.
- Formatted the Date column.
- Kept blank prices for unavailable listings because they represent valid missing values.
- Checked for duplicate records using **listing_id** and **date**.
- Saved the cleaned dataset as **Calendar.xlsx**.

---

• Reviews Dataset

The following cleaning steps were performed:

- Formatted the Date column.
- Checked for duplicate Review IDs.
- Preserved reviewer names and comments without modification.
- Saved the cleaned dataset as **Reviews\_.xlsx**.

---

• Dashboard Features

The Tableau dashboard provides insights into:

- Average Airbnb prices across Seattle.
- Price comparison by ZIP Code.
- Price distribution by neighborhood.
- Listing availability throughout the year.
- Total listings available in Seattle.
- Review trends and summary metrics.

---

• Key Insights

- Some neighborhoods have significantly higher average listing prices than others.
- Listing availability varies throughout the year.
- Premium locations generally have higher average prices.
- The Seattle Airbnb market contains a wide range of property prices and listing types.

---

• Skills Demonstrated

- Data Cleaning in Microsoft Excel
- Data Preparation
- Data Validation
- Tableau Data Modeling
- Interactive Dashboard Design
- Data Visualization
- Business Insight Generation

---

• Dashboard Preview

- Seattle Airbnb Dashboard - "C:\Users\priya\OneDrive\Documents\Seattle-Airbnb-Tableau-Dashboard\Images\Dashboard.png.png"

---

• Dataset Source

Seattle Airbnb Open Dataset (https://www.kaggle.com/datasets/airbnb/seattle)

---
