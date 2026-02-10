 # BEST4PETS COMPANY TURNOVER REPORT
Best4Pets is a sample company that offers pet maintenance services and sells pet products ranging from food to toys. The HR Head is particularly concerned about the company’s turnover rate, noticing a significant number of employees leave within the first year especially in the Customer Support department. The HR Head is only interested in insights from employees who joined the company from 2023 until 2025.
The HR Head provided access to the company HR records which contain key information (tenure days, working hours, training stats etc.) about current and previous employees and data from a questionnaire sent to previous employees after their resignations (the same questionnaire was also sent to current employees to gather additional data for comparison purposes). The questionnaire mostly requested participants to anonymously rate (on a scale of 1 to 5) the company’s performance on specific areas based on their experience or thoughts, this included salary satisfaction and engagement/support from assigned managers.
Using the provided data the project aims to understand why employees especially in Customer Support are leaving the company, the risk factors involved and recommendations to reduce turnover.
 ### KEY QUESTIONS: 
*	What is the overall turnover rate?
* Which department has the highest turnover?
*	When are employees most likely to leave (0–6 months, 6–12 months, etc.)?
*	Is training completion linked to turnover?
*	What can be done to reduce turnover (recommendations)
### METHODOLOGY AND DATA PREPARATION:
**TOOLS USED:**
*	**Power BI:** Dashboard creation, DAX measures, data visualisation
*	**Excel:** Initial data cleaning and validation
*	**Statistical Analysis:** Basic hypothesis testing for training impact
### DATA SOURCES:
1.	**HR Records:** Employee demographics, tenure, training completion, performance metrics
2.	**Exit Questionnaire:** 5-point Likert scale ratings on: 
-	Salary satisfaction
-	Manager engagement/support
-	Work environment
-	Distributed to both current and former employees
### DATA CLEANING STEPS:
1.	**Duplicate Check:** Verified no duplicate employee IDs (n=120 unique records)
2.	**Missing Values:** 
*	8 employees had incomplete questionnaire responses (6.7%)
*	Handled by excluding from engagement analysis only
*	Retained for tenure and training analysis
3.	**Date Validation:**
*	Confirmed all start dates within 2023-2025 range
*	Calculated tenure in days: Tenure = *End Date - Start Date* (for leavers)
*	For current employees: Tenure = *TODAY() - Start Date*
4.	**Categorisation:** 
* Created tenure buckets: 0-3 months, 3-6 months, 6-12 months, 12+ months
*	Binary training completion: Yes/No
5.	**Data Quality Checks:** 
* Verified no negative tenure values
*	Confirmed questionnaire scores within 1-5 range
*	Cross-checked department assignments
  
**SAMPLE SIZE BREAKDOWN:**

<img width="607" height="184" alt="image" src="https://github.com/user-attachments/assets/fa0b74ef-ea2f-45b0-99df-253e0a0ed315" />

**Overall Turnover Rate:** 31.7% (38/120)

**Limitations & Caveats:**
*	**Small sample size** (n=120) limits statistical power for some analyses
*	**Survey response bias:** Former employees may rate experiences more negatively
*	**Time period:** 2-year window may not capture seasonal hiring patterns
*	**Self-reported data:** Engagement scores are subjective
*	**Survivorship bias:** Current employees still in early tenure may eventually leave
*	**Missing qualitative data:** No exit interview notes for deeper context





