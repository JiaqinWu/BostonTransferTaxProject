# Boston Transfer Tax Project
Purpose: The purpose of our research is to examine the necessity of implementing an additional transfer tax on houses in Boston.

### Web Scraping
To gather the necessary housing data for analysis, we utilized the website https://www.masslandrecords.com/suffolk/default.aspx. Specifically, we conducted web scraping in 2022, focusing on houses with UNIT DEED and DEED types. This allowed us to extract relevant information such as prices, dates, grantors, grantees, and addresses. These data points will serve as the foundation for conducting in-depth analysis.

### Data Cleaning
In order to ensure the accuracy and reliability of our analysis, we implemented data cleaning procedures. We excluded houses with prices below $100,000 and employed keywords such as LLC, LC, Trust, etc., to identify houses involving investors as grantees or grantors. Additionally, we performed analyses at both the neighborhood-level and house type-level, allowing us to gain comprehensive insights into the data.

### Data Visualization
To enhance our understanding and effectively communicate our findings, we employed data visualization techniques. By utilizing the address information and Google API, we generated latitude and longitude coordinates for each house. This enabled us to map the houses to their corresponding locations. Additionally, we incorporated a geojson file from the official Boston website (https://data.boston.gov/dataset/boston-neighborhoods) to determine the neighborhood affiliations of the addresses. This geographic visualization at the neighborhood-level in Boston provides valuable spatial context.

Furthermore, we conducted descriptive data visualization, exploring patterns and trends both at the neighborhood and month-level in Boston. These visualizations offer a comprehensive overview of the data, making it easier to identify significant insights and patterns.

# Conclusion
By employing web scraping, data cleaning, and data visualization techniques, we aim to gain a comprehensive understanding of the housing market in Boston and assess the potential benefits and implications of implementing an additional transfer tax.