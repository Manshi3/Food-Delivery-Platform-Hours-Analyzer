# Food Delivery Hours Analyzer

## Project Overview
This project analyzes business hours consistency across multiple food delivery platforms (UberEats and Grubhub). It uses SQL to identify and categorize discrepancies in restaurant operating hours between platforms.

## Key Features
- Compares business hours between UberEats and Grubhub
- Parses complex JSON data structures
- Categorizes time discrepancies (In Range, Out of Range, Out of Range with 5 mins difference)

## Technologies Used
- SQL (BigQuery)
- JSON parsing

## How It Works
The SQL query:
1. Extracts business hours from UberEats and Grubhub data
2. Normalizes the data for comparison
3. Identifies mismatches and categorizes them
