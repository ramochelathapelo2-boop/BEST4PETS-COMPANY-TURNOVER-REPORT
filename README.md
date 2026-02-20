 # BETTERFORPETS COMPANY TURNOVER REPORT
BetterForPets is a  company that offers pet maintenance services and sells pet products ranging from food to toys. The HR Head is particularly concerned about the company’s turnover rate, noticing a significant number of employees leave within the first year especially in the Customer Support department. The HR Head is only interested in insights from employees who joined the company from 2023 until 2025.
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
* **Statistical Analysis:** Basic hypothesis testing for training impact
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

## EXECUTIVE SUMMARY:
**Turnover rate:**

The Customer Support department records the highest employee turnover at 41%, significantly exceeding the turnover rates of other departments, which range between 24% and 32%. 

In contrast, the **Finance and IT departments** exhibit the lowest turnover rate at 24%, suggesting stronger employee retention. A deeper investigation into these departments is recommended to identify practices or conditions that contribute to their lower exit rates and assess whether they can be replicated elsewhere.

**Tenure analysis:**

Most employee exits occur between **6 and 12 months of employment**. This suggests that employees may encounter critical challenges during this period that influence their decision to leave. Notably, **employees in the Customer Support department tend to exit earlier** on average than employees in other departments, reinforcing the need for targeted retention strategies within this department.

**Training:**

**Training completion** shows a **statistically significant** relationship with retention outcomes (p < 0.05). **Employees who completed training demonstrate an 18% lower turnover rate** compared to those who did not. This indicates the importance of structured training programs; therefore it is recommended that training completion be made mandatory for all employees.

**Engagement and Salary satisfaction:**

There is minimal difference in salary satisfaction scores between employees who left and those who stayed. This indicates that compensation alone is unlikely to resolve the turnover issue. Instead, **employee engagement and managerial support emerge as the primary drivers of turnover**, suggesting that efforts should focus on improving leadership effectiveness and employee involvement to enhance retention

<img width="940" height="516" alt="image" src="https://github.com/user-attachments/assets/fdc3c45c-ba5a-46b8-a8d2-b9957616438d" />
Dashboard highlighting KPIs and visuals discussed in the Executive Summary

## TURNOVER RATE:
**The Customer Support department leads with the highest turnover rate of 41%.**

<img width="229" height="384" alt="image" src="https://github.com/user-attachments/assets/515bba05-2839-41ce-89e7-96d93964953e" />
</br>
<img width="608" height="187" alt="image" src="https://github.com/user-attachments/assets/7a5d1e83-4fcd-48b4-a177-d580f41745f8" />

## TENURE ANALYSIS:
**38 % of leavers left the company between 6 and 12 months after their employment.**

<img width="413" height="242" alt="image" src="https://github.com/user-attachments/assets/41ce5f8b-0c7a-4b9f-96cd-b9515577fc89" />


* 38% of leavers exited between 6 and 12 months, making this the highest-risk period for employee turnover.
* 28% left between 3 and 6 months, indicating a significant number of employees disengage shortly after joining.
*	21% left within the first 0–3 months, suggesting onboarding or role expectation issues for some new hires.
*	Only 13% left after 12 months, showing that employees who stay beyond one year are far more likely to remain.
  
**Insights:**

*	Turnover is concentrated in the first year of employment, especially after initial onboarding but before long-term commitment is established.
*	The 6–12-month window often coincides with:
     *	Increased workload expectations
     *	Performance evaluations
     *	Reduced onboarding support
     *	Reassessment of career growth opportunities

The first year, particularly months 6 to 12 is a critical retention period. Interventions during this stage could significantly reduce overall turnover.

**Recommendations:**
*	Introduce mid-year check-ins (around months 4–6 after employment)
*	Strengthen career development conversations
*	Provide manager support and coaching during the first year
*	Extend onboarding support beyond the first 3 months

**On average, employees from the Customer Support department leave the company earliest.** 

<img width="345" height="146" alt="image" src="https://github.com/user-attachments/assets/74bbf141-04fc-46e8-b019-a6a1626e6592" />


This chart compares average employee tenure (in days) between the Customer Support (CS) department and all other departments combined

**Key Findings**
*	Employees in Customer Support leave significantly earlier than employees in other departments.
*	The average tenure in Customer Support is 158 days, which is 52 days shorter than the company-wide average of 210 days.
*	Other departments retain employees for considerably longer, indicating that early exits are not a company-wide issue, but are concentrated within Customer Support.
  
