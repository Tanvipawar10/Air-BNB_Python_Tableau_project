**Data_Visualization_Air_BNB_Python_Tableau_project**

In the context of Airbnb operations, how can the utilization of Python, Tableau Prep, Tableau facilitate a comprehensive examination between Chicago and New Orleans.

This inquiry seeks to leverage Tableau's visual analytics capabilities to uncover and illustrate the shared attributes, disparities, and distinctive patterns inherent to Airbnb's presence in these cities, thus elevating the depth and insightfulness of the study.

For this EDA project, we have chosen the "Airbnb Listings Data" dataset from 2 major cities: Chicago and New Orleans. This dataset provides a comprehensive snapshot of various attributes related to Airbnb listings, such as property type, neighbourhood, pricing, availability, and more. The dataset is ideal for conducting an in-depth exploration of the local Airbnb market and deriving actionable insights.

**Repository files -**
Chicago_listings.csv - Chicago listings dataset
New_Orleans_listings.csv - New Orleans listings dataset
Air_BNB_Python_Tableau_project.ipynb - Google Collab Notebook used for data manipulation data wrangling with Python.
AirBNB_Tableau_Prep.csv - Appended cleaned dataset generated after Python Data Wrangling.
Tableau prep project 4.tfl - Data transformation & data manipulation done with Tableau Prep.
AirBNB_Tableau_online.csv - Dataset ready for visualization generated from tableau prep.

**Airbnb Data Visualization Link**

**Steps to proceed with the dashboard:**

**ETL Process**
**Data Cleaning:**
Addressed disorder and inconsistency in the dataset using Google Colab and Tableau Prep. This involved rectifying discrepancies, eliminating duplicates, and standardizing data formats to ensure consistency across both datasets (Chicago and New Orleans).

**Data Transformation:**
Generated supplementary columns from pre-existing categorical data by splitting and transforming extensive descriptive text. These new columns provided a clearer, structured representation of the data, making it more suitable for visualization and analysis. The transformation improved the overall readability and helped enhance insights derived from the data.

**Tableau Prep (Transformation & Load):**
Leveraged Tableau Prep's Group and Replace feature to resolve inconsistencies in neighborhood names caused by letter casing, spelling variations, or phonetic similarities. After cleaning and transforming the dataset, appended the processed data with previously cleaned datasets, preparing the final data for visualization. The refined dataset was then loaded into Tableau for visual analytics and reporting.
