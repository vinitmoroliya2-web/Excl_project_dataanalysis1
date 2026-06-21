Excl_project_dataanalysis1
Interactive Excel project analyzing bike-buying trends. Cleaned raw data, applied nested IF formulas for age brackets, and built dynamic pivot tables. Designed a sleek corporate dashboard with cross-connected slicers for interactive demographic filtering (region, education, status)—perfectly documented for my data analytics portfolio.


📊 Data Analyst Portfolio Project: End-to-End Excel Data Analytics & Interactive Dashboard

 Executive Summary

The goal of this project was to transform a raw, unorganized dataset containing customer demographic profiles into a polished, interactive business intelligence tool. By executing a rigorous data cleaning, transformation, and visualization pipeline entirely within Microsoft Excel, I built a dynamic dashboard that uncovers actionable insights into factors influencing bike purchase behavior.

 Tools & Technologies Used

Application: Microsoft Excel
Competencies: Data Deduplication, Find & Replace Standardization, Form Formatting, Pivot Tables, Pivot Charts, Slicer Cache Connections, Page Layout Alignment.



The Project Workflow

Phase 1: Data Preparation & Cleaning

To preserve data integrity, the original dataset was stored securely in a Raw Data Sheet, and all operations were performed on a dedicated Working Sheet.

Deduplication:Identified and eliminated duplicate records to ensure statistical accuracy across customer listings.
Data Standardization: Streamlined ambiguous single-letter abbreviations into user-friendly textual forms (e.g., changing `M`/`S` to `Married`/`Single`, and `M`/`F` to `Male`/`Female`). This step significantly improved final dashboard readability for non-technical stakeholders.
Format Uniformity: Standardized the `Income` field to currency formatting without altering raw numeric properties, striking a balance between aesthetic presentation and mathematical utility.

Phase 2: Data Transformation & Feature Engineering

Raw numerical attributes like age can clutter visual charts. To extract meaningful categorical trends, I implemented feature engineering:

Age Bracketing:Segmented customers into three logical life stages using a Nested IF Statement:

{Age Bracket Formula} = {IF}(L2 \le 30,"Adolescent", {IF}(L2 \le 54, {"Middle Age"}, {"Old"}))


Label Optimization: Cleaned and reorganized non-standard sorting values within the `Commute Distance` categories (such as correcting the placement of "More than 10 miles") to ensure accurate progressive formatting on chart axes.

 Phase 3: Pivot Tables & Data Analysis

Using the cleaned working dataset, I constructed multiple Pivot Tables to isolate variables and cross-examine key demographic drivers:
Income Trends:Evaluated the average income breakdown relative to gender and purchasing choices.
Commute Distribution: Aggregated customer volume against commute distances to check if physical proximity to work scales with bike ownership.
Demographic Volume:Counted total transactions across the engineered age brackets.


Phase 4: Dashboard Design & Interactive Filters

The final stage focused on user experience (UX) and dashboard interactivity:

Visual Hygiene:** Removed standard Excel gridlines to establish a clean, corporate presentation canvas.
Layout Alignment: Utilized Excel's Shape Format Align toolsets to guarantee uniform spacing and structural symmetry among charts.
Cross-Connected Slicers:Deployed interactive Slicers for `Marital Status`, `Region`, and `Education`. By linking these slicers to control all underlying pivot tables simultaneously, the user can drill down into localized demographic segments on demand.


Key Business Insights

The Sweet Spot:Middle-aged individuals (31 <= 54) represent the core consumer base, buying bikes at a drastically higher rate than adolescents or the older demographic.
Income Factor:Higher average disposable income positively correlates with bike-buying behavior across both genders.
Demographic Nuance:** Married individuals within this dataset maintain a higher average income threshold than single buyers, presenting a distinct target segment for premium marketing efforts.

