# Automated Retail Sales Data Pipeline

An automated Python-based ETL (Extract, Transform, Load) pipeline that processes sales data, aggregates category performance metrics, and automatically generates summary reports and charts.

## Features
- **Data Ingestion**: Reads raw sales transaction datasets.
- **Data Processing**: Aggregates total revenue and quantity sold per product category using Pandas.
- **Visualization**: Automatically generates and saves visual charts using Seaborn and Matplotlib.
- **Task Scheduling**: Configured with the `schedule` library to execute reporting pipelines automatically at set intervals.

## How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/retail-sales-automation.git](https://github.com/YOUR_USERNAME/retail-sales-automation.git)
   cd retail-sales-automation
