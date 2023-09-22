# Labor-Policy-Database

## Introduction
The aim of the labor policy database is to systematically organize and report on the existence of policies impacting labor conditions and requirements across US states and counties from 2013 to 2022. The policy areas tracked in this database include labor regulations (e.g., minimum wage and secure scheduling ordinances), public health and Covid-19 mandates (e.g., mask mandates), and civil rights related legislation (e.g., policies surrounding gender identity and undocumented status). 

## Policy Coding
In our state-level tracker, we create monthly measures for all 50 states and D.C. indicating whether a state has enacted or, for certain policy areas, prohibited/preempted such policies. Our local-level tracker does the same for all counties in the U.S. (as represented by county FIPS codes), and it also includes city-level measures indicating if any city within that county has such policies and, if so, how many. Both databases report on these policies for each month between 2013 and 2022.

For each policy, we recorded our data source (state or county legal code, third party policy trackers, etc.) and the enactment date. We did this separately for states vs. counties/cities. Some policy areas encompassed more than one law or required more coding decisions than simple binary indicators. 

## State vs Local Database
Our state- and local-level trackers are uniquely identified by state and county FIPS (Federal Information Processing System) codes, respectively, as well as month-year. Researchers can, thus, merge this policy information to their data using the relevant FIPS code, but should pay careful attention to how they deal with time. Finally, although the local-level tracker has information about city-level policies, it is within the context of counties (e.g., the number of cities within a county that has a certain policy). This information cannot be directly merged to city-level data.

### Suggested Citation
Harknett KH, Schneider DS, Wolfe R, Williams C. (2023). "Shift Project State and Local Policy Database." Available at: github.com/Shift-HKS/Labor-Policy-Database

### Funding Acknowledgement
The compilation of this database was supported by the National Institute for Occupational Safety and Health (Grant No. U19OH012293).



