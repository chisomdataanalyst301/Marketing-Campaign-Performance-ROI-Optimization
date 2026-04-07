# Marketing-Campaign-Performance-ROI-Optimization
## Problem Statement
#### The Business Challenge
The company is investing significantly in various marketing channels (Email, Social Media, Search Engine, and Direct Mail) across multiple regions and products. However, the current budget allocation lacks a data-driven foundation, leading to inconsistent ROI and missed revenue opportunities.

#### Why it Matters
In a competitive landscape, marketing efficiency is critical. Every dollar spent must contribute to growth. Identifying high-performing channels and underperforming regions allows the business to:

#### Maximize ROI: 
Shift budget from low-yield to high-yield activities.

#### Scale Revenue: 
Focus on products and regions with the highest growth potential.

#### Reduce Waste:
Identify and eliminate inefficiencies in ad spend.
## Project Overview
This report evaluates the fiscal performance and operational efficiency of the organization’s marketing division. By auditing $261,166 in advertising expenditure across four primary digital and physical channels, this analysis seeks to identify high-yield growth opportunities and eliminate cost inefficiencies. The project concludes with a strategic reallocation plan designed to maximize total revenue and optimize the portfolio’s Return on Investment (ROI).

## Data Methodology & Governance
To ensure the integrity of the findings, a rigorous Data Quality Audit (DQA) was performed using Python.

#### Technical Process:
Normalization: Corrected naming conventions and structural errors (e.g., mislabeled date periods).

#### Financial Validation: 
Legacy ROI calculations in the raw data contained extreme outliers (due to low-spend denominators). All metrics were recalculated using a standard (Revenue / Spend) formula to ensure a consistent baseline.

#### Outlier Mitigation: 
Capped extreme statistical anomalies at the 95th percentile to prevent regional "performance noise" from skewing the strategy.
## Strategic Exploratory Analysis
Our EDA focused on the Efficiency-to-Scale ratio. We analyzed not just which channel brings in the most money, but which channel grows the most efficiently as spend increases.

#### Key Research Objectives:

Determine the "Incremental ROI" of each marketing dollar per channel.

Analyze the correlation between regional spend and conversion velocity.

Segment product performance to identify "Halo" products that drive cross-channel revenue.
## Key Insights
#### Search Engine Efficiency: 
While Email generates the highest total revenue ($302k), Search Engine marketing yields the highest average ROI (4.69), suggesting it is the most efficient channel for every dollar spent.

#### Product C Dominance: 
Product C is the primary revenue driver, contributing significantly more to the bottom line than Products A or D.

#### Regional Disparity: 
The East and West regions account for over 60% of total revenue, whereas the South region is underperforming despite moderate spend.

#### The Direct Mail Lag:
Direct Mail has the lowest ROI and the highest Cost Per Acquisition (CPA), making it the least viable channel for scaling.

#### Spend Saturation: 
The correlation between Spend and Revenue is positive but shows diminishing returns at very high spend levels, suggesting a "sweet spot" for budget allocation.
## Business Recommendations
#### Reallocate Budget: 
Shift 15% of the budget from Direct Mail to Search Engine ads to capitalize on the higher ROI.

#### Product Focus: 
Launch a targeted campaign for Product C in the South region to address the revenue gap, using the high-performing Search Engine channel.

#### Email Optimization: 
Since Email has high revenue but lower ROI than Search, perform A/B testing on Email CTR to lower the Cost Per Click (CPC).

#### Regional Strategy: 
Investigate the East region's success to create a "playbook" that can be replicated in the South to improve performance.
## Power BI Dashboard Plan
#### KPI Cards: 
Total Revenue, Average ROI, Total Conversions, and Total Ad Spend.

#### Line Chart (Revenue Trend): 
Shows revenue fluctuations by month to identify seasonality.

#### Clustered Bar Chart (Channel Performance): 
Compare Revenue vs. Spend side-by-side for each channel.

#### Donut Chart (Product Mix):
Share of total revenue by Product (A, B, C, D).

#### Slicers: 
Date Range, Product, and Marketing Channel.
## Project Storytelling 
#### The Story of Data-Driven Growth
When I first looked at this marketing dataset, the company was flying blind—spending heavily across four channels without knowing which one truly moved the needle.
I began by cleaning the data, stripping away calculation errors and inconsistencies to reveal the truth behind the numbers. My analysis uncovered a fascinating paradox: while Email brought in the most cash, Search Engine marketing was the hidden engine of efficiency, delivering 20% more value per dollar spent.
I discovered that Product C was a superstar in the East, yet almost invisible in the South. By connecting these dots, I developed a strategy to pivot the budget away from expensive, low-return 'Direct Mail' toward high-efficiency 'Search Engine' tactics. This project isn't just about charts; it's about transforming a fragmented marketing spend into a precision growth engine.
### Chisom Precious
Data Analyst | Power BI Developer | Business Analyst | Aspiring Data Scientist.

