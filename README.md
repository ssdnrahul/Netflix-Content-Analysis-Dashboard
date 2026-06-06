# 🎬 Netflix Content Analysis Dashboard

## 📌 Project Overview

This project analyzes Netflix Movies and TV Shows data using Power BI to uncover content trends, audience engagement patterns, IMDb rating behavior, and content performance insights.

The dashboard was developed to answer key business questions around content quality, popularity, release trends, and viewer preferences. By combining IMDb ratings with audience votes, the project provides a more reliable measure of content success.

---

## 🎯 Project Objective

The objective of this project was to:

- Analyze Netflix content performance using IMDb ratings and votes.
- Understand content release trends over time.
- Identify the highest-performing Movies and TV Shows.
- Evaluate audience engagement patterns.
- Analyze the relationship between age certification and ratings.
- Generate actionable business recommendations through data visualization.

---

## 💼 Business Problem

Netflix continuously invests in content production and acquisition. To make informed content strategy decisions, the business needs to answer questions such as:

- Which titles perform best?
- How has content production changed over time?
- Are ratings improving or declining?
- Which audience segments engage the most?
- How does age certification impact ratings?
- What content characteristics drive better performance?

This dashboard helps answer these questions using historical Netflix content data.

---

## 🛠 Tools & Technologies Used

- Power BI
- Power Query
- Microsoft Excel
- Data Visualization
- Business Intelligence

---

## 📊 Dashboard Preview

![Dashboard](Dashboard.png)

---

## 📈 Key KPIs

| KPI | Value |
|------|--------|
| Total Titles | 5,283 |
| Total Movies | 3,407 |
| Total TV Shows | 1,876 |
| Average IMDb Rating | 6.53 |
| Total IMDb Votes | 123 Million |

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed using Power Query:

- Removed unnecessary columns such as `index` and `imdb_id`.
- Reviewed missing values in IMDb Votes.
- Created a custom metric:

### Score × Votes

```text
IMDb Score × IMDb Votes
```

This metric was created to evaluate both content quality and popularity simultaneously.

- Validated data types and numerical fields.
- Prepared the dataset for reporting and visualization.

---

## 🔍 Analysis Performed

The dashboard includes the following analyses:

### 1. Top-Rated Movies & TV Shows
Identified the highest-performing content using the custom Score × Votes metric.

### 2. Movie Release Trend
Analyzed content release patterns across different years.

### 3. IMDb Rating Trend
Evaluated how average IMDb ratings changed over time.

### 4. IMDb Votes Trend
Measured audience engagement through voting activity.

### 5. Runtime Trend
Analyzed how average runtime evolved across years.

### 6. Age Certification Analysis
Compared average ratings across certification categories.

---

## 💡 Key Insights

### Content Distribution

- Total Titles: 5,283
- Movies: 3,407 (64.5%)
- TV Shows: 1,876 (35.5%)

### Content Release Trends

- Content production increased significantly after 2010.
- The dataset is heavily skewed toward modern content releases.
- Recent years contain the highest concentration of titles.

### Content Performance

Top-performing titles include:

- Inception
- Forrest Gump
- Breaking Bad
- Django Unchained
- Saving Private Ryan

These titles achieved strong performance because they combined high ratings with large audience participation.

### IMDb Rating Trends

- Average IMDb Rating: 6.53
- Ratings remained relatively stable across most years.
- Content quality has remained consistent despite increasing content volume.

### Audience Engagement

- IMDb Votes increased significantly in recent years.
- Modern content attracts substantially more audience interaction than older releases.

### Runtime Trends

- Average runtime has gradually decreased over time.
- Viewer preferences appear to be shifting toward shorter and more consumable content.

### Age Certification Insights

- TV-14 is the highest-rated certification category.
- TV Shows generally receive higher ratings than Movies.
- PG-13 performs strongly among Movies.

---

## 🚀 Business Recommendations

Based on the analysis, the following recommendations can be made:

### 1. Invest More in TV-14 Content

TV-14 content consistently receives the highest average ratings and demonstrates strong audience appeal.

### 2. Prioritize High-Performing TV Shows

TV Shows generally outperform Movies in terms of ratings and viewer engagement.

### 3. Use Quality + Popularity Metrics

Content success should not be measured using ratings alone. Combining ratings with audience votes provides a more reliable performance indicator.

### 4. Continue Investing in Recent Content

Recent releases show the highest engagement levels and represent the strongest growth area.

### 5. Explore Shorter Content Formats

Runtime trends suggest that audiences increasingly prefer shorter and more accessible content.

---

## 📂 Repository Structure

```text
Netflix-Content-Analysis-Dashboard
│
├── README.md
├── Dashboard.png
├── Netflix_Content_Analysis.pbix
└── Netflix_Content_Dataset.xlsx
```

---

## 📁 Files Included

| File | Description |
|--------|-------------|
| Netflix_Content_Analysis.pbix | Power BI Dashboard |
| Netflix_Content_Dataset.xlsx | Source Dataset |
| Dashboard.png | Dashboard Preview |
| README.md | Project Documentation |

---

## 👨‍💻 Author

**Rahul Chhabra**
