E-Commerce Sales & Customer Behaviour Analysis
A complete Data Analysis project built in Python that cleans, explores, and extracts business insights from a raw e-commerce transactional dataset containing 100,500 records.

Project Structure
├── Project.ipynb                  # Jupyter Notebook with full analysis
├── ecommerce_dirty_dataset.csv    # Raw dataset (input)
├── cleaned_dataset.csv            # Cleaned dataset (output)
├── Project_Documentation.docx    # Full project documentation
├── Executive_Summary.pdf          # One-page business summary
└── README.md

Overview
This project simulates a real-world Data Analyst role in an E-Commerce company. The dataset contains raw transactional information including order details, customer segments, product categories, sales, profit, discounts, shipping costs, and payment methods. The dataset was intentionally designed with quality issues to demonstrate end-to-end data cleaning and analysis skills.

Tools & Libraries
ToolPurposePythonCore programming languagePandasData manipulation and cleaningMatplotlibData visualizationSeabornStatistical plottingJupyter NotebookDevelopment environment

Project Phases
Phase 1 — Data Cleaning

Basic inspection: shape, dtypes, missing values, duplicates
Missing value handling using mode and median imputation
Duplicate removal
Data type correction for date columns
Logical validation: negative sales, date inconsistencies, high discounts, abnormal shipping costs
Profit outlier detection using IQR method
Product category standardization and sub-category remapping

Phase 2 — Exploratory Data Analysis (EDA)

Univariate Analysis — Distribution, skewness, and outliers for Sales, Profit, Discount, Quantity, Shipping Cost
Categorical Analysis — Sales by Region, Customer Segment, Product Category, Top 10 Products and States
Bivariate Analysis — Sales vs Profit, Discount vs Profit, Shipping Cost vs Profit, Category vs Profit
Time-Based Analysis — Monthly trends, quarterly growth, seasonal patterns, best and worst months
Customer Analysis — Pareto analysis, repeat customer behaviour, average order value per segment
Correlation Analysis — Full correlation matrix with relationship categorization

Phase 3 — Business Insights
Answered 6 key business questions backed entirely by data:

Which region is most profitable?
Which product category should be promoted?
Is the discount strategy hurting profitability?
Which customer segment generates the most revenue?
Is shipping cost impacting margins?
Five actionable business recommendations

Phase 4 — Visualizations
17 meaningful charts created including histograms, scatter plots, box plots, bar charts, and line charts with labeled axes and insight commentary.

Key Findings

East region is the most profitable with an average profit of ₹12,948 per transaction
Consumer segment generates the highest total revenue; Corporate leads in Average Order Value (₹52,121)
Top 20% of customers contribute 29.84% of total revenue
4,000 repeat customers identified — 100% repeat rate
Sales & Profit have a strong positive correlation of 0.777
Discount & Profit have a weak negative correlation of -0.066
December is the best month (₹447.9M); February is the worst (₹385.9M)
Clothing consistently underperforms in both sales and profit


Business Recommendations

Improve Low-Performing Product Categories — Review pricing, cost structure, and marketing for Clothing
Leverage High-Revenue Customer Segments — Personalized campaigns to increase customer lifetime value
Optimize Discount Strategy — Cap discounts at 40%; eliminate discounts above 80%
Enhance Data Monitoring and Reporting — Build real-time dashboards for sales, profit, and customer metrics
Control Shipping Costs — Negotiate logistics contracts or set minimum order value for free shipping


How to Run

Clone the repository

bashgit clone https://github.com/your-username/ecommerce-analysis.git
cd ecommerce-analysis

Install required libraries

bashpip install pandas matplotlib seaborn jupyter

Launch the notebook

bashjupyter notebook Project.ipynb

Dataset
The dataset (ecommerce_dirty_dataset.csv) contains 100,500 rows and 16 columns:
Order_ID, Order_Date, Ship_Date, Customer_ID, Customer_Segment, Region, State, Product_Category, Sub_Category, Product_Name, Sales, Quantity, Discount, Profit, Shipping_Cost, Payment_Mode

Note: The dataset contains intentional quality issues as part of the project scope.


Author

Manoj Kommoju
linked in : https://www.linkedin.com/in/manoj-k-695156348
github username : Mano6669
