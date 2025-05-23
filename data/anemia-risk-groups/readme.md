# Share of the population with anemia in higher risk groups - Data package

This data package contains the data that powers the chart ["Share of the population with anemia in higher risk groups"](https://ourworldindata.org/grapher/anemia-risk-groups?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Women of reproductive age
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 2000–2019  
Unit: % of women ages 15-49  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) (2025) – processed by Our World in Data

#### Full citation
World Health Organization (via World Bank) (2025) – processed by Our World in Data. “Women of reproductive age” [dataset]. World Health Organization (via World Bank), “World Development Indicators” [original data].
Source: World Health Organization (via World Bank) (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank) (2025)?
Prevalence of anemia among women of reproductive age refers to the combined prevalence of both non-pregnant with haemoglobin levels below 12 g/dL and pregnant women with haemoglobin levels below 11 g/dL.

### Source

#### World Health Organization (via World Bank) – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


## Pregnant women
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 2000–2019  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) (2025) – processed by Our World in Data

#### Full citation
World Health Organization (via World Bank) (2025) – processed by Our World in Data. “Pregnant women” [dataset]. World Health Organization (via World Bank), “World Development Indicators” [original data].
Source: World Health Organization (via World Bank) (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank) (2025)?
Prevalence of anemia, pregnant women, is the percentage of pregnant women whose hemoglobin level is less than 110 grams per liter at sea level.

Limitations and exceptions: Data should be used with caution because surveys differ in quality, coverage, age group interviewed, and treatment of missing values across countries and over time.

Data on anemia are compiled by the WHO based mainly on nationally representative surveys, which measure hemoglobin in the blood. WHO's hemoglobin thresholds are then used to determine anemia status based on age, sex, and physiological status.

Statistical concept and methodology: Anemia is a condition in which the number of red blood cells or their oxygen-carrying capacity is insufficient to meet physiologic needs, which vary by age, sex, altitude, smoking status, and pregnancy status. In its severe form it is associated with fatigue, weakness, dizziness, and drowsiness. Children under age 5 and pregnant women have the highest risk for anemia.

### Source

#### World Health Organization (via World Bank) – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


## Children
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 2000–2019  
Unit: % of children under 5  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) (2025) – processed by Our World in Data

#### Full citation
World Health Organization (via World Bank) (2025) – processed by Our World in Data. “Children” [dataset]. World Health Organization (via World Bank), “World Development Indicators” [original data].
Source: World Health Organization (via World Bank) (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank) (2025)?
Prevalence of anemia, children ages 6-59 months, is the percentage of children ages 6-59 months whose hemoglobin level is less than 110 grams per liter, adjusted for altitude.

Limitations and exceptions: Data for blood haemoglobin concentrations are still limited, compared to other nutritional indicators such as hild anthropometry. As a result, the estimates may not capture the full variation across countries and regions.

Statistical concept and methodology: Data on anemia are compiled by the WHO, and a statistical model was used to estimate trends. WHO’s hemoglobin threshold concentration in blood was used.

### Source

#### World Health Organization (via World Bank) – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


    