The early exits in Customer Support suggest department-specific challenges, rather than general organisational problems.

**Possible contributing factors may include:**
*	High workload or emotional labour
*	Insufficient training or onboarding
*	Management or team culture issues
*	Misalignment between role expectations and reality

**Recommendations:**

Conduct a deep-dive analysis or investigation into Customer Support:
*	Compare engagement scores against other departments
*	Assess training completion rates
*	Analyse turnover by manager within the department

## TRAINING COMPLETION AND TURNOVER ANALYSIS:
This table compares turnover rates between employees who completed training and those who did not complete training

<img width="583" height="160" alt="image" src="https://github.com/user-attachments/assets/caaa65d0-4661-4bdb-ad1c-91938f327caa" />

**Key Findings:**
 Employees who completed training had a significantly lower turnover rate:
*	27% leavers
*	73% stayers
  
Employees who did not complete training were 18 percentage points more likely to leave the company than those who completed training.

**Statistical Analysis: Training and employee retention**

A chi-square test of independence was conducted to assess whether the observed difference in turnover rates between trained and untrained employees was statistically significant.

Hypothesis statements:

**Null hypothesis (H₀):** Training completion and employee retention are independent.

**Alternative hypothesis (H₁):** Training completion and employee retention are associated.

**Test Results:**
*	χ² = 4.31, df = 1, p = 0.038
*	**Conclusion:** The association between training completion and retention is statistically significant at the α = 0.05 level. **H₀** rejected since p <0.05

**Interpretation:** There is less than a 4% probability that the observed difference occurred by chance alone. This provides reasonable evidence that training completion is meaningfully associated with employee retention.

However, due to the relatively small sample size (n = 120), the results should be interpreted with caution, as statistical reliability may be reduced and the findings may not fully generalise to the broader population.

**Takeaway:**
Training completion is **strongly associated** with employee retention.

Employees who complete training are likely to:
  *	Feel more confident in their roles
  *	Perform better due to improved skills
  *	Feel supported by the organisation
  
In contrast, employees who do not complete training may:
*	Struggle with role expectations
*	Experience lower confidence and engagement
*	Be more vulnerable to early exit
  
**Insight:**

Training completion appears to be a key protective factor against turnover, with trained employees nearly twice as likely to remain with the company.

**Recommendations:**
*	Ensure mandatory training completion, especially within the first 3 months.
*	Track training completion rates by department and manager.
*	Provide additional support or refresher training for employees who fall behind.

## ENGAGEMENT SCORE AND SALARY SATISFACTION:

**Analysis of results from the questionnaire reveal that leavers had the lowest engagement scores and the most unsatisfied with their salaries.**

<img width="500" height="131" alt="image" src="https://github.com/user-attachments/assets/15eb7f2f-d589-4449-be84-47bc47c8cdd7" />

*	Leavers reported low levels of support from management and colleagues, with an average engagement score of 2.7 out of 5, indicating that engagement and workplace support play a critical role in employee retention.
*	Salary satisfaction scores showed minimal difference between leavers and stayers. However, stayers reported slightly higher satisfaction, with an average score of 3.4 out of 5, suggesting that compensation alone is not the primary driver of turnover

**Recommendations**
*	The HR department should prioritise initiatives to improve employee engagement, particularly by strengthening managerial support, team collaboration, and regular feedback mechanisms, in order to reduce high turnover rates.
  
## RECOMMENDATIONS SUMMARY:
**Strengthen Early-Tenure Retention (First 12 Months)**
*	Introduce structured *check-ins at 3, 6, and 9 months*, with particular focus on the 6–12-month high-risk period.
*	Extend onboarding support beyond the initial induction phase.

**Improve Training Completion**
*	Make training mandatory and time-bound, especially within the first 3 months.
* Track training completion by department and manager.

**Address Customer Support-Specific Challenges**
*	Conduct a targeted review of the Customer Support department, including:
    *	Managerial practices
    *	Training adequacy
*	Introduce department-specific retention initiatives, such as mentoring or workload balancing.

**Strengthen Manager Capability**
*	Review turnover trends by manager to identify potential leadership gaps.
*	Provide manager coaching focused on supporting new hires and early-tenure employees.


