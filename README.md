# Sales Analysis Dashboard - Power BI

![output](https://github.com/user-attachments/assets/0050c2b4-b242-4460-b659-2f5ef827fcbc)


## 📖 About the Project
This project is a **Power BI Sales Analysis Dashboard** designed to help businesses track their **Total Sales Orders, Total Revenue, Order Quantity, Total Cost, and Total Profit**. The dashboard provides insights into:  
✔ **Top-performing products**  
✔ **Sales distribution by city, channel, and currency**  
✔ **Revenue trends and business performance**  

## 🎯 Key Features
- 📊 **Dynamic KPI Cards:** Display Total Revenue, Order Quantity, Total Cost, and Total Profit.  
- 📈 **Visual Analytics:** Pie charts, bar graphs, and line charts to showcase sales trends.  
- 🌍 **Geographical Breakdown:** Revenue insights based on different cities.  
- 🔄 **Filter Options:** Channel selection (Distributor, Export, Wholesale) and date range filter.  
- 📥 **Interactive Reports:** Helps business owners make data-driven decisions.  

## 📁 Dataset Information
The dataset consists of:  
- **Sales Orders** (Order Number, Unit Price, Order Quantity, Total Revenue, etc.)  
- **Customers** (Customer demographics, region, etc.)  
- **Regions** (Geographical data)  
- **Products** (Product details, categories)  

## 🛠 Power BI DAX Formulas Used
```DAX
Total Sales Orders = DISTINCTCOUNT('Sales Orders'[OrderNumber])
Total Revenue = SUM('Sales Orders'[Total Revenue])
Total Order Quantity = SUM('Sales Orders'[Order Quantity])
Total Cost = SUM('Sales Orders'[Total Unit Cost])
Total Profit = [Total Revenue] - [Total Cost]
```

## 🔧 Tools & Technologies
- **Power BI** – For data visualization and dashboard creation  
- **DAX (Data Analysis Expressions)** – For custom calculations  
- **Excel** – For data preprocessing  
- **SQL (Optional)** – For advanced queries  

## 📥 How to Use
1. **Download the Power BI file (`.pbix`)** from the repository.  
2. **Open it in Power BI Desktop.**  
3. **Customize filters and explore visualizations.**  
4. **Export insights for business decision-making.**  

## 📌 Future Enhancements
🔹 Add **forecasting models** for sales prediction.  
🔹 Integrate with **live databases** for real-time analysis.  
🔹 Improve **UX/UI design** for better usability.  

## 🤝 Contributing
Feel free to **fork this repo, open an issue, or submit a pull request** if you’d like to improve this project.  

## 🔖 Topics
- Power BI  
- Sales Dashboard  
- Data Visualization  
- Business Intelligence  
- DAX  
- KPI Metrics  
- SQL  
- Excel  
- Revenue Analysis  
- Data Analytics  

## 📜 License
MIT License  

```
MIT License

Copyright (c) 2025 Allan Otieno Akumu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software...
```

---
