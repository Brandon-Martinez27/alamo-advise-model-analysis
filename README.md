# Alamo Advise Model Analysis
## Background
You have been asked to give an update on the percentage of students with formal academic plan status. The institution is required to maintain 95% threshold that affects student persistence, engagement and completion. In particular, senior leadership would like to know the following:
>1. Has the advising team as a unit met the 95% goal? 
>2. In instances where goal attainment is below expected target, what are the reasons?
>3. College Leadership has a hypothesis that hours earned is impacting the 95% goal. Identify any possible patterns that may support hypothesis.

**Data Descriptors**:
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

All work is done in [Tableau](https://public.tableau.com/views/AlamoAdviseModelAnalysis/ExecutiveSummary?:language=en&:display_count=y&publish=yes&:toolbar=n&:origin=viz_share_link)
