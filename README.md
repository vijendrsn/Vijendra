
Description:

This repository contains an in-depth Exploratory Data Analysis (EDA) of the 2023 New York City Yellow Taxi Trip dataset, aimed at optimizing taxi operations. The analysis covers a comprehensive range of tasks, from data loading and cleaning to detailed insights and strategic recommendations.

**Key Objectives & Tasks:**

* **Data Preparation:**
    * Loading and sampling data from monthly Parquet files.
    * Combining datasets and handling data inconsistencies.
* **Data Cleaning:**
    * Fixing column formats and index issues.
    * Addressing missing values in critical columns like `passenger_count`, `RatecodeID`, and `congestion_surcharge`.
    * Handling outliers in `payment_type`, `trip_distance`, and `tip_amount`.
* **Exploratory Data Analysis (EDA):**
    * General EDA:
        * Categorizing variables and analyzing distributions.
        * Identifying peak hours, days, and months for taxi pickups.
        * Filtering and analyzing fare, distance, and tip data.
        * Analyzing monthly revenue trends and quarterly contributions.
        * Visualizing relationships between distance and fare, and fare/tips and trips/passengers.
        * Analyzing payment type distributions.
        * Integrating taxi zone shapefile data for geospatial analysis.
        * Mapping trip counts by zone.
    * Detailed EDA:
        * Identifying slow routes and busy hours.
        * Scaling trip counts for actual traffic volume estimation.
        * Comparing weekday and weekend hourly traffic.
        * Identifying top pickup and drop-off zones.
        * Analyzing pickup/drop-off ratios and night-time traffic.
        * Comparing revenue shares between day and night.
        * Analyzing fare per mile per passenger and by time/day.
        * Comparing vendor fare rates and tip percentages.
        * Analyzing passenger count trends and variations across zones.
        * Identifying patterns in extra charge applications.
* **Conclusions and Recommendations:**
    * Providing data-driven recommendations for optimized routing and dispatching.
    * Suggesting strategic cab positioning based on demand patterns.
    * Proposing adjustments to pricing strategies for revenue maximization.

**Technologies Used:**

* Python (Pandas, NumPy, Matplotlib, Seaborn, GeoPandas)
* Parquet file handling
* Jupyter Notebooks

**Expected Outcomes:**

* A well-structured EDA report with detailed visualizations and insightful findings.
* Actionable recommendations for optimizing NYC taxi operations.
* A reproducible analysis pipeline.

This project demonstrates a thorough approach to leveraging taxi trip data for operational improvements, strategic planning, and enhanced passenger experience in New York City.

