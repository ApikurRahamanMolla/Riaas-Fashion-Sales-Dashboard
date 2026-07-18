# Riaas Fashion E-Commerce Sales Dashboard

## 📊 Project Overview
An interactive Power BI dashboard tracking dynamic metrics across 1,500+ operational order lines. This project involved building a relational star-schema data model mapping transactional facts to customer, geographical, and time-based dimensional hierarchies.

## 📁 Repository Structure
* **`riaas_fashion_sales_report.pbix`**: The complete interactive dashboard file.
* **`Orders.csv`**: Dimension table detailing Order ID, Dates, Customer Names, and Geography (State/City).
* **`Details.csv`**: Fact table detailing financial components (Amount, Profit), quantity, product categories, and payment modes.

## 💡 Key Analytical Focus Areas
* **Data Modeling:** Resolved filter relationship breaks by connecting dimension attributes natively across granularities.
* **UX/UI Best Practices:** Configured modern, custom structural containers utilizing high-contrast styling, proper leader lines, and high-level card metrics positioned gracefully within reading flow lines.
* **Slicer Integration:** Established precise visual cross-filtering using categorical and dynamic chronological (Quarterly) slicers.

## 🛠️ Technology Stack
* Power BI Desktop
* Power Query (Data cleaning, column trimming)
* DAX Expressions
