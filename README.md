# Alamo Advise Model Analysis
## About the Project
### Background
You have been asked to give an update on the percentage of students with formal academic plan status. The institution is required to maintain 95% threshold that affects student persistence, engagement and completion. In particular, senior leadership would like to know the following:

### Goals
>1. Has the advising team as a unit met the 95% goal? 
>2. In instances where goal attainment is below expected target, what are the reasons?
>3. College Leadership has a hypothesis that hours earned is impacting the 95% goal. Identify any possible patterns that may support hypothesis.

### Deliverables
- [Slide deck](https://www.canva.com/design/DAEZnf2cBOQ/tBRA2jsJ4i8RppGkDKcXXA/view?utm_content=DAEZnf2cBOQ&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu) with presentation of analysis
- [Tableau](https://public.tableau.com/profile/brandon.martinez6956#!/vizhome/AlamoAdviseModelAnalysis/ActivePlanPercentagebyAdvisor?publish=yes) workbook with various dashboards and visualizations

### Acknowledgments
- [Northeast Lakeview College Recruiting](https://www.alamo.edu/nlc)
- [Faith Kane](https://public.tableau.com/profile/faith.kane#!/vizhome/DrillingDownIntoChurn/Dashboard1)

## Data Dictionary
All students are enrolled at NLC. Banner is the student information system.
- Banner Id = student unique id
- Banner Advisor Name = assigned student advisor
- Banner Hour Range = student earned hours (e.g. student has earned in range of 31-45 hours)
- DW (Degree Works) Plan Description = student’s description for their plan
- DW (Degree Works) Plan Status = status of formal academic plan
- Banner Degree = degree program
  - AA = Associate of Arts
  - AAS = Associate of Applied Science 
  - AS = Associate of Science
  - AAT = Associate of Arts in Teaching
- Banner Program = field code student is enrolled in
- Banner Earned Hours = number of hours student has earned
- Banner StuType = student type as follows

| Code | Description           |
|------|-----------------------|
| 0    | Undeclared            |
| 1    | Continuing Education  |
| A    | Ability to Benefit    |
| C    | Continuing            |
| E    | Early Admit           |
| F    | Transfer, Former      |
| H    | Early College HS      |
| M    | Transfer Military     |
| N    | New First Time        |
| R    | Returning, Former     |
| T    | Transfer              |
| U    | Concurrent HS Student |
| V    | Virtual College       |
| X    | Transient             |
| Z    | Senior Citizen        |

## Project Steps
### Acquire & Prepare
Data was given in the form of an excel spreadsheet `sample_data.xlsx`

### Explore
![Executive Summary](https://github.com/Brandon-Martinez27/alamo-advise-model-analysis/blob/main/exec-summ.png?raw=true)

![Advising Unit Performance](https://github.com/Brandon-Martinez27/alamo-advise-model-analysis/blob/main/advising-performance.png?raw=true)

![Below Threshold Group](https://github.com/Brandon-Martinez27/alamo-advise-model-analysis/blob/main/below-threshold-group.png?raw=true)

![Hours Earned](https://github.com/Brandon-Martinez27/alamo-advise-model-analysis/blob/main/hours-earned.png?raw=true)

### Conclusions
- Advising unit performance is about 8% shy of goal. 
- Plan description is the largest source of Non-active plans.
- The hypothesis that credit hours have an influence on threshold is supported by data indicating that new students have more Non-active than active plans.

*Recommendations*
1. Meet with the group of advisors below threshold.
2. Schedule meetings with students at regular intervals to update plans with detailed descriptions.
3. Make plan update a mandatory part of onboarding process.

## Tools & Requirements
Tableau 2020.4.1
