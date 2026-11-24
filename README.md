# ⌚ E-Commerce Watch Market Intelligence & Pricing Analytics

An Excel-based data analytics project that explores Flipkart watch listings to uncover insights into brand representation, pricing patterns, discount distribution, and customer ratings through data cleaning, PivotTables, PivotCharts, and an interactive dashboard.

---

## 📌 Project Overview

The **E-Commerce Watch Market Intelligence & Pricing Analytics** project focuses on analysing watch product data collected from Flipkart.

The project follows an end-to-end Excel analytics workflow, starting with raw scraped data, transforming it into a structured dataset, performing exploratory analysis, and presenting key findings through an interactive Excel dashboard.

The analysis covers **179 watch listings across 64 brands**, helping understand product distribution, pricing segments, customer rating patterns, and highly rated products.

## 🎯 Project Objectives

- Analyse brand-wise distribution of watch listings.
- Explore original prices, special prices, and discount patterns.
- Segment products into Budget, Mid-Range, and Premium categories.
- Understand customer rating distribution.
- Compare average customer ratings across price categories.
- Identify products with high rating counts.
- Build an interactive dashboard to communicate key insights.

## 📊 Dataset Overview

| Dataset Detail         |        Information |
| ---------------------- | -----------------: |
| Marketplace            |           Flipkart |
| Data Collection Method | Chrome Web Scraper |
| Original Records       |                440 |
| Original Columns       |                 17 |
| Cleaned Records        |                179 |
| Distinct Brands        |                 64 |
| Analysis Fields        |                  7 |

### Dataset Attributes

The cleaned dataset contains the following fields:

- `Name` – Watch product name
- `Brand` – Product brand
- `Original Price` – Listed original price
- `Discount` – Discount percentage
- `Special Price` – Discounted product price
- `Rating` – Customer rating
- `Rating Count` – Recorded customer rating count

> **Note:** The dataset represents a scraped snapshot. Product prices, discounts, ratings, and availability may change over time.

## 🧹 Data Cleaning & Preparation

The raw dataset contained product information along with scraper-related metadata and text-formatted values.

The preprocessing workflow included:

- Removing unnecessary scraper metadata and URL columns.
- Cleaning discount values by removing text such as `off`.
- Converting discount values into numeric percentages.
- Cleaning and combining rating count information.
- Removing duplicate records.
- Retaining relevant product attributes for analysis.

### Feature Engineering

Two additional calculated columns were created in Excel:

**1. Price Category**

| Category  | Price Range          |
| --------- | -------------------- |
| Budget    | Below ₹500           |
| Mid-Range | ₹500 to below ₹1,500 |
| Premium   | ₹1,500 and above     |

**2. Rating Category**

| Category  | Rating Range     |
| --------- | ---------------- |
| Excellent | 4.5 and above    |
| Good      | 4.0 to below 4.5 |
| Average   | 3.0 to below 4.0 |
| Poor      | Below 3.0        |

## 🛠️ Tools & Technologies

- **Microsoft Excel** – Data cleaning, analysis, and dashboard development
- **Excel Tables** – Structured data management
- **Excel Formulas** – Calculated columns and data transformation
- **PivotTables** – Data summarisation and aggregation
- **PivotCharts** – Visual representation of analytical results
- **Slicers** – Interactive filtering
- **Data Visualization** – Dashboard design and insight presentation

## 📈 Key Performance Indicators (KPIs)

| KPI                   |     Value |
| --------------------- | --------: |
| Total Products        |       179 |
| Total Brands          |        64 |
| Average Special Price | ₹1,150.66 |
| Average Discount      |    64.56% |

## 🔍 Key Analysis & Findings

### 1. Brand Representation

- Allen Solly has the highest number of product listings, with **17 watches**.
- Fastrack follows with 15 listings.
- TIMEX has 14 listings.
- PETER ENGLAND has 13 listings.

### 2. Price Category Distribution

