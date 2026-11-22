# Python-Web-Scraping-Books-Analysis
A Python web scraping project using Requests, BeautifulSoup, Pandas, and Matplotlib to collect, clean, analyze, and visualize data from 1,000 books.


## 📌 Project Overview

This project focuses on collecting, cleaning, analyzing, and visualizing book data from [Books to Scrape](https://books.toscrape.com/) using Python.

Using Requests and BeautifulSoup, data was extracted from 50 web pages containing 1,000 books. The collected data was processed and analyzed using Pandas, while Matplotlib was used to create visualizations.

The project demonstrates a practical application of Python for web scraping and exploratory data analysis.

## 🎯 Project Objectives

- Extract book information from a real website.
- Scrape data from multiple web pages.
- Collect book titles, prices, ratings, and availability.
- Clean and transform the extracted data.
- Validate data quality.
- Perform basic exploratory data analysis.
- Create visualizations to understand the dataset.
- Export the cleaned dataset into a CSV file.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Programming language |
| Requests | Sending HTTP requests |
| BeautifulSoup | Extracting data from HTML |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| Jupyter Notebook | Development environment |

## 📊 Dataset Information

The dataset was collected from 50 pages of Books to Scrape.

| Dataset Details | Value |
|---|---:|
| Total Books | 1,000 |
| Total Columns | 4 |
| Missing Values | 0 |
| Duplicate Records | 0 |

### Dataset Columns

- **Book Title:** Name of the book.
- **Price:** Price of the book in GBP (£).
- **Rating:** Book rating from 1 to 5.
- **Availability:** Stock availability status.

## 🔄 Project Workflow

### 1. Website Connection
- Connected to the website using Requests.
- Checked the HTTP response status.
- Retrieved the HTML content.

### 2. Web Scraping
- Parsed HTML using BeautifulSoup.
- Extracted book titles, prices, ratings, and availability.
- Scraped all 50 pages.
- Collected 1,000 book records.

### 3. Data Collection
- Stored the extracted information in Python lists.
- Created a Pandas DataFrame containing 1,000 records.

### 4. Data Cleaning
- Removed currency symbols from prices.
- Converted prices into numeric values.
- Converted text-based ratings into numerical values.

### 5. Data Validation
- Checked for missing values.
- Checked for duplicate records.
- Verified dataset dimensions and data types.

### 6. Data Analysis
Performed the following analysis:

- Average book price.
- Highest book price.
- Lowest book price.
- Book rating distribution.
- Identification of top-rated books.

### 7. Data Visualization
Created visualizations using Matplotlib:

- Book Rating Distribution – Bar Chart.
- Book Price Distribution – Histogram.

### 8. Data Export
- Exported the cleaned dataset into a CSV file.
- Verified the exported CSV file using Pandas.

## 📈 Key Findings

| Analysis | Result |
|---|---:|
| Average Book Price | £35.07 |
| Highest Book Price | £59.99 |
| Lowest Book Price | £10.00 |
| Average Book Rating | 2.923 |

### Book Rating Distribution

| Rating | Number of Books |
|---|---:|
| 1 Star | 226 |
| 2 Stars | 196 |
| 3 Stars | 203 |
| 4 Stars | 179 |
| 5 Stars | 196 |

## 📁 Project Structure

text
Python-Web-Scraping-Books-Analysis/
│
├── Web_Scraping_Books_Analysis.ipynb
├── all_books_data.csv
└── README.md


## 🚀 How to Run This Project

### Step 1: Clone the Repository


git clone YOUR_GITHUB_REPOSITORY_URL


### Step 2: Navigate to the Project Folder


cd Python-Web-Scraping-Books-Analysis


### Step 3: Install Required Libraries


pip install requests beautifulsoup4 pandas matplotlib


### Step 4: Open Jupyter Notebook


jupyter notebook


### Step 5: Run the Notebook

Open Web_Scraping_Books_Analysis.ipynb and execute the cells step by step.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Web scraping with Python.
- Working with HTML structures.
- Extracting data using BeautifulSoup.
- Sending HTTP requests using Requests.
- Data cleaning and preprocessing.
- Data manipulation using Pandas.
- Exploratory data analysis.
- Data visualization using Matplotlib.
- Exporting and validating datasets.

## 🌐 Data Source

[Books to Scrape](https://books.toscrape.com/)

This website is designed for practicing web scraping.

---

**Project Category:** Python | Web Scraping | Data Analysis

**Author:** Ratheena Aaskeen
