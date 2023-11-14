# Data-Analysis-Access-to-drinking-water
Investigate access to safe and affordable drinking water.  By understanding the data overview, having a look at the different features and definitions of this dataset.

* The Sustainable Development Goals (SDGs) are an ongoing global call to action to end poverty, ensure prosperity and peace for all people, and protect our planet.

* Due to changes in our climate, droughts are becoming more prevalent and water supplies are decreasing worldwide. This not only affects access to drinking water but also sanitation and hygiene which often results in unnecessary diseases and death.
* In order to ensure greater access to water and sanitation, communities across the world need to assist each other in developing and managing water resources.

* In this project, we’ll investigate access to safe and affordable drinking water focussing on inequalities in service levels between different countries and regions.

## Understanding the data
We’ll take a look at the WHO/UNICEF JMP (Joint Monitoring Programme for Water Supply,
Sanitation, and Hygiene) Estimates on the use of water dataset for 2020.

* Columns: We have a total of 16 features (or columns) in our dataset, 12 of which are service-level percentage shares.
name: The country or area name.  
income_group: The country’s classification according to income group.  
pop_n: The national population size estimate in thousands.  
pop_u: The urban population share estimate in percentage points (%).  
wat_bas_n: The estimated national share of people with at least basic service (%).  
_wat_lim_n_: The estimated national share of people with limited service (%).  
_wat_unimp_n_: The estimated national share of people with unimproved service (%).  
_wat_sur_n_: The estimated national share of people with surface service (%).  
wat_bas_r: The estimated rural share of people with at least basic service (%).  
_wat_lim_r_: The estimated rural share of people with limited service (%).  
_wat_unimp_r_: The estimated rural share of people with unimproved service (%).  
_wat_sur_r_: The estimated rural share of people with surface service (%).  
_wat_bas_u_: The estimated urban share of people with at least basic service (%).  
_wat_lim_u_: The estimated urban share of people with limited service (%).  
_wat_unimp_u_: The estimated urban share of people with unimproved service (%).  
_wat_sur_u_: The estimated urban share of people with surface service (%).  



## Steps:
1. Import data to the spreadsheet.
2. Clean the data: NaN values.
3. Investigating population size: In 2020, the world population was estimated to be 7.821 billion, 55% of which lived in urban areas.
   ![10](https://github.com/nervana12/Data-Analysis-Access-to-drinking-water/assets/87612394/96d2964e-38e5-4391-a42e-0bf2a9b32ae2)

4. Deal with outliers.
5. Investigating access by area: investigate what access to water at the different service levels looks like for people in specific types of areas (national, urban, and rural).
6. Investigating access by population size: Visualise the national access to water on all four levels based on the national population size.
7. Investigating access by income group: We want to investigate the relationship between GNI (gross national income) or income group, population size, urbanisation, and national water access.
