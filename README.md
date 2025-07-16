
# Power BI Project: AdventureWorks Sales Analysis

## Description
This Power BI project leverages the **AdventureWorks** dataset to provide a detailed analysis of sales performance across different regions, products, and time periods. The project includes interactive dashboards that help track key performance indicators (KPIs), analyze sales trends, and identify areas for improvement.

## Features
- **Interactive Dashboards**: Explore multiple views of sales performance, product categories, and regional analysis.
- **Data Sources**:
  - AdventureWorks dataset (Sales, Products, Regions, etc.)
- **Key Metrics**:
  - **Total Sales**: The total revenue generated across different regions and products.
  - **Sales by Product**: Analysis of sales performance by product categories.
  - **Sales by Region**: Insights into how sales vary by geographical location.
  - **Sales Growth**: Year-over-year sales growth and trends.
  - **Average Order Value (AOV)**: Calculation of average revenue per order.
- **Advanced Visualizations**:
  - **Bar Charts**: Display of sales performance by product and region.
  - **Line Charts**: Year-over-year sales trends.
  - **Pie Charts**: Product category sales distribution.
  - **KPIs**: Key sales metrics such as total revenue, average order value, etc.
  - **Treemap**: Visual representation of sales distribution by category and subcategory.

## Installation
To run this project locally, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/[your-username]/[project-repository].git
   ```
2. **Install Power BI Desktop** (if you haven't already).
   - Download from the official [Microsoft website](https://powerbi.microsoft.com/desktop/).
3. **Open the .pbix file**: Navigate to the folder containing the `.pbix` file and open it in Power BI Desktop.

## Usage
- **Data Refresh**: Ensure that the AdventureWorks dataset is connected and set for data refresh (if you are using a live or direct query).
- **Modifying Reports**: You can modify the visuals, filters, and metrics by editing the fields and visual elements within Power BI Desktop.
- **Exploring Dashboards**: Use the interactive filters (e.g., product categories, regions, time period) to explore specific insights on sales data.

## Data Model
The AdventureWorks dataset has been structured with the following key components:
- **Tables**:
  - **Sales**: Contains transaction data including sales orders, amounts, and quantities.
  - **Products**: Information about the products, including category and subcategory.
  - **Regions**: Geographic locations where sales are made.
  - **Dates**: Time-based data to support time intelligence features like year-over-year growth.
- **Relationships**:
  - One-to-many between **Sales** and **Products** (each sale is linked to a product).
  - One-to-many between **Sales** and **Regions** (sales are tied to specific regions).
  - Many-to-one between **Sales** and **Dates** (sales are linked to specific dates).

## Contributing
If you'd like to contribute to this project:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
