# It's Just Coffee
Matt Ryan

## Abstract
The coffee industry historically has a fair-trade problem, with many coffee bean suppliers/growers not being compensated fairly for their produce and coffee buyers holding much of the buying power. Acquiring a fair-trade certification through the Fair Trade Labeling Organization International (FLO) can lead to better economic outcomes for coffee farmers; however, these certifications can be cost and time intensive--or even prohibitive--to acquire and can leave the majority of growers out in the cold, leading to a rich-get-richer scenario for growers. With that in mind, we can use data [available to us](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GRIAV8) to identify and create a network of coffee growers in Ethiopia that exist outside of the FLO certification program, but are on the cusp of being certified, to then work with in achieving FLO certification while being paid FLO prices.

## Design

This project is premised on the hypothetical that a growing cafe and roastery chain with an emphasis on ethical and sustainable consumption employed our consulting team's data science services to aid them in their mission. With the Fair Trade Organization's efforts not being as developed in Africa, many of the growers in Ethiopia are left un-certified. 

## Data

The IFPRI dataset used here, hosted on Dataverse, is composed of 27 different CSV files and encompass the results of an extensive survey issued to 1,598 different households of Ethiopian coffee growers and producers. Ultimately, we narrowed our features down to a handful for an initial evaluation, with features of note including level of fair trade certification, level of other certifications, whether or not minors were employed, and number of years the farm has been in operation, size of plots, etc.

## Algorithms


*EDA*

The data used originally came in the form of 27 separate csv files, with each file representing a respective section of the survey issued. In addition, a PDF document was provided translating column codes and answer numbers into full questions and answers. With that in mind, during the data exploration we sifted through the csv's and attempted to identify key questions pertaining to FLO certification per the offical FLO coffee standards and added each csv featuring these questions was added into a new worksheet in single Excel file. From there, we used the front-page survey worksheet to use vlookup's to reference specific questions by the household ID, ultimately resulting in a single worksheet featuring a quick look at many of the desired key features. Finally, we manually transformed columnn names and some answers per the provided PDF file.



*Visualization*

We used Tableau to visualize the data that we cleaned with Excel. Ultimately we developed two dashboards, one giving more of an overview of the survey results and one focusing on a single grower identified as a model grower. These dashboards can be found [here](https://public.tableau.com/app/profile/matt.ryan3507/viz/coffee_dash/Overview) and [here](https://public.tableau.com/app/profile/matt.ryan3507/viz/coffee_dash/ModelGrower)



## Tools
- Microsoft Excel for EDA and data-storage
- Tableau for visualization

## Communication

Ultimately, we believe employing a logistic regression model on our data after a little further EDA to identify more key features to create a model predicting the probability of a grower to become FLO certified. Further, we recommend working with the business team leaders to identify the appropriate measures of success and to develop and implement the program to work with growers while providing them FLO prices.
