# Superstore LRFM Analysis
>`AIMAR MOHAMMAD BUTRAGUENO` - `JCDS 2804`

# **Dataset Overview**
| Column | Description |
| -- | --- |
| Row ID | Unique ID for each row |
| Order ID | Unique Order ID for each Customer |
| Order Date | Order Date of the product |
| Ship Date | Shipping Date of the Product |
| Ship Mode | Shipping Mode specified by the Customer |
| Customer ID | Unique ID to identify each Customer |
| Customer Name | Name of the Customer |
| Segment | The segment where the Customer belongs |
| Country | Country of residence of the Customer |
| City | City of residence of of the Customer |
| State | State of residence of the Customer |
| Postal Code | Postal Code of every Customer |
| Region | Region where the Customer belong |
| Product ID | Unique ID of the Product |
| Category | Category of the product ordered |
| Sub-Category | Sub-Category of the product ordered |
| Product Name | Name of the Product |
| Sales | Sales of the Product |
| Quantity | Quantity of the Product |
| Discount | Discount provided |
| Profit | Profit/Loss incurred |

# **Insight**
- The dataset contains over 5,000 customer transactions.
- The following metrics were derived for LRFM segmentation:
  - Recency: Days since the most recent transaction.
  - Length: Time span between a customer’s first and last transaction.
  - Frequency: Number of unique orders per customer.
  - Monetary: Total spending by each customer.
- Missing values are minimal and do not affect LRFM calculations.
- Two segmentation approaches were used:
  - Rule-Based Segmentation using quantile-based scoring on LRFM values.
  - K-Means Clustering to validate segments and identify new behavioral patterns.
- Insights from this analysis support:
  - Identification of loyal, at-risk, and high-value customers.
  - Targeted marketing strategies and campaign personalization.
  - Designing retention and loyalty programs based on customer value.

# **Data Source**
Data Analysis Superstore
> https://console.cloud.google.com/bigquery?invt=Abuvbw&orgonly=true&project=jcds-2804-022&supportedpurview=organizationId,folder,project&ws=!1m5!1m4!4m3!1sjcds-2804-022!2ssuperstore_dataset!3sSample_Superstore_Clean

Data LRFM Anlysis
> https://console.cloud.google.com/bigquery?invt=Abuvbw&orgonly=true&project=jcds-2804-022&supportedpurview=organizationId,folder,project&ws=!1m5!1m4!4m3!1sjcds-2804-022!2ssuperstore_dataset!3sSuperstore_LRFM_Segmented
