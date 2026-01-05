# Dash E-Commerce Analytics

Interactive analytics dashboard built with Plotly Dash to explore customer orders, products, payments, and delivery performance for a Brazilian e-commerce marketplace.

## Project Overview

This project provides a data-driven view of an e-commerce business using a real-world public dataset. It brings together order, customer, product, seller, and delivery details to answer common business questions such as:

- How do order volumes and revenues change over time?
- Which product categories contribute the most to sales?
- Where are customers located and how does geography affect delivery time?
- How do payment methods and installment counts impact revenue?
- What are the delivery performance trends and review outcomes?

The result is a Dash-based dashboard that enables quick, interactive exploration across these dimensions.

## Dataset Source

Data comes from the **Brazilian E-Commerce Public Dataset by Olist** on Kaggle. This dataset contains ~100k orders from 2016–2018 and includes customer, order, payment, product, seller, and review information. It is commonly used for e-commerce analytics, delivery performance analysis, and customer behavior exploration.

- Kaggle dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Project Structure

Key folders and files in this repository:

- `app.py` / `main.py`: Dash application entry points.
- `pages/`: Multi-page Dash layout and page components.
- `data/`: Local data assets (CSV files from the Olist dataset).
- `assets/`: Front-end assets such as CSS or images used by Dash.
- `notebooks/`: Exploration and analysis notebooks.
- `config/`: Configuration files for the app.

## Key Analyses Covered

The dashboard surfaces insights across the full order lifecycle:

- **Orders & revenue trends:** Monthly/weekly patterns and growth.
- **Product categories:** Category distribution and top performers.
- **Payments:** Payment type usage and installment behavior.
- **Geography:** Customer distribution by state and city.
- **Delivery performance:** Lead times, delays, and fulfillment trends.
- **Reviews:** Review score distribution and customer sentiment signals.

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Start the app:
   ```bash
   python app.py
   ```
3. Open the local URL printed in your terminal to view the dashboard.

> If you are using a different entry point, check `main.py` or `pages/` for the primary app file.

## Notes

- The dataset is anonymized and shared for educational and analytical use.
- The project is suitable for demos, portfolio work, and learning Dash/Plotly analytics workflows.

## License

This project uses the dataset under the Kaggle license provided by Olist. Please refer to the dataset page for full licensing details.
