# EDA's
In this repository, I share a few projects focused on Exploratory Data Analysis. The goal is to extract information on different Datasets, exercising Data Analysis and Visualisation skills.

If you are interested in Machine Learning, have a look at my projects [here](https://negrinij.github.io/Portfolio).

## Projects

### [Kaggle EDA Challenge 2020](https://nbviewer.jupyter.org/github/negrinij/EDA/blob/main/KaggleEDA/2020-kaggle-eda-competition.ipynb)

- Exploratory data analysis (EDA) of the most comprehensive dataset available on the state of machine learning and data science today according to the Kaggle Community
- The survey answers covered demographic, education, employment, and technology usage to learn more about data science practitioners in 2020.
- Key Insights include:
  - India, the USA and Brazil are the countries with the most survey participants
  - India is the country with the highest number of young participants (18-21 years old)
  - Female participation range from 15-20% across different countries
  - 39% of participants hold a Masters and 34% Bachelors degrees, demonstrating the importance of Formal Education
  - Almost 60% of doctorates are working as Research Scientists. Also, PhD holders account for only 7% of currently unemployed. Unfortunately, 42% of currently unemployed hold a Bachelor degree

![](../main/KaggleEDA/KaggleHeatmap.png)


### [Natural Disasters 1900-2021: An EDA](https://nbviewer.jupyter.org/github/negrinij/EDA/blob/main/EM-DAT/eda-natural-disasters.ipynb)

- This notebook explores EM-DAT data extracted from www.emdat.be. The data being analysed takes into account all continents, and presents details regarding natural disasters from 1900 to currrent date
- The database is compiled from various sources, including UN agencies, non-governmental organisations, insurance companies, research institutes and press agencies
- Key Insights:
  - The number of Natural Disasters recorded has increased over the years. While the EM-DAT has started collecting data officially from 1988, we see a proeminent upward trend starting in the 60's and seems to reach a peak in the 00's, and continue to vary around this peak to this day
  - In total, the number of disasters seem to have stabilised, however, there seems to be a trend that every two or three years there is a sharp rise
  - Metereological (e.g. Storms) and Hydrological (e.g. Floods) are the most commonly occurring types of disasters, followed by Geophysical (e.g. Volcanic Activity), Biological (e.g. Epidemic) and Climatological (e.g. Drought)
  - Climatological events have taken more lives than any other type of Natural Disasters, followed by Hydrological events
  - Hydrological events are the ones who affect most people
  - Floods (Hydro), Storms (Meteo) and Earthquakes (Geo) are the Disasters Subtypes that occurred the most since 1900. In total, 5.400 Floods, 4.400 Storms and 1.500 have been recorded since then.

![](../main/EM-DAT/DeathCountries.png)

### [Iowa House Market](https://nbviewer.jupyter.org/github/negrinij/EDA/blob/main/HouseMarketIOWA/iowa-house-market-data-analysis.ipynb)

- The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa
- In here an initial data analysis is performed to guide the next steps. The most relevant points learned from this data analysis are:
  - A strategy to handle the null values must be trialled. KNN, mean values replacement and MICE strategies need to be tested
  - There are features that are highly correlated. They could be removed or combined to simplify the dataset
  - Skewed variables are present. Feature transformation can be used to improve model performance, mainly if ANN or SVM are used
  - From the feature analysis, it was possible to obtain ideas for new features that could improve model performance.

![](../main/HouseMarketIOWA/corrMatrix.png)
