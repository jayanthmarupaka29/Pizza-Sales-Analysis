# Pizza Sales Analysis Project

## 📊 Project Overview
A comprehensive data analysis project examining pizza sales data from January 2015 to December 2015. The project combines SQL analysis with Power BI visualization to derive actionable business insights from a pizza restaurant chain's sales data.

## 🎯 Key Metrics
[![Dashboard 1](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI/blob/main/dashboard1.png)](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI)

| Metric | Value |
|--------|--------|
| Total Revenue | $817.86K |
| Average Order Value | $38.31 |
| Total Pizzas Sold | 49,574 |
| Total Orders | 21,350 |
| Average Pizzas Per Order | 2.32 |

## 📈 Analysis Features

### 1. Sales Performance Analysis
- Daily and monthly trend analysis
- Peak hours identification
- Category-wise performance tracking
- Size-based sales distribution

### 2. Product Performance
- Top/Bottom 5 pizzas by:
  - Revenue
  - Quantity
  - Total Orders
- Category-wise analysis
- Size preference analysis

## 🛠️ Built With

- **SQL Server** - Data Analysis
- **Power BI** - Data Visualization

## 📂 Project Structure

```plaintext
├── SQL/
│   └── pizza_sales_analysis.sql
├── PowerBI/
│   └── pizza_sales_dashboard.pbix
├── Images/
│   ├── dashboard1.png
│   └── dashboard2.png
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Microsoft SQL Server
- Power BI Desktop
- Sample Pizza Sales Dataset

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI.git
```

2. Import the database using the provided SQL scripts
```bash
sqlcmd -S serverName -E -i pizza_sales_analysis.sql
```

3. Open the Power BI dashboard
```plaintext
Open pizza_sales_dashboard.pbix with Power BI Desktop
```

## 📊 Dashboards

### Main KPI Dashboard
[![Dashboard 1](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI/blob/main/dashboard1.png)](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI)

### Best/Worst Sellers Dashboard
[![Dashboard 2](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI/blob/main/dashboard2.png)](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI)

## 📊 Key Insights

### Time-Based Analysis
- Peak order times: Friday/Saturday evenings
- Busiest months: July and January
- Consistent daily order patterns with weekend spikes

### Category Performance
- Classic category leads in sales volume
- Large size pizzas generate maximum revenue
- Category distribution:
  - Classic: 26.91%
  - Supreme: 25.46%
  - Veggie: 23.68%
  - Chicken: 23.95%

### Top Performers
1. By Revenue:
   - Thai Chicken Pizza
   - Barbecue Chicken Pizza
   - California Pizza
   - Classic Deluxe Pizza
   - Spicy Italian Pizza

2. By Quantity:
   - Classic Deluxe Pizza
   - Barbecue Chicken Pizza
   - Hawaiian Pizza
   - Pepperoni Pizza
   - Thai Chicken Pizza

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 📫 Contact

Your Name - [@yourusername](https://github.com/yourusername)

Project Link: [https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI](https://github.com/yourusername/Pizza-Sales-Project-SQL-PowerBI)

## 🙏 Acknowledgments

* [Power BI Community](https://community.powerbi.com/)
* [SQL Server Documentation](https://docs.microsoft.com/sql/)
* [Dataset Source Name/Link]
