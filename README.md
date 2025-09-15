# **Project Overview**
This project showcases a comprehensive data analysis journey—from sourcing and cleaning open data to conducting advanced analytics and presenting insights through an interactive Tableau dashboard. The goal is to transform raw data into a compelling visual story that supports decision-making and demonstrates my analytical skills.

 # **Objectives**
- Conduct exploratory and advanced analytics using Python
- Develop hypotheses and test them using regression, clustering, and time-series techniques
- Create a geospatial analysis using shapefiles
- Design and publish an interactive Tableau dashboard that narrates the analytical journey

 # **Datasets Source & Description**
This project utilizes data from the World Happiness Report dataset on Kaggle (https://www.kaggle.com/datasets/unsdsn/world-happiness), compiled by the **Sustainable Development Solutions Network**. The dataset is based on responses from the Gallup World Poll and ranks countries by their average happiness scores across multiple years (2015–2019).

Each country's happiness score is derived from a life evaluation question known as the Cantril Ladder, where respondents rate their current lives on a scale from 0 (worst possible life) to 10 (best possible life). The dataset includes:
- **Country and Region:** Geographical identifiers
- **Happiness Score and Rank:** Overall score and global ranking
- **Standard Error:** Confidence interval for the score
- **Key Contributing Factors:**
  - GDP per Capita (Economic production)
  - Family (Social support)
  - Life Expectancy (Health)
  - Freedom to make life choices
  - Generosity
  - Trust (Perception of government corruption)
- **Dystopia Residual:** A benchmark metric comparing each country to a hypothetical least-happy nation. This feature was excluded from the analysis because they are difficult to measure consistently across all countries.

 # **Analytical Techniques**
- Exploratory visual analysis (scatterplots, heatmaps, pair plots)
- Geospatial mapping using Python
- Regression modeling
- K-means clustering
- Time-series decomposition and stationarity testing

# **Dashboard Features**
Built in Tableau Public, the dashboard includes:

- Introduction page with project context, Hypotheses, research questions and data source
- Visuals from exploratory analysis 
- Geospatial insights
- Results from regression, clustering, and time-series analysis
- Summary of findings, limitations, and next steps

 # **Repository Contents**
- Clean, well-commented Python scripts (Jupyter notebooks)
- Logical folder structure with industry-standard naming
- README file detailing:
    - Project description
    - Data sources
    - Research questions
    - Cleaning procedures
    - Tableau dashboard:  https://public.tableau.com/app/profile/olufemi.ige/viz/GlobalHappinessStory2019/HappinessStory2019 