| Price Category | Products | Distribution |
| -------------- | -------: | -----------: |
| Budget         |       84 |       46.93% |
| Mid-Range      |       50 |       27.93% |
| Premium        |       45 |       25.14% |

**Insight:** Budget watches account for the largest share of listings in the analysed dataset.

### 3. Customer Rating Distribution

| Rating Category | Products | Distribution |
| --------------- | -------: | -----------: |
| Good            |      132 |       73.74% |
| Average         |       25 |       13.97% |
| Excellent       |       22 |       12.29% |
| Poor            |        0 |           0% |

**Insight:** Most products fall within the Good rating category.

### 4. Average Rating by Price Category

| Price Category | Average Rating |
| -------------- | -------------: |
| Budget         |           4.03 |
| Mid-Range      |           4.32 |
| Premium        |           4.39 |

**Insight:** Premium watches have the highest average customer rating in this dataset, followed by Mid-Range and Budget watches.

### 5. Most Rated Products

The analysis also identifies the top 10 watches based on their recorded rating counts to understand which listings have comparatively higher customer engagement.

## 📊 Interactive Excel Dashboard

The dashboard combines KPI cards, charts, and slicers to provide a consolidated view of the watch market analysis.

### Dashboard Visualizations

1. **Top 10 Brands by Product Count** – Compares brand representation.
2. **Watch Price Category Distribution** – Shows the distribution of products across pricing segments.
3. **Customer Rating Distribution** – Displays product distribution by rating category.
4. **Top 10 Most Rated Watches** – Highlights products with the highest rating counts.
5. **Average Customer Rating by Price Category** – Compares average ratings across price segments.

### Interactive Features

- Brand slicer for filtering dashboard analysis.
- Connected PivotTables and PivotCharts.
- Dynamic visual summaries.
- KPI cards for quick performance insights.

## 📁 Repository Structure

```text
E-Commerce-Watch-Market-Intelligence-Pricing-Analytics/
│
├── Analysis/
│   └── Excel analysis and supporting project materials
│
├── Cleaned Data/
│   └── Processed and analysis-ready dataset
│
├── Raw Data/
│   └── Original scraped dataset
│
├── Result/
│   └── Dashboard and project presentation outputs
│
└── README.md
```

## 💡 Business Insights & Interpretation

This analysis provides a descriptive view of watch listings available in the collected dataset.

- Brand-wise product counts indicate listing representation, not actual market share.
- Rating counts represent recorded customer engagement, not confirmed sales volume.
- Price-category comparisons show differences in average ratings but do not establish a causal relationship between price and customer satisfaction.
- Discount percentages and product prices reflect the collected dataset and may not represent current marketplace values.

## 🚀 How to Explore This Project

1. Clone or download this repository.
2. Open the `Raw Data` folder to review the original dataset.
3. Explore the `Cleaned Data` folder to understand the processed dataset.
4. Review the `Analysis` folder for the Excel analysis.
5. Open the files in the `Result` folder to explore the dashboard and project outputs.

## 🎓 Project Outcome

This project demonstrates practical Excel data analytics skills through an end-to-end workflow:

**Raw Data → Data Cleaning → Feature Engineering → Exploratory Analysis → PivotTables & PivotCharts → Interactive Dashboard → Business Insights**

It highlights the use of Microsoft Excel to transform raw e-commerce product data into meaningful analytical findings and visual reports.

## 🙌 Acknowledgement & Data Attribution

The dataset is based on Flipkart watch product listings. The supplied source material identifies Chrome Web Scraper as the data collection method.

---

**Project Domain:** E-Commerce Analytics | Retail Analytics | Pricing Analytics

**Primary Tool:** Microsoft Excel

**Project Type:** Data Analytics & Dashboarding

**Author:** Ashika Shrivastava

**GitHub Repository:** [E-Commerce Watch Market Intelligence & Pricing Analytics](https://github.com/Ashika20015/E-Commerce-Watch-Market-Intelligence-Pricing-Analytics)

