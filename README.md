
### Executive Summary

This project was targetted at creating actionable data from statistics gathered from the SAT & ACT during the years 2017-2018. The population in the datasets are a percentage based population of students from each state that have taken the exams.  
Within the dataset, variables were targetted and explored for potential relationships. Notably between participation rates between both tests, as well as the effect of participation rates on scores. 

Through external research for supplementary purposes, key findings were that legislature drove most of the changes within the data, and that further effective steps in order to increase SAT foothold on the market. 

### Problem Statement
While there have been many adopters of the SATs, the ACT still maintains a large chunk of the target market. How can we take effective actionable steps toward having a higher SAT participation rate. 

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
'state'|object|2017/18  ACT/SAT|US State from which data was collected|
'act_2017participation'|float64|2017 ACT|Percentage of graduating hs seniors taking the ACT in 2017, Scored 1-100
'act_2017english'|float64|2017 ACT|Avg test scores by state in English for ACT in 2017, Scored 1-36
'act_2017math'|float64|2017 ACT|Avg test scores by state in Math for ACT in 2017, Scored 1-36
'act_2017reading'|float64|2017 ACT|Avg test scores by state in Reading for ACT in 2017, Scored 1-36
'act_2017science'|float64|2017 ACT|Avg test scores by state in Science for ACT in 2017, Scored 1-36
'act_2017composite'|float64|2017 ACT|Avg Composite score by state for ACT in 2017, Scored 1-36
'sat_2017participation'|float64|2017 SAT|Percentage of graduating HS Seniors taking the SAT in 2017, Scored 1-100
'sat_2017evidence-based_reading_and_writing'|int64|2017 SAT|Avg test scores by state in EBRW for SAT in 2017, Scored 400-800
'sat_2017math'|int64|2017 SAT|Avg test scores by state in Math for SAT in 2017, Scored 400-800
'sat_2017total'|int64|2017 SAT|Avg total test scores by state for SAT in 2017, Scored 800-1600
'act_2018participation'|float64|2018 ACT|Percentage of graduating HS Seniors taking the ACT in 2018, Scored 1-100
'act_2018composite'|float64|2018 ACT|Avg composite score for the ACT in 2018, Scored 1-36
'sat_2018participation'|float64|2018 SAT|Percentage of graduating HS Seniors taking the SAT in 2018, Scored 1-100
'sat_2018evidence-based_reading_and_writing'|int64|2018 SAT|Avg test scores by state in EBRW for SAT in 2018, Scored 400-800
'sat_2018math',|int64|2018 SAT|Avg test scores by state in Math for SAT in 2018, Scored 400-800
'sat_2018total'|int64|2018 SAT|Avg total test scores by state for SAT in 2018, Scored 800-1600


### Outside Research
`Colorado: Experienced the highest rate of change for both the ACTs & the SATs.`
- During 2018, SAT was able to secure a contract that partnered it with the Colorado, this created a wide adoption of the SAT within Colorado pushing participation rates to 100%. This also caused the ACT participation rate to fall 70% from the previous year to 30%.

- Source: https://www.washingtonpost.com/education/2018/10/23/sat-reclaims-title-most-widely-used-college-admission-test/

<br>`Illinois: Saw a ten-fold increase on SAT participation rates and a 50% decrease on the ACTs.`
- Like Colorado, the SAT was able to secure another crucial partnership here to create a ten-fold increase in participation rates.(9% in 2017 -> 99% in 2018) Similarly with Colorado, the ACT participation rates in Illinois plummeted by 53%.

- Source: https://chalkbeat.org/posts/chicago/2018/07/27/act-protests-state-boards-embrace-of-rival-test-provider/

<br>`West Virginia: Saw participation for SAT double while ACT saw a slight decrease.`
- Unlike the drastic changes in Colorado & Illinois, West Virginia experienced a notable yet not as drastic increase in SAT participants. This seems due to West Virginia offering the SAT as an optional but free test. While it may not be as heavy handed as the actions taken in Illinois & Colorado, it gives the SAT a foot-in-the-door in a state that was more ACT based (69% participation rates during ACT2017)

- Source: https://www.wsaz.com/content/news/All-WVa-high-school-juniors-to-begin-taking-SAT-exam-beginning-Spring-2018-444248263.html

### Conclusions and Recommendations

Through the outside research on variables identified through the dataset, it was easy to note that most of the drastic changes toward participation rate tended to be legislative in nature. While actions like giving the test out for free create some foothold, it seems the most effective course of action is through politicians and legislature. To that end, the college board might see best results hiring lobbyists to push for SAT adoption although the action can be seen as heavy handed. 

Additionally, perhaps a reflection of the SAT strategy compared to the ACT, the ACT boasts impressive 100% participation rates over several states, versus the SAT which has a more scattered participation rate. The reason for the ACT's high participation rates have been key contracts which partner states, which mandate taking the ACTs for students within that state. 