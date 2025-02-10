# Insurance Data Analysis | MySQL, Power BI, Python

This project focuses on performing a comprehensive data analysis of insurance-related data, leveraging MySQL, Power BI, and Python to gain actionable insights. The project includes data analysis, dynamic visualizations, sentiment analysis, and the integration of role-level security (RLS) to enhance data privacy and compliance.

## Key Features

- **MySQL Data Import**: Imported over 1,000 rows of insurance data into MySQL Server for structured analysis.
- **Dynamic Visualizations in Power BI**: Created various visualizations such as slicers, bar charts, donut charts, and ribbon charts to uncover key trends and insights on policies and claims.
- **Role-Level Security (RLS)**: Implemented RLS in Power BI, enabling controlled access to sensitive data based on user roles, ensuring compliance with privacy standards.
- **Sentiment Analysis Integration**: Integrated sentiment analysis with Power Query, improving reporting efficiency by 20%. This was particularly useful for analyzing textual data related to claims, policies, and premiums.
- **Real-Time Data Refresh**: Optimized scheduled data refreshes in Power BI, enabling real-time insights into insurance data.

## Dashboard & Visuals

Here’s a screenshot of the **Power BI Dashboard**:

![Dashboard](images/dashboard.jpg)

Additionally, a **Word Cloud** was generated to visually represent the most frequently used words from the textual data:

![Word Cloud](images/wordcloud.jpg)

## Data Files

1. **Insurance Data (data.csv)**: A CSV file containing structured data on insurance policies, claims, and premiums.
2. **Textual Data for Sentiment Analysis (textualdata.csv)**: A CSV file containing textual data used for sentiment analysis, such as customer feedback and claims descriptions.

## Technologies Used

- **MySQL**: For data storage and structured querying.
- **Power BI**: For data visualization and reporting, including slicers, bar charts, donut charts, ribbon charts, and role-level security.
- **Python**: For implementing sentiment analysis with libraries like `TextBlob` and `NLTK`.
- **Power Query**: Used to optimize data integration and refresh schedules for real-time reporting.

## Setup

### Prerequisites

- MySQL Server
- Power BI Desktop (or Power BI Service for publishing)
- Python (for sentiment analysis)

### Steps to Run

1. **Import the Data into MySQL**:
   - Load the `data.csv` file into your MySQL Server to start analyzing insurance data.
   
2. **Create Power BI Report**:
   - Import the `data.csv` and `textualdata.csv` into Power BI.
   - Build the dynamic visualizations using slicers, bar charts, and donut charts.
   - Implement Role-Level Security (RLS) to control access to sensitive data.
   
3. **Sentiment Analysis**:
   - Load the `textualdata.csv` into Python for sentiment analysis.
   - Use Python's `TextBlob` or `NLTK` to analyze sentiments and integrate the findings into Power Query in Power BI for reporting.

4. **Deploy Dashboard**:
   - Publish your Power BI report/dashboard for access by authorized users.

## Conclusion

This project provides a comprehensive analysis of insurance data, offering valuable insights into policies, claims, and customer sentiment while ensuring data privacy and compliance through RLS in Power BI. The integration of sentiment analysis enhances reporting efficiency, providing real-time insights into the insurance domain.

---


