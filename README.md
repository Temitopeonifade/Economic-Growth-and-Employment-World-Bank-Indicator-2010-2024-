Economic Growth and Employment Analysis using World Development Indicators (2010–2024)

Project Overview

This project analyzes the relationship between economic growth and employment using the World Bank World Development Indicators (WDI) dataset. The objective is to explore how economic performance influences employment outcomes across 266 countries between 2010 and 2024.

The analysis was carried out using Python for data cleaning and preparation, while Power BI was used to build an interactive dashboard for visualization and insight generation.


Project Objectives
 • Analyze trends in economic growth across countries.
 • Examine unemployment and labor force participation over time.
 • Compare GDP per capita among countries.
 • Explore the relationship between GDP growth and unemployment.
 • Build an interactive dashboard to support data-driven decision-making.


Dataset

Source: World Bank – World Development Indicators (WDI)

The dataset contains economic and employment indicators for countries worldwide.

Indicators Used
 • GDP growth (annual %)
 • GDP per capita (current US$)
 • Unemployment, total (% of total labor force)
 • Employment-to-population ratio
 • Labor force participation rate
 • Population, total

Period Covered: 2010–2024

Tools Used
 • Python (Pandas) – Data cleaning and transformation
 • Jupyter Notebook in Google colab – Data preprocessing
 • Power BI – Interactive dashboard development
 • GitHub – Project documentation and version control


Data Loading and Cleaning (Python)

The dataset was imported into Google colab using the Pandas library for preprocessing before visualization.

Data Cleaning Process
 • Loaded the World Development Indicators CSV dataset into a Pandas DataFrame.
 • Filtered the dataset to retain only indicators relevant to economic growth and employment.
 • Selected the analysis period (2010–2024).
 • Removed unnecessary indicator records and year columns outside the analysis scope.
 • Checked for and handled missing values.
 • Removed duplicate records.
 • Converted the dataset from wide format to long format using the melt() function, creating the following structure:
 • Country Name
 • Country Code
 • Indicator Name
 • Indicator Code
 • Year
 • Value
 • Exported the cleaned dataset as a CSV file for Power BI.


Data Visualization (Power BI)

The cleaned dataset was imported into Power BI to create an interactive dashboard.

Dashboard Features

KPI Cards
 • Total Countries
 • Average GDP Growth (%)
 • Average GDP per Capita (US$)
 • Average Labor Force Participation Rate (%)
 • Average Population
 • Average Unemployment Rate (%)

Visualizations
 • GDP Growth Trend (2010–2024)
 • Unemployment Trend (2010–2024)
 • GDP Growth vs. Unemployment (Scatter Plot)
 • Top 10 Countries by GDP per Capita
 • Labor Force Participation Rate by Country

Interactive Filters
 • Country Name
 • Year

These filters allow users to explore country-specific and year-specific economic performance.


Key Insights

What does the data reveal?
 • GDP growth fluctuated noticeably between 2010 and 2024, with a sharp decline around 2020 followed by a strong recovery in 2021.
 • Unemployment generally declined over the study period but declined massively in 2020 with averag of 7.16, although temporary increases were observed during periods of economic disruption.
 • GDP per capita varies significantly across countries, indicating considerable differences in income levels and economic development.
 • Labor force participation rates remain relatively stable across many countries, suggesting consistent workforce engagement despite economic fluctuations.

What trends or patterns were discovered?
 • The economic downturn around 2020 was followed by a strong rebound in GDP growth, reflecting global recovery after major disruptions.
 • Countries with higher GDP growth generally tend to experience lower unemployment, although the relationship is not perfectly linear.
 • High-income economies consistently rank among the countries with the highest GDP per capita.
 • The scatter plot indicates that employment outcomes are influenced by multiple factors beyond economic growth alone.
 
Most Important Findings
 • Economic growth contributes to improved employment outcomes but does not automatically eliminate unemployment.
 • Considerable disparities exist in GDP per capita across countries.
 • Labor market performance differs significantly among countries despite experiencing similar levels of economic growth.
 • Continuous monitoring of both economic and labor market indicators is essential for understanding sustainable development.


Recommendations

Actions for Stakeholders
 • Develop policies that promote sustainable economic growth while creating quality employment opportunities.
 • Increase investment in sectors with high job creation potential, such as manufacturing, technology, agriculture, and infrastructure.
 • Strengthen workforce development through education, vocational training, and skills acquisition programs.
 • Monitor labor market indicators alongside GDP growth to evaluate the effectiveness of economic policies.

Opportunities and Risks

Opportunities
 • Strong economic growth can improve living standards and increase employment opportunities.
 • Countries with growing GDP can attract more domestic and foreign investment.
 • Data-driven policymaking can improve resource allocation and economic planning.

Risks
 • Economic growth without sufficient job creation may result in persistent unemployment.
 • External economic shocks can quickly reverse growth and negatively affect labor markets.
 • Large income disparities may widen if economic benefits are not distributed equitably.

Decision-Making Support

The dashboard provides policymakers, researchers, and development practitioners with an interactive tool to:
 • Monitor economic and employment performance across countries.
 • Compare development indicators over time.
 • Identify countries requiring targeted economic interventions.
 • Evaluate the relationship between economic growth and labor market outcomes.
 • Support evidence-based policy formulation and strategic planning.


Dashboard Preview

The Power BI dashboard provides an interactive overview of key economic and employment indicators, enabling users to explore trends, compare countries, and derive actionable insights through dynamic filters and visualizations.


Conclusion

This project demonstrates an end-to-end data analytics workflow, from data cleaning in Python to interactive dashboard development in Power BI. By leveraging the World Bank World Development Indicators dataset, the analysis provides valuable insights into the relationship between economic growth and employment, highlighting how data visualization can support informed decision-making and sustainable development planning.

Contributor - Onifade Rofiat 
