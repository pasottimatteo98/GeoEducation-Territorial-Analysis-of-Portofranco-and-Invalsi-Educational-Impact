# GeoEducation: Territorial Analysis of Portofranco and Invalsi Educational Impact

## Overview
This project analyzes data related to Portofranco educational services and Solidarity Desks ("Banchi di Solidarietà"), correlating them with INVALSI test results across municipalities in Lombardy, Italy. The goal is to study the relationship between the presence of beneficiaries and volunteers of these services and educational outcomes at the municipal level, visualizing these relationships through choropleth maps and statistical analysis.

## Data
The project uses several datasets:
- **Volunteers - Solidarity Desks**: Data on volunteers working at Solidarity Desks
- **Beneficiaries - Solidarity Desks**: Data on beneficiaries of Solidarity Desks
- **Beneficiaries - Portofranco**: Data on beneficiaries of Portofranco educational services
- **Volunteers - Portofranco**: Data on volunteers at Portofranco
- **INVALSI Reports**: Data on standardized test results at the municipal level
- **Administrative Boundaries**: Geographic data of Italian municipalities (from ISTAT)

## Key Features
- **Segmentation of Portofranco Beneficiaries**: Analysis of beneficiaries across personal, social, and educational domains
- **Year-over-Year Comparison**: Analysis of changes in INVALSI scores between 2020-21 and 2021-22 academic years
- **Choropleth Maps**: Geographic visualization of educational outcomes and service distribution
- **Correlation Analysis**: Relationship between Portofranco presence and educational performance
- **Role Distribution**: Mapping of beneficiaries and volunteers across municipalities

## Technical Implementation
- **Data Preprocessing**: Cleaning and merging various datasets, handling missing values
- **Geographic Processing**: Integration of administrative boundaries with educational data
- **Visualization**: Custom choropleth maps and bar charts to communicate findings
- **Scaling Techniques**: Normalization of scores for comparative visualization
- **Statistical Analysis**: Calculation of mean scores and differences across domains

## Dependencies
- pandas
- geopandas
- matplotlib
- numpy
- scikit-learn
- shapely
- requests
- zipfile
- io

## Usage
1. Mount Google Drive to access the datasets
2. Run the data processing cells to integrate and clean the data
3. Execute the analysis to segment beneficiaries by domain
4. Generate choropleth maps to visualize the geographic distribution
5. Create comparative visualizations between INVALSI scores and Portofranco presence

## Results
The analysis reveals patterns in the relationship between educational support services and standardized test performance, with color-coded maps showing both the distribution of volunteers/beneficiaries and the changes in educational outcomes over time.

## Future Work
- Expand the analysis to include more years of data
- Incorporate additional variables like socioeconomic factors
- Develop predictive models to anticipate educational needs
- Extend the geographic scope beyond Lombardy

## Acknowledgements
This project uses data from INVALSI, ISTAT, Portofranco, and Solidarity Desks organizations.
