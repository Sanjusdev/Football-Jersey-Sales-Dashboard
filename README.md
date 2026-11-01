
# Football Jersey Sales Dashboard

An interactive **Power BI dashboard** that analyzes sales for a football jersey shop. It helps answer key business questions: which teams sell the most, how customers prefer to pay, which sizes are in demand, and how sales change across quarters and years.

## Objectives

- Track overall revenue and sales performance
- Identify the best-selling teams
- Understand customer payment preferences
- Analyze demand by jersey size
- Compare sales trends across quarters and years
- Let users explore the data by sales channel, team, and payment method

## Key Metrics

| Metric | Value |
|---|---|
| Total Sales Amount | ~3M |
| Sum of Unit Price | ~832K |
| Period Covered | 2023 – 2024 |

## Dashboard Visuals

| Visual | What It Shows |
|---|---|
| KPI Cards | Total sales amount and sum of unit price at a glance |
| Slicers | Filter by Sales Channel, Team, and Payment Method |
| Customers by Payment Method (bar chart) | Which payment methods customers use most |
| Sales by Quarter and Team (area chart) | Quarterly sales trends for each team |
| Sales by Team and Payment Method (clustered column chart) | How payment preferences differ across teams |
| Quantity by Size (donut chart) | Share of units sold per jersey size (S, M, L, XL) |
| Team Count and Sales by Year (line chart) | Year-over-year comparison between 2023 and 2024 |
| Sales by Team (bar chart) | Revenue ranking of teams |

## Key Insights

- **Real Madrid** generates the highest revenue, followed by **Manchester United**, **FC Barcelona**, and **Juventus**.
- **Online Payment** is the most common payment method by customer count, ahead of Credit Card, Cash, UPI, and Debit Card.
- Jersey sales are spread across multiple sizes, with no single size dominating the order mix.
- Quarterly and yearly views make it easy to spot seasonal changes and compare 2023 with 2024.

## Interactive Filters

Use the slicers on the dashboard to filter every visual by:

- **Sales Channel** (e.g., In-Store, Online)
- **Team** (e.g., Arsenal, Bayern Munich, Chelsea, FC Barcelona)
- **Payment Method** (Cash, Credit Card, Debit Card, Online Payment, UPI)

## Dataset

The dashboard is built on jersey shop sales data with fields such as:

- `CustomerID`
- `Team`
- `Size`
- `Quantity`
- `UnitPrice`
- `TotalAmount`
- `SalesChannel`
- `PaymentMethod`
- `Quarter` / `Year`

## Tools and Skills

- **Power BI Desktop** for data modeling, visualization, and interactive dashboard design
- **Excel / CSV** as the data source
- Data cleaning and preparation
- KPI design and dashboard storytelling


