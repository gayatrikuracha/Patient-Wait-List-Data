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
- Compare average and median wait times by case type (Day Case vs. Inpatient).
- Compare Case Type and Age Profile with Waitlist: Analyze waitlist distribution across various case kinds and age profiles.
- Find the top 5 specializations with the longest wait times and visualize them.
- Analyze monthly waitlist patterns for Day Case, Inpatient, and Outpatient cases to understand patient flow dynamics.
- Detailed view provides a deeper look into wait times for inpatients at this healthcare system.

# Findings
- There has been a noticeable increase in the waitlist count compared to the previous year, indicating a growing demand or backlog in patient handling.
- Outpatient cases constitute nearly three-quarters of the total, followed by day cases and inpatients.
- The waitlist is highest for the 18+ months time band, particularly for the age group 16-64, which consistently has a higher presence across all time bands.
- Day cases and inpatient numbers are relatively stable or slightly declining, outpatient numbers have been steadily increasing, suggesting a shift towards more outpatient treatments.

# Recommendations
- To address the increasing waitlist, allocate more resources to manage the growing demand, particularly for outpatient services.
- Enhance capacity for handling long-waiting patients, especially in the 16-64 age group and for the 18+ months time band.
- Focus on optimizing outpatient care processes to accommodate the rising numbers.
- Additionally, consider strategic planning to balance the load across different case types and specialties to prevent backlogs.

# Limitations
- The dataset spans from January 31, 2018, to March 31, 2021, limiting insights to this period and potentially missing longer-term patterns or recent changes.
- The broad age group categories may obscure more nuanced trends that narrower age ranges could reveal.
- Additionally, the dataset does not account for external factors like healthcare policy changes, population shifts, or events such as pandemics, which could significantly impact waitlist trends and demand.

# References
- Patient Wait List Data : [Link](https://github.com/gayatrikuracha/Patient-Wait-List-Data/tree/main/Data)
- Power Bi Dashboard : [Link](https://github.com/gayatrikuracha/Patient-Wait-List-Data/blob/main/Patient%20Wait%20list%20dashboard.pbix)


