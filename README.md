# Patient Wait List Analysis
# Project overview
Project utilizes Power BI to analyze inpatient and outpatient data related to patient waitlists, examining trends, distribution across case types and age profiles, and identifying specialties with long wait times. The insights gained aim to aid healthcare administrators and practitioners in optimizing waitlist management, improving efficiency, and ensuring timely patient care. Through thorough data transformation, modeling, and analysis, actionable findings and recommendations are provided to enhance the patient waitlist management process.
![pwlt snip](https://github.com/gayatrikuracha/Patient-Wait-List-Data/assets/167384815/4b8f2015-5fbf-49ea-af9f-1d6386e4e705)




# Data source
The analysis is based on a Patient Wait List dataset encompassing both inpatient and outpatient data. Both datasets feature information archived by date and list various medical specialties. Patients are classified as either Day Case or Inpatient, with age groups spanning from Child to Adult, further delineated by age profile. Time bands may represent duration of stay.

# Tools 
Utilized Power BI for both data visualization and transformation processes.

# Data Transformation and Modeling
Columns such as "specialty name" were renamed to ensure consistency across datasets. Custom columns like "case type" were added to the outpatient data as required. Inpatient and outpatient tables were appended to consolidate pertinent data effectively. This process enhances the coherence and accessibility of information within the dashboard.

# Data analysis
- Compare the overall waitlist for the current month to the same month from the prior year.
- Split case types by average and median waitlist times
- Compare average and median queue times by case type (Day Case vs. Inpatient).
- Compare Case Type and Age Profile with Waitlist: Analyze waitlist distribution across various case kinds and age profiles.
- Find the top 5 specializations with the longest wait times and visualize them.
- Analyze monthly waitlist patterns for Day Case, Inpatient, and Outpatient cases to understand patient flow dynamics.
- Detailed view provides a deeper look into wait times for inpatients at this healthcare system,

# Findings
- The waiting list decreased from January 2018 to March 2021. 
- By case type, outpatient appointments are the most common, followed by day cases and inpatient hospitalizations. 
- Age Profile: The waitlist has a majority of patients aged 16–64, with no data available for those beyond 64. 
- Pediatric dermatology, ENT, and orthopaedics have the most waiting patients. It's crucial to note that the data only includes pediatric specialty waitlists.

# Recommendations
- Investigate the cause of the overall waitlist decrease. Are there new waitlist management strategies?
- Analyze waitlist trends for specific specialties, particularly those with high volumes (e.g., Paediatric Dermatology). Can these departments improve efficiency?
- Include data for geriatric patients (over 64) to provide a more comprehensive picture.

# Limitations
- Temporal Coverage: The dataset spans from January 2018 to March 2021, which may restrict the ability to capture long-term trends or seasonal variations beyond this timeframe. 
- While the dataset includes information for patients aged 64 and below, data for geriatric patients (over 64 years old) is not available.

# References
- Patient Wait List Data : [Link](https://github.com/gayatrikuracha/Patient-Wait-List-Data/tree/main/Data)
- Power Bi Dashboard : [Link](https://github.com/gayatrikuracha/Patient-Wait-List-Data/blob/main/Patient%20Wait%20list%20dashboard.pbix)


