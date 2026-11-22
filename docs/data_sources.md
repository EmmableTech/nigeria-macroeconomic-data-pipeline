Data Sources and Indicators

1. Primary Data Source

The project uses the World Bank Open Data API to retrieve publicly available macroeconomic information about Nigeria.

Website: https://data.worldbank.org/country/nigeria

API documentation: https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation

Country code: NGA

2. Selected Economic Indicators

Indicator| World Bank Code| Unit
GDP growth| NY.GDP.MKTP.KD.ZG| Annual percentage
Inflation rate| FP.CPI.TOTL.ZG| Annual percentage
Total population| SP.POP.TOTL| Number of people

3. Data Format

The World Bank API provides data in JSON format. Python will retrieve the responses and prepare them for storage and processing.

4. Data Collection Scope

The project will collect historical observations for Nigeria for each selected indicator.

The observation year, indicator name, indicator code and recorded value will be retained.

5. Data Quality Considerations

Some indicators may have missing observations for particular years. Missing values will be identified and handled during the transformation stage rather than treated as zero.

6. Source Reliability

The World Bank is the primary source for all three selected indicators. Source information will be retained to support data traceability.
