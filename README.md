Code Alpha Task:Web Scraping

project title:
Book Data Collection using web scraping

objective:
To collect book titles,prices,availability from a website using python.

Tools Used:
python,Requests,Beautifulsoup,Pandas,Google Colab

Methodology:
1. Connectd to the books to scrape practice website.
2. Retrived the websites HTML.
3. Extracted book titles,prices,availability.
4. Stored the Collected information in a pandas data frame.
5. Saved the Dataset as CSV file.

Dataset:
Collected 20 book records from the first page of the website.

Website:
https://books.toscrape.com/

Conclusion:
This project helped me learn the basics of webscraping and
collecting structured data for further analysis.


# Exploratory Data Analysis (EDA) – CodeAlpha Internship

## 1. Project Overview
Exploratory Data Analysis (EDA) was performed on an e-commerce books dataset named `books_data.csv`. The purpose of this project is to understand book prices and availability by examining the dataset, calculating basic statistics, and creating visualizations using Python.

## 2. Objectives
- Understand the structure of the dataset.
- Identify missing values and duplicate records.
- Check and correct data types.
- Analyze book prices using descriptive statistics.
- Examine book availability.
- Visualize price patterns and identify key findings.

## 3. Dataset Description
The dataset contains information about books collected from an e-commerce website.

| Column | Description |
|---|---|
| Title | Name of the book |
| Price | Price of the book in pounds (£) |
| Availability | Stock availability status |

**Dataset size:** 20 rows and 3 columns.

## 4. Tools and Technologies Used
- Python
- Google Colab
- Pandas
- Matplotlib

## 5. Data Inspection
The dataset was loaded using Pandas. The number of rows and columns, column names, data types, and sample records were examined to understand the structure of the data.

## 6. Data Cleaning
The following data quality checks were performed:
- Checked for missing values in each column.
- Checked for duplicate records.
- Examined the data types of the columns.
- Removed the unwanted currency symbols from the Price column.
- Converted book prices into numeric values for statistical analysis.

## 7. Descriptive Statistics
Descriptive statistics were calculated for the cleaned Price column to understand the distribution of book prices.

The analysis included:
- Average book price
- Minimum book price
- Maximum book price
- Other relevant summary statistics

## 8. Availability Analysis
The Availability column was analyzed using value counts to understand the distribution of book stock statuses in the dataset.

## 9. Data Visualization
A horizontal bar chart titled **Top 10 Most Expensive Books** was created using Matplotlib. The chart compares the prices of the ten most expensive books in the dataset and makes it easier to identify the highest-priced books.

## 10. Key Findings
- The dataset contains book titles, prices, and availability information.
- Currency symbols were removed and prices were converted into numeric values for analysis.
- Missing values and duplicate records were checked.
- Descriptive statistics helped summarize book prices.
- Availability counts helped examine stock status.
- The price visualization highlighted the ten most expensive books in the dataset.

## 11. Conclusion
The EDA project provided an understanding of the e-commerce books dataset through data inspection, data cleaning, descriptive statistics, availability analysis, and visualization. Python, Pandas, and Matplotlib were used to prepare and analyze the data. The results demonstrate how exploratory data analysis can help identify patterns and summarize information before further analysis.

## 12. Limitations
- The dataset contains only 20 records.
- The analysis is limited to book prices and availability.
- The findings represent only the collected dataset and may not reflect the entire e-commerce books market.


# Data Visualization – CodeAlpha Internship

## 1. Project Overview
Data visualization was performed on the e-commerce books dataset, `books_data.csv`, to present book price information in a clear and understandable graphical format. Python and Matplotlib were used to create charts and identify patterns in book prices.

## 2. Objectives
- Represent book prices visually.
- Identify the most expensive books in the dataset.
- Compare prices across different books.
- Improve understanding of the dataset through graphical analysis.

## 3. Dataset Description
The dataset contains 20 rows and 3 columns.

- **Title:** Name of the book.
- **Price:** Price of the book in pounds (£).
- **Availability:** Availability status of the book.

## 4. Tools and Technologies Used
- Python
- Google Colab
- Pandas
- Matplotlib

## 5. Data Preparation
The `books_data.csv` file was loaded into Pandas for visualization. The Price column was cleaned by removing unwanted currency symbols and converting the values into numeric format. This enabled accurate price comparisons and chart creation.

## 6. Visualization Performed

### Top 10 Most Expensive Books
A horizontal bar chart was created to display the ten most expensive books in the dataset.

**Purpose:**
- Compare prices of the selected books.
- Identify the highest-priced books.
- Present price differences in an easy-to-read format.

**Analysis:**
The horizontal bar chart makes it easier to compare book prices and identify which books have higher prices within the dataset.

## 7. Key Findings
- The visualization highlights the ten most expensive books among the collected records.
- Book prices vary across the selected titles.
- The horizontal bar chart provides a clear comparison of book prices.
- Visual representation makes it easier to identify high-priced books than examining individual records in a table.

## 8. Conclusion
The data visualization task successfully presented book price information using Python and Matplotlib. The horizontal bar chart helped compare book prices and identify the ten most expensive books in the dataset. This project demonstrates how visualizations can communicate data patterns clearly and support basic data analysis.

## 9. Limitations
- The visualization is based on a small dataset of 20 books.
- The analysis focuses primarily on book prices.
- The results may not represent the prices of all books available on the e-commerce website.


