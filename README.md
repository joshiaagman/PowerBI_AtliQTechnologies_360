# AtliQ Business Intelligence 360

## Project Overview
AtliQ Technologies, a rapidly growing electronics company, faced substantial losses in Latin America due to their reliance on Excel files and intuition-based decision-making. With increasing competition in the consumer electronics sector, AtliQ needed to adopt a data-driven approach. This project aims to develop an enterprise-wide business intelligence dashboard providing insights into finance, sales, marketing, and supply chain sectors.

## Problem Statement
AtliQ Technologies faced significant losses due to outdated Excel files and intuition-based decisions. The goal was to transition to data-driven decision-making in response to rising competition.

## Objective
The objective is to create a comprehensive business intelligence dashboard for data-driven decisions across finance, sales, marketing, and supply chain departments.

## Tools Used
- **MySQL**: Data storage and querying.
- **Power BI Desktop**: Dashboard creation and visualization.
- **Power Query M**: Data transformation and cleaning.
- **DAX**: Calculated fields and measures.
- **DAX Studio**: DAX query optimization.

## Domain-Related Terms
- **Gross Price**: Total price before deductions.
- **Pre-Invoice Deductions**: Reductions before invoicing.
- **Net Invoice Sales**: Sales after pre-invoice deductions.
- **Post-Invoice Deductions**: Reductions after invoicing.
- **Net Sales**: Total sales after all deductions.
- **COGs (Cost of Goods Sold)**: Direct production costs.
- **Gross Margin**: Difference between net sales and COGs.
- **Operational Expense**: Costs required to run a business.
- **Net Profit**: Profit after all expenses.

## Project Setup and Installation

### Prerequisites
- **MySQL**: Installed and running.
- **Power BI Desktop**: Download from [Microsoft Power BI](https://powerbi.microsoft.com/desktop/).
- **DAX Studio** (optional): For advanced DAX analysis.

### Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/joshiaagman/PowerBI_AtliQTechnologies_360.git
   cd PowerBI_AtliQTechnologies_360
   ```

2. **Set Up MySQL Database**:
   - Import the SQL dump file (`database_dump.sql`) into MySQL.
   - Configure Power BI connection strings to MySQL.

3. **Open Power BI File**:
   - Open `AtliQ_BI_Dashboard.pbix` in Power BI Desktop.
   - Refresh data to connect to MySQL.

4. **Explore the Dashboard**:
   - Navigate through the dashboard views.

## Data Files
The data files are located in the `data` directory:
- `database_dump.sql`: SQL dump for MySQL setup.
- `data_sample.xlsx`: Sample data for testing.

## Dashboard
View the live Power BI dashboard here: [AtliQ BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTFmNjVjNzUtNTkwMS00MDE5LTk0OWEtMjgwNTY3ZTQ4NWFkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Workflow
1. **Project Charter**: Define objectives, stakeholders, and success measures.
2. **Data Import**: Import data into MySQL.
3. **Data Integration**: Connect Power BI with MySQL.
4. **Data Cleaning**: Use Power Query for data transformation.
5. **Dashboard Design**: Apply design principles for usability.
6. **Stakeholder Feedback**: Validate and iterate on dashboard functionality.
7. **DAX Optimization**: Optimize queries with DAX Studio.
8. **Publishing**: Publish to Power BI service for team access.

## Report Views
### Info View
- Content: Data refresh info, sources, FAQs, and Excel download links.

### Finance View
- KPIs: Net Sales, Gross Margin %, Net Profit %.
- Visuals: P&L Statement, Top/Bottom Products & Customers.

### Sales View
- Visuals: Net Sales Over Time, Bubble Chart, Product/Customer Matrix.

### Marketing View
- Visuals: Market Performance Bubble Chart, Sales and GM Bifurcation.

### Supply Chain View
- KPIs: Forecast Accuracy, Net Error, Absolute Error.
- Visuals: Accuracy Trend, Key Metrics by Customer & Products.

### Executive View
- KPIs: Net Sales, Gross Margin %, Net Profit %, Forecast Accuracy %.
- Visuals: Revenue Contribution, Key Metrics Trends, Top Customers/Products.

## Contributing
1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m 'Add your feature'`.
4. Push to branch: `git push origin feature/your-feature`.
5. Open a pull request.

## Acknowledgements
- **Power BI Community**: For resources and inspiration.
- **AtliQ Technologies**: For business context and data.

## Contact
- **Author**: Aagman Joshi
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/aagmanjoshi/)
- **Email**: aagman.work@gmail.com

```
