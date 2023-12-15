# Understanding Home Owners' Loan Corporation grade inequality in LA

Present-day environmental justice may reflect legacies of injustice in the past. The United States has a long history of racial segregation which is still visible. During the 1930's the Home Owners' Loan Corporation (HOLC), as part of the New Deal, rated neighborhoods based on their perceived safety for real estate investment. Their ranking system, (A (green), B (blue), C (yellow), D (red)) was then used to block access to loans for home ownership. Colloquially known as "redlining", this practice has had widely-documented consequences not only for community wealth, but also health. Redlined neighborhoods have less greenery and are hotter than other neighborhoods.

A recent study found that redlining has not only affected the environments communities are exposed to, it has also shaped our observations of biodiversity. Community or citizen science, whereby individuals share observations of species, is generating an enormous volume of data. Ellis-Soto and co-authors found that redlined neighborhoods remain the most undersampled areas across 195 US cities. This gap is highly concerning, because conservation decisions are made based on these data.

## Goal
To investigate the legacy of redlining in current environmental (in)justice and investigate the legacy of redlining in biodiversity observations.


## Highlights
- Create maps using the tmap package
- Run an analysis to finding percentages and amounts relating to redlining communities
- Create a bar graph to visualize results

## Data
### EJScreen

We will be working with data from the United States Environmental Protection Agency's EJScreen: Environmental Justice Screening and Mapping Tool.

According to the US EPA website:

This screening tool and data may be of interest to community residents or other stakeholders as they search for environmental or demographic information. It can also support a wide range of research and policy goals. The public has used EJScreen in many different locations and in many different ways.

EPA is sharing EJScreen with the public:- to be more transparent about how we consider environmental justice in our work,- to assist our stakeholders in making informed decisions about pursuing environmental justice and,- to create a common starting point between the agency and the public when looking at issues related to environmental justice.

EJScreen provides on environmental and demographic information for the US at the Census tract and block group levels. You will be working with block group data that has been downloaded from the EPA site. To understand the associated data columns, you will need to explore the Technical Documentation and column description spreadsheet available in the data folder. I also encourage you to explore the limitations and caveats of the data.

### Mapping Inequality

A team of researchers, led by the Digital Scholarship Lab at the University of Richmond have digitized maps and information from the HOLC as part of the Mapping Inequality project.

We will be working with maps of HOLC grade designations for Los Angeles. Information on the data can be found here.

### Biodiversity observations

The Global Biodiversity Information Facility is the largest aggregator of biodiversity observations in the world. Observations typically include a location and date that a species was observed.

We will be working observations of birds from 2021 onward.


**Note:** the data associated with this assignment is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1lcazRbNSmP8Vj9sH1AIJcO4D1d_ulJij/view?usp=share_link). Unzip the folder and all the contents and store in your directory as follows.

## Repo Structure
```         
HOLC_Grade_Inequality
│   README.md
│   HOLC_Grade_Inequality.html
│   HOLC_Grade_Inequality.Rmd
│   HOLC_Grade_Inequality.Rproj
│   .gitignore
│   data
    └─── │  column descriptions: EJSCREEN_2023_BG_Columns.xlsx
         │  metadata explation: ejscreen-tech-doc-version-2-2.pdf
         │  spatial data: EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
         │  biodiversity data: gbif-birds-LA/gbif-birds-LA.shp
```
