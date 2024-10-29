# SpatialData
## Analysis of positive COVID-19 diagnosis in Peru (2020-2024)
This project graphically analyzes the spread of COVID-19 in Peru between 2020 and 2024 using georeferenced data. Spatial correlation, local spatial correlation, and local bivariate spatial correlation are conducted
The positive COVID-19 data can be downloaded from the gobernment website: https://www.datosabiertos.gob.pe/dataset/casos-positivos-por-covid-19-ministerio-de-salud-minsa

## Dictionary of Variables
| Variable              | Description                                                                                                       |
|-----------------------|-------------------------------------------------------------------------------------------------------------------|
|DEPARTAMENTO           |Department where the person confirmed as a positive COVID-19 case resides                                          |
|PROVINCIA              |Province where the person confirmed as a positive COVID-19 case resides                                            |
|FECHA_RESULTADO        |Date of the COVID-19 test result                                                                                   |
|ANO                    |Year of the COVID-19 test result                                                                                   |
|LOCATION               |Department + Province where the person confirmed as a positive COVID-19 case resides                               |                               
|YEAR2021_QT            |Transformed values of COVID cases in 2021 to a normal distribution (Quantile Transformation)                       |
|YEAR2022_QT            |Transformed values of COVID cases in 2022 to a normal distribution (Quantile Transformation)                       |
|YEAR2023_QT            |Transformed values of COVID cases in 2023 to a normal distribution (Quantile Transformation)                       |
|YEAR2024_QT            |Transformed values of COVID cases in 2023 to a normal distribution (Quantile Transformation)                       |
|COVID_QUADRANT_2021    |Indicates the presence of significant spatial clusters of COVID cases in 2021, where values represent cluster types|
|COVID_QUADRANT_2022    |Indicates the presence of significant spatial clusters of COVID cases in 2022, where values represent cluster types|
|COVID_QUADRANT_2023    |Indicates the presence of significant spatial clusters of COVID cases in 2023, where values represent cluster types|
|COVID_QUADRANT_2024    |Indicates the presence of significant spatial clusters of COVID cases in 2024, where values represent cluster types|
|COVID_Q_NAMES_2021     |Assigns descriptive labels to the spatial clustering results of COVID cases in 2021                                |
|COVID_Q_NAMES_2022     |Assigns descriptive labels to the spatial clustering results of COVID cases in 2022                                |
|COVID_Q_NAMES_2023     |Assigns descriptive labels to the spatial clustering results of COVID cases in 2023                                |
|COVID_Q_NAMES_2024     |Assigns descriptive labels to the spatial clustering results of COVID cases in 2024                                |
|LISACOVID_BV_20_21     |Represents the results of the Local Bivariate Moran's I analysis for COVID-19 cases in 2020 and 2021               |
|LISACOVID_BV_21_22     |Represents the results of the Local Bivariate Moran's I analysis for COVID-19 cases in 2021 and 2022               |
|LISACOVID_BV_22_23     |Represents the results of the Local Bivariate Moran's I analysis for COVID-19 cases in 2022 and 2023               |
|LISACOVID_BV_23_24     |Represents the results of the Local Bivariate Moran's I analysis for COVID-19 cases in 2023 and 2024               |
