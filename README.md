# Product-Data-Scraper-using-Playwright-
# 🛒 Product Data Scraper using Playwright (Python)

This project is a web scraper built with [Playwright](https://playwright.dev/python/) that dynamically extracts product data from a webpage where products load in cards. The extracted data is saved to a JSON file for further analysis.

## 🔧 Features

- Extracts product details like:
  - Name
  - ID
  - Material
  - Stock
  - Size
- Handles dynamic content loading using Playwright
- Supports multiple pages of products (if implemented)
- Outputs data in clean JSON format

## 📁 Output

The script creates a file named `products.json` with an array of product objects, like:

```json
[
  {
    "Name": "Budget Sports Device",
    "ID": "12",
    "Material": "Plastic",
    "Stock": 150,
    "Size": "30×20×10 cm"
  },
  ...
]
