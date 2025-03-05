# Florida Health Provider Analysis Behavioral / Mental!

## Case study of private company Balanced Wellbeing, LLC Florida for the year 2024

### Table of Contents

* [Motivation](#motivation)
* [Limitations and challenges](#limitations-and-challenges)
* [Technologies Used](#technologies-used)
* [Future scope of the project](#future-scope-of-the-project)
* [Conclusion](#conclusion)
* [Sources](#sources)

# Motivation
While looking into the mental health data of Florida, it was revealed that the state ranked first in the number of adults experiencing mental illness but 43rd in mental health workforce availability. After researching more, the interesting fact caught my attention which is, Florida’s community mental health system is fully privatized—it contracts with private programs to offer state-funded mental health services. This project aims to explore how a private mental health care provider is positively impacting patient outcomes and improving access to providers and quality resources.

# Limitations and challenges
The study's descriptive health trajectories are based on data sourced from the private healthcare provider company, Balanced Wellbeing, LLC Florida. The data primarily includes information from nursing homes and assisted living facilities and focuses on elderly patients only, served by the company. The data was provided in 12 seperate excels files for the year 2024. The providers mentioned in the data are employed by company in each month. 
> - All the quantative/numeric data posed challenges in drawing conclusions and creating trajectories.
> - It was challenging to mask the actual provider names. The names of providers are masked in Python.
> - An original dataset does not contain timestamp. The date was only mentioned in the name of excel file. I fetched the datestamp from excel file name and created a new column to store it for each excel file.
> - The dataset for overall review (first screen) derived from Gov. website, dosen't have datestamp either. An original dataset contained labels of excel file columns as fiscal years like FY-16_17. I had to covert them into column and assigned appropriate datestamp to it.

# Technologies Used
> - Python / Pandas : for exploration, normalizing and aggregation of the dataset
> - Power BI : for creating interactive dashboard
> - PowerPoint : for introduction of Project
> - Git : for version control

# Future scope of the project
> - Analyze data for 3 years at least, to produce better overall projections/results of analysis.
> - Improve visuals on the dashboard.
> - Adding slicers of date stamp.
> - Creating  different Tabs for Psychiatrist ,Psychologist and Both in dashboard. Group respective analysis and place it in appropriate Tab.
> - Examine the providers and facilities where the company offers mental health services, to understand how a private mental health care provider is enhancing patient outcomes and improving access to quality resources and providers.

# Conclusion
> - The growth in rate of medical providers per 100,000 population has been increased by 4.93% in 6 years. The gradual increasing trend led to projection of around 4.48% increase in next 5 year.
> - Winter Blue – Highest mental health issues are recorded in the month of October-November based on medication and assessment data. Whereas lowest issues are recorded in the month of May.
> - For elderly individuals, the number of pain assessments is observed to be nearly equal to the number of trauma assessments.
> - In 2024, the company's 180 mental health providers conducted a total of 293,000 trauma and pain assessments.

# Sources
> - Information about Florida Behavioral/Mental Health Professionals related county wise counts can be found here: https://www.flhealthcharts.gov/ChartsDashboards/rdPage.aspx?rdReport=NonVitalIndNoGrp.Dataviewer&cid=9892
> - The study's descriptive health trajectories are based on data sourced from the private healthcare provider company, Balanced Wellbeing, LLC Florida. 
> - Forida Mental Health Statistics :   https://olympicbehavioralhealth.com/rehab-blog/florida-mental-health-statistics/



