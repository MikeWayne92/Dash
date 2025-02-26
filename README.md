# Sales Analytics Dashboard

## Project Overview
This interactive dashboard provides comprehensive insights into sales performance across multiple dimensions. By visualizing key metrics related to product categories, customer segments, and temporal patterns, this dashboard enables data-driven decision making for optimizing sales strategies and identifying growth opportunities.

## Dashboard Access
- [View Interactive Dashboard](https://lookerstudio.google.com/s/kRYxYqLWBZ4)

## Dashboard Preview
![Dashboard Overview](images/Maindash.png)


## Key Features

### 1. Sales Overview Scorecard
- **Purpose**: Provides at-a-glance performance metrics
- **Metrics**: Total Sales, Profit, Quantity Ordered, and Order Count
- **Value**: Quickly assess overall business health and performance

### 2. Sales Trend Analysis
- **Purpose**: Track sales and profit performance over time
- **Implementation**: Time series chart with date range selector
- **Value**: Identify seasonal patterns and growth trends

### 3. Product Category Performance
- **Purpose**: Compare performance across product categories
- **Visualization**: Bar chart showing Sales, Profit, and Quantity
- **Value**: Identify top-performing and underperforming product lines

### 4. Customer Segment Analysis
- **Purpose**: Understand revenue distribution across customer segments
- **Visualization**: Pie charts for Sales and Profit by segment
- **Value**: Target marketing efforts to most valuable customer segments

### 5. Product Category Breakdown
- **Purpose**: Detailed view of product sub-categories
- **Visualization**: Treemap with hierarchical category structure
- **Value**: Identify specific product niches driving business results

### 6. Order Priority Distribution
- **Purpose**: Analyze order fulfillment by priority level
- **Visualization**: Donut chart showing distribution
- **Value**: Optimize resource allocation for order processing

### 7. Weekday Performance Analysis
- **Purpose**: Track sales patterns throughout the week
- **Visualization**: Column chart showing daily performance
- **Value**: Optimize staffing and inventory based on day-of-week patterns

### 8. Order Returns Analysis
- **Purpose**: Identify products with high return rates
- **Visualization**: Table with drill-down capability
- **Value**: Address quality issues and improve customer satisfaction

## Data Source
This dashboard utilizes a comprehensive sales dataset containing:
- **Customer Information**: ID, Name, City, Segment
- **Order Details**: Date, ID, Priority, Weekday, Returns
- **Product Information**: Category, Sub-Category, Name
- **Financial Metrics**: Sales, Profit, Quantity, Unit Price

## Implementation Details

### Data Preparation
1. Connected Google Sheets data source to Looker Studio
2. Established data type formatting (dates, currencies, numbers)
3. Created calculated fields for enhanced analysis

### Dashboard Construction
1. Designed multi-page layout with logical information hierarchy
2. Implemented cross-filtering capabilities across visualizations
3. Added interactive controls for dynamic data exploration
4. Optimized for both desktop and mobile viewing

### Key Calculations
- **Profit Margin**: `Profit / Sales`
- **Return Rate**: `Count of Returned Orders / Total Orders`
- **Day-of-Week Ordering**: Used Weekday helper field for proper sorting

## Insights

Based on the dashboard analysis, several key insights emerged:

1. **Product Performance**: [Add your specific insight here]
2. **Customer Behavior**: [Add your specific insight here]
3. **Temporal Patterns**: [Add your specific insight here]
4. **Profit Drivers**: [Add your specific insight here]

## Future Enhancements

Plans for dashboard expansion include:

1. Adding predictive analytics for sales forecasting
2. Implementing geographic visualization of customer distribution
3. Creating customized views for different stakeholder groups
4. Incorporating inventory data for supply chain optimization

## Technical Implementation
For details on the technical implementation, see [IMPLEMENTATION.md](IMPLEMENTATION.md).

---

*This dashboard was created using Google Looker Studio.*
