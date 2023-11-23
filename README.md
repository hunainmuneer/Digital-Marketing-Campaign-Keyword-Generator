# Digital Marketing Campaign Keyword Generator

## Introduction

This Python notebook is designed to assist digital marketing agencies in generating a set of keywords for search campaigns based on a client's brief. The client, a low-cost retailer of furniture, wants to target price-sensitive customers and focus on specific products such as sofas, convertible sofas, love seats, recliners, and sofa beds.

## Workflow Overview

1. **List of Words:**
   - The notebook starts by defining a list of words that align with the client's focus, such as "buy," "price," "discount," etc.

2. **Combining Words with Products:**
   - The words are then combined with the specified products to generate meaningful keyword combinations. For each product, combinations like "product buy," "buy product," "product price," etc., are created.

3. **DataFrame Creation:**
   - The resulting combinations are organized into a DataFrame for easy manipulation and management.

4. **Column Renaming:**
   - Columns in the DataFrame are renamed to more meaningful names, improving readability.

5. **Campaign and Match Type Columns:**
   - Additional columns for "Campaign" and "Criterion Type" (match type) are added to the DataFrame.

6. **Duplicate Keywords for Phrase Match:**
   - The keywords are duplicated to create a version for phrase match, providing a broader set of matched keywords.

7. **Save as CSV:**
   - The final DataFrame is saved as a CSV file, suitable for uploading to platforms like Google AdWords or Bing Ads.

## Usage

To use this notebook:
1. Ensure you have Python and Jupyter Notebook installed.
2. Open the notebook and execute each cell sequentially.
