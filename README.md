# Social Media Advertising Performance Analysis

## Project Overview

This project analyzes social media advertising performance using Python to identify performance patterns across advertising platforms, audience segments, devices, ad types, and ad categories.

The analysis focuses on Facebook and Instagram, using key performance indicators (KPIs) such as clicks, Click-Through Rate (CTR), engagement, and conversions to generate actionable business insights and recommendations.

**Dataset:** 500 records and 16 columns. The dataset is simulated based on a Kaggle social media advertising dataset.

## Business Objectives

The project aims to answer the following questions:

- Which platform demonstrates stronger advertising performance?
- Which age group shows the strongest conversion performance?
- How does device type relate to conversion performance?
- Which ad formats achieve higher CTR?
- Which advertising categories perform better on each platform?
- How is engagement associated with CTR and conversions?
- What actions could improve future advertising campaigns?

## Tools & Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualizations
- **Jupyter Notebook** — Analysis environment

## Methodology

### 1. Data Cleaning
- Inspected dataset structure and data types.
- Checked for missing values and duplicate records.
- Reviewed descriptive statistics.
- Investigated potential outliers using the IQR method.

### 2. Feature Engineering
Created additional performance metrics:

- **CTR:** Clicks / Impressions × 100
- **Conversion Rate:** Conversions / Clicks × 100
- **Age Groups:** Grouped users into age segments for comparative analysis.

### 3. Exploratory Data Analysis (EDA)
Analyzed advertising performance by platform, age group, device, ad type, ad category, and other available variables.

### 4. Correlation Analysis
Examined relationships between engagement, CTR, clicks, time spent on ads, and conversions.

### 5. Business Insights
Translated analytical findings into recommendations for campaign testing and optimization.

## Key Findings

### 1. Instagram Showed Stronger Overall Performance

| Metric | Facebook | Instagram |
|---|---:|---:|
| Total Clicks | 1,086 | 1,174 |
| Average CTR | 52.35% | 55.57% |
| Average Engagement Score | 0.502 | 0.538 |
| Total Conversions | 110 | 125 |

Instagram performed better across these metrics in the analyzed dataset.

### 2. The 25–34 Age Group Was a Strong Audience Segment

The 25–34 age group achieved conversion rates of 52% on Facebook and 55% on Instagram. Instagram engagement for this age group reached 0.57.

This segment is a promising candidate for further audience-targeting tests.

### 3. Instagram Mobile Showed Strong Conversion Performance

The observed conversion rate was 56% for Instagram Mobile, compared with 42% for Facebook Mobile.

This suggests that mobile-focused campaign testing may be valuable.

### 4. Video and Image Ads Had Higher CTR on Instagram

| Ad Type | Average CTR |
|---|---:|
| Video | 57.63% |
| Image | 57.41% |
| Carousel | 51.69% |

Video and Image formats showed stronger CTR than Carousel ads in the analyzed Instagram data. Further testing is needed to compare conversion outcomes and costs.

### 5. Top-Performing Ad Categories Differed by Platform

**Instagram:**
- Sportswear: 64.36% CTR
- Luggage: 57.07% CTR
- Food & Beverage: 56.41% CTR

**Facebook:**
- Electronics: 59.92% CTR
- Luggage: 55.31% CTR
- Gadgets: 52.58% CTR

These results suggest that category-specific advertising strategies may be worth testing on each platform.

### 6. Engagement Was Strongly Associated with Conversion

| Variables | Correlation |
|---|---:|
| Engagement and Conversion | 0.813 |
| Engagement and CTR | 0.754 |
| Clicks and CTR | 0.691 |
| Clicks and Engagement | 0.517 |
| Time Spent and Engagement | 0.405 |

Engagement showed a strong positive association with conversion and CTR. However, correlation does not prove causation.

## Business Recommendations

Based on the analysis:

1. **Prioritize Instagram testing:** Test Instagram campaigns while continuing to monitor Facebook performance.
2. **Focus on the 25–34 segment:** Experiment with audience-specific messages, offers, and creatives.
3. **Optimize for mobile:** Review ad creatives and landing pages for mobile usability.
4. **Test Video and Image formats:** Run A/B tests to compare CTR, conversions, and costs across creative formats.
5. **Use platform-specific strategies:** Test different categories and messages on Facebook and Instagram.
6. **Monitor multiple KPIs:** Evaluate CTR, engagement, conversion rate, and total conversions together rather than relying on clicks alone.

## Data Quality & Limitations

- Dataset size: 500 rows × 16 columns.
- Missing values: 0.
- Duplicate rows: 0.
- No IQR outliers were detected in the numerical variables tested.

**Important limitations:**

- The dataset is simulated and should not be treated as evidence of real-world campaign results.
- Advertising spend, revenue, CPM, CPC, and ROAS are not included in this analysis.
- High CTR values should be interpreted carefully when impressions are very low.
- The reported average CTR is based on the mean of row-level CTR values; it is not necessarily the same as total clicks divided by total impressions.
- Correlation indicates association, not causation.

These limitations mean that the analysis cannot establish which platform is the most profitable.

## Conclusion

The analysis found stronger overall performance for Instagram than Facebook across clicks, average CTR, engagement, and conversions within this dataset.

The 25–34 age group and Instagram Mobile were promising segments, while Video and Image ads showed strong CTR on Instagram. Engagement was also positively associated with conversion.

These findings can guide future campaign experiments. Real-world decisions should be validated using actual campaign data, controlled tests, and financial performance metrics.

## Project Files

- `SOCIALMEDIA PYTHON.ipynb` — Python analysis, calculations, and visualizations.
- `README.md` — Project overview, findings, and recommendations.
- `Social_Media_Ads_Report.pdf` — Detailed project report, if included in the repository.

## Skills Demonstrated

Python | Pandas | NumPy | EDA | Data Cleaning | Feature Engineering | KPI Analysis | Correlation Analysis | Data Visualization | Business Insights


