**Data Analytics Project I: Data Cleaning, Combining, and Pivot Table Creation**

In the initial phase of the Data Analytics Project I, the primary focus was on ensuring the integrity and completeness of the raw data, a crucial step in any data analysis endeavor. The process involved several key steps to clean and combine disparate datasets for a comprehensive analysis.

**Data Cleaning and Combining:**

*Step 1:* The first step involved a thorough examination of the provided raw data to verify clarity and identify any missing values. This meticulous check ensured the dataset's quality and completeness.

*Step 2:* Subsequently, the Orders table was merged with the Customers and Products tables, creating a unified dataset that incorporated essential information from multiple sources.

*Step 3:* A critical aspect of data integration was performed through the utilization of the XLOOKUP function. This involved cross-referencing the Orders and Customers tables using the customer ID on the Customer Sheet, allowing for the retrieval of additional information such as E-mail and Country.

*Step 4:* The Index and Match functions were applied to map specific attributes, including Coffee Type, Roast, Type, Size, Unit Price, and Sales. This systematic process facilitated the automation of value population for these attributes.

*Step 5:* To standardize the currency, Unit Price, and Sales were converted to Indian Rupees, ensuring consistency in the analysis.

*Step 6:* The project then proceeded to calculate Sales by multiplying the Quantity and Unit Price, providing a key metric for performance assessment.

**Pivot Table Creation:**

*Step 7:* The focus then shifted to the creation of Pivot Tables for a structured analysis. This involved selecting all columns and rows in the Orders Table and creating a Pivot Table, offering a comprehensive overview of the data.

*Steps 8-9:* Initial pivot tables were generated, featuring Line Charts for coffee flavors over the years and Bar Charts depicting Total Sales by country and the Top 5 Customers. Display options, such as Ascending and Top 5, were highlighted, providing flexibility in data presentation.

*Steps 10-11:* To enhance the user experience and create a dynamic dashboard, Slicers and Timeliners options were incorporated. These features allowed for easy customization by enabling users to select specific parameters such as Size and Type, with corresponding charts dynamically adjusting. The final touch involved arranging the charts for an intuitive and dynamic view of the dashboard.

In essence, this meticulous process of data cleaning, combining, and pivot table creation lays the foundation for a robust and insightful data analytics project, providing a comprehensive understanding of the dataset at hand.
