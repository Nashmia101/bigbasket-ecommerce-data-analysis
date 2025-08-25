BigBasket E-commerce Data Analytics & Business Intelligence
Comprehensive data wrangling and business intelligence pipeline implementing advanced statistical techniques for e-commerce dataset analysis, featuring systematic data quality enhancement, outlier detection algorithms, and actionable pricing strategy optimization with 87.7% data retention efficiency.
Problem 1 – E-commerce Data Quality Enhancement

Task: Transform raw BigBasket e-commerce dataset with 27,561 observations into analysis-ready format through systematic data manipulation strategies.
Constraints:

Handle 8,626 missing values (31.3% of rating data) without losing data integrity
Remove duplicate entries while preserving unique product information
Eliminate price outliers without compromising statistical validity
Maintain business-relevant data relationships for downstream analysis



Approach

Modeled as a four-stage data transformation pipeline with sequential quality enhancement.
Built systematic approach with missing values → duplicates → outliers → feature engineering.
Applied median imputation for skewed distributions to preserve data characteristics without bias.
Implemented IQR-based outlier detection (1.5×IQR rule) for both sale_price and market_price variables.
Included feature engineering phase to create analytical variables (price_difference, discount_rate, rating_category).

Problem 2 – Business Intelligence & Strategic Analysis

Task: Generate actionable business insights for pricing optimization, inventory management, and revenue enhancement strategies.
Constraints:

Identify top 100 highest-discount products across all categories
Determine optimal product correlation strategies for cross-selling
Classify products into performance tiers based on customer ratings
Provide data-driven recommendations for business decision making



Approach

Built a discount rate analysis framework with descending sort algorithms to identify high-discount products.
Implemented iterative search methodology to find highest profit-margin products for strategic correlation.
Applied conditional classification logic for rating-based performance segmentation (High ≥4.0, Average 2.5-3.99, Poor <2.5).
Developed cross-sell optimization strategy through product complementarity analysis for revenue maximization.

Results

Implemented a working data quality enhancement system achieving 87.7% data retention with complete missing value elimination.
Implemented a business intelligence framework generating 4+ actionable recommendations for pricing and inventory optimization.
Both solutions documented with statistical validation and business impact analysis.

Technical Performance

Data Quality Enhancement: 100% missing value elimination, 368 duplicate records removed, 3,377 outliers handled
Feature Engineering: 300% increase in analytical variables with successful validation
Business Intelligence: Kitchen, Garden & Pets category identified as high-discount segment, Steel Storage Deep Dabba identified as optimal cross-sell product
Processing Efficiency: O(n log n) time complexity for sorting operations, O(n) space complexity with optimized memory management

Technologies & Implementation

Programming Environment: R Programming with Quarto framework for reproducible analysis
Libraries: dplyr (data manipulation), readr (data import), tidyverse ecosystem
Statistical Methods: IQR-based outlier detection, median imputation, quantile analysis, conditional logic systems
Business Logic: Iterative search algorithms, sorting mechanisms, classification frameworks

Author
Nashmia Shakeel
