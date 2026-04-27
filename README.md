# UrbanStyle Customer Data Cleaning Project

## Overview

The UrbanStyle Customer Data Cleaning Project is a Python-based data preparation and analytics project focused on improving raw customer records for a fictional retail brand called **UrbanStyle**. The script imports messy customer data, identifies quality issues, cleans and standardizes records, engineers new business metrics, and generates actionable insights. :contentReference[oaicite:0]{index=0}

This project demonstrates essential data cleaning skills used in real-world analytics, marketing, and customer intelligence roles.

---

## Features

### Data Quality Assessment
- Detects missing values
- Identifies duplicate records
- Finds inconsistent formatting
- Reviews incorrect data types

### Data Cleaning & Standardization
- Fixes inconsistent date formats
- Converts currency fields to numeric values
- Standardizes names and categories
- Formats phone numbers consistently
- Fills missing values using logical methods

### Feature Engineering
Creates new business metrics such as:

- Days since last purchase
- Average purchase value
- Purchase frequency category
- Customer loyalty insights

### Business Reporting
- Revenue by loyalty tier
- Category revenue ranking
- Customer satisfaction vs spending correlation
- Final cleaned dataset preview

---

## Technologies Used

- Python 3
- Pandas
- NumPy

---

## Raw Dataset Includes

### Customer Information
- Customer ID
- First name
- Last name
- Email
- Phone number
- Age
- City
- State

### Purchase Data
- Join date
- Last purchase date
- Total purchases
- Total spent

### Preferences
- Preferred category
- Loyalty status
- Satisfaction rating

:contentReference[oaicite:1]{index=1}

---

## Cleaning Tasks Performed

### Missing Values Handled
- Missing names replaced
- Missing phone numbers filled
- Missing ages estimated using median
- Missing loyalty statuses filled
- Missing satisfaction scores imputed

### Standardization
- Names converted to proper case
- Categories standardized (Menswear, Womenswear, etc.)
- Phone numbers converted to `(XXX) XXX-XXXX`

### Type Conversion
- Dates converted to datetime format
- Spending converted to numeric
- Purchases converted to integers

### Duplicate Removal
- Duplicate customer rows removed while preserving first valid entry

---

## Business Insights Generated

- Total customer count after cleaning
- Average revenue by loyalty level
- Highest-performing product category
- Relationship between customer satisfaction and spending

---

## How to Run

### Install Dependencies

```bash
pip install pandas numpy
