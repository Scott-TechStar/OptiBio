**Project Name: OptiBio**

**Description:** OptiBio is a cutting-edge AI-powered solution for optimizing the waste-to-energy supply chain, specifically focusing on the state of Gujarat in western India. Leveraging historical biomass data and advanced remote sensing techniques, OptiBio accurately forecasts the spatial distribution of biomass availability in the region, providing valuable insights for biorefineries and stakeholders.

**Objective:** The primary objective of OptiBio is to identify optimal locations for different assets across the waste-to-energy supply chain, including harvesting sites, preprocessing depots, and biorefineries. By efficiently collecting and transporting biomass feedstock to biorefineries, OptiBio aims to create a robust and sustainable supply chain while meeting practical objectives and constraints.

**Key Tasks:**

1. **Biomass Forecasting:** Utilize the Biomass_History.csv dataset containing a time-series of biomass availability from 2010 to 2017 to accurately forecast the spatial distribution of biomass for the year 2018 and 2019.

2. **Optimal Asset Locations:** Based on the forecasted biomass data and Distance_Matrix.csv, identify optimal locations for preprocessing depots and biorefineries. These locations should be strategically chosen to minimize travel distances and maximize biomass supply to each biorefinery.

**Dataset Description:**

The provided dataset includes the following files:

1. **Biomass_History.csv:** A time-series of biomass availability in the state of Gujarat, representing 2418 equisized grid blocks (harvesting sites). The data includes location index, latitude, longitude, and year-wise biomass availability for each site.

2. **Distance_Matrix.csv:** A 2418 x 2418 matrix providing the travel distance from one grid block to another, accounting for non-symmetrical distances due to road conditions.

3. **sample_submission.csv:** Contains a sample format for submission, indicating the columns to be filled with optimal asset locations.
