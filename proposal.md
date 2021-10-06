## Proposal
Matt Ryan

# Problem 
The coffee industry historically has a fair-trade problem, with many coffee bean suppliers/growers not being compensated fairly for their produce and coffee buyers holding much of the buying power. Acquiring a fair-trade certification throught the Fair Trade Labeling Organization International (FLO) can lead to better economic outcomes for coffee farmers; however, these certifications can be cost and time intensive--or even prohibitive--to acquire and can leave the majority of growers out in the cold, leading to a rich-get-richer scenario for growers. 

**Impact Hypothesis**
We can use data ![available to us](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GRIAV8) to identify and create a network of coffee growers in Ethiopia that exist outside of the FLO certification program, but are on the cusp of being certified. From there, we can create a funnel of coffee growers/producers we can work with to ensure they are on track to FLO certification, while also allowing them to be paid fair prices for their beans today, freeing up resources for them to dedicate towards working towards fair-trade certification.

**Solution Paths**
- This is likely a classification problem: ie classify growers into groups of FLO certified, on-track to be certified, and not certified. 
- From there develop and implement funnel steps to get growers on track to working towards FLO certification. 


**Measures of Success**
Be able to create a network of *x*-size growers within our funnel to work towards certification, and be able to demonstrate *y%* growth in income after *z* years in program. (might still need some crystallization in timeline and metrics)

**Major Risks/Assumptions**
A core assumption here is that all growers identified or sorted into the funnel would be willing or able to work towards FLO certification. Some potential risks include unreliability of data/model in identifying on-track growers, complexity of data leading to necessity for intense EDA, and potential ability of growers to game the system and achieve fair-trade prices without working towards certification, thus hurting the social justice efforts of the FLO and negatively impacting growers already associated with the FLO.