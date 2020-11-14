# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Problem statement

Since 1926, SAT is the most well known standardized test in US. Over the past decade, ACT has been gaining substantial popularity. In 2012, its number of test participants exceeds SAT. Practically, all American college will accept the scores of either test for admission considerations and awarding merit-based scholarships. It is important to study the statistical relationship of SAT, ACT and its scores, to gain insights for recommendations to improve SAT participation rate.

### Executive summary

For this project, we will focus on 2017 and 2018 datasets.

Key highlights:
- It was observed that participation rate is inversely proportional to their respective scores
- SAT participation rate median is 14% higher in 2018 as compared to 2017
- In 2018, ACT participation rate median is 14% higher than SAT

Research Findings
- Certain states, example Colorado and Illionis, show drastic participation rate improvement to 100% in 2018 due to:
Statewide mandatory implementation and state covered cost of SAT for all their public students. 


Appropriate Recommendations
- Convince respective states to adopt SAT test as a statewide mandatory test.
- Improving SAT test by improving test structure, affordability, accessibility and awareness

#### Data dictionary

|       DATA DICTIONARY (METADATA)      	|         	|         	|      	|                    	|             	|       	|                                                                                                                                                                                                                        	|
|:-------------------------------------:	|:-------:	|:-------:	|:----:	|:------------------:	|:-----------:	|:-----:	|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:	|
| Feature                               	|   Type  	| Dataset 	| Year 	| Data Description   	|    Scale    	| Level 	| Feature   Description                                                                                                                                                                                                  	|
| state                                 	|  object 	| SAT/ACT 	| 2017 	|        name        	|      50     	| State 	| Participating   US states                                                                                                                                                                                              	|
| sat_participation_17                  	|  float  	|   SAT   	| 2017 	|        rate        	|  0 to 100%  	| State 	| count   of students taking test divided by total students, in percentage                                                                                                                                                              	|
| sat_evidence_based_reading_writing_17 	| integer 	|   SAT   	| 2017 	|     mean score     	|  200 to 800 	| State 	| Students   will be tested on reading comprehension and analysis skills for the given   short passages. Writing test requires participants to correct grammatical   errors or poor stylistic choices in order to score. 	|
| sat_math_17                           	| integer 	|   SAT   	| 2017 	|     mean score     	|  200 to 800 	| State 	| Maths                                                                                                                                                                                                                  	|
| sat_total_17                          	| integer 	|   SAT   	| 2017 	|      sum score     	| 800 to 1600 	| State 	| Sum   of maths and evidence based reading and writing. Each subject weighs 50%                                                                                                                                         	|
| act_participation_17                  	|  float  	|   ACT   	| 2017 	|        rate        	|  0 to 100%  	| State 	| count   of students taking test divided by total students, in percentage                                                                                                                                                              	|
| act_english_17                        	|  float  	|   ACT   	| 2017 	|     mean score     	|   1 to 36   	| State 	| Test   on english grammar & usage, punctuation, sentence structure, strategy,   organization, and style                                                                                                                	|
| act_math_17                           	|  float  	|   ACT   	| 2017 	|     mean score     	|   1 to 36   	| State 	| Pre-algebra,   elementary algebra, intermediate algebra, coordinate geometry, plane   geometry, and trigonometry                                                                                                       	|
| act_reading_17                        	|  float  	|   ACT   	| 2017 	|     mean score     	|   1 to 36   	| State 	| English   reading comprehension of what is directly stated or implied                                                                                                                                                  	|
| act_science_17                        	|  float  	|   ACT   	| 2017 	|     mean score     	|   1 to 36   	| State 	| Interpretation,   analysis, evaluation, reasoning, and problem solving                                                                                                                                                 	|
| act_composite_17                      	|  float  	|   ACT   	| 2017 	| overall mean score 	|   1 to 36   	| State 	| Aggregate   of mean all subjects                                                                                                                                                                                       	|
| sat_participation_18                  	|  float  	|   SAT   	| 2018 	|        rate        	|  0 to 100%  	| State 	| count   of students taking test divided by total students, in percentage                                                                                                                                                              	|
| sat_evidence_based_reading_writing_18 	| integer 	|   SAT   	| 2018 	|     mean score     	|  200 to 800 	| State 	| Students   will be tested on reading comprehension and analysis skills for the given   short passages. Writing test requires participants to correct grammatical   errors or poor stylistic choices in order to score. 	|
| sat_math_18                           	| integer 	|   SAT   	| 2018 	|     mean score     	|  200 to 800 	| State 	| Maths                                                                                                                                                                                                                  	|
| sat_total_18                          	| integer 	|   SAT   	| 2018 	|      sum score     	| 800 to 1600 	| State 	| Sum   of maths and evidence based reading and writing. Each subject weighs 50%                                                                                                                                         	|
| act_participation_18                  	|  float  	|   ACT   	| 2018 	|        rate        	|  0 to 100%  	| State 	| count   of students taking test divided by total students, in percentage                                                                                                                                                              	|
| act_english_18                        	|  float  	|   ACT   	| 2018 	|     mean score     	|   1 to 36   	| State 	| Test   on english grammar & usage, punctuation, sentence structure, strategy,   organization, and style                                                                                                                	|
| act_math_18                           	|  float  	|   ACT   	| 2018 	|     mean score     	|   1 to 36   	| State 	| Pre-algebra,   elementary algebra, intermediate algebra, coordinate geometry, plane   geometry, and trigonometry                                                                                                       	|
| act_reading_18                        	|  float  	|   ACT   	| 2018 	|     mean score     	|   1 to 36   	| State 	| English   reading comprehension of what is directly stated or implied                                                                                                                                                  	|
| act_science_18                        	|  float  	|   ACT   	| 2018 	|     mean score     	|   1 to 36   	| State 	| Interpretation,   analysis, evaluation, reasoning, and problem solving                                                                                                                                                 	|
| act_composite_18                      	|  float  	|   ACT   	| 2018 	| overall mean score 	|   1 to 36   	| State 	| Aggregate   of mean all subjects                                                                                                                                                                                       	|

#### Conclusions

The below is the summary of the takeaways:

**Histogram study**
- Participation rate, mean math, reading/verbal for ACT, SAT for both years does not exhibit normal dustribution. They do not have normal distribution characteristics such as unimodal, symmetric, bell-curve(mean = median =mode).

**Scatter plot study**
- Math and reading/verbal scores for SAT is not corelated to ACT.
- SAT total score is not corelated to ACT total composite score.
- However, mean total scores for SAT and ACT can be co-related for different years. This shows the mean total scores were comparable year to year for each test.

**Boxplot study**
- SAT participation rate improved from 2017 to 2018. This is due to 11 states had they SAT test cost covered by public schools, implementation of SAT school day program. Multiple participation rate improvement resulting 25% participation rate increase in 2018.
- ACT has approximately 21% higher participation rate than SAT
- Reading is the top scoring subject for both SAT and ACT

**Scatter plot study**
- Higher participation rate was observed when the mean total/composite scores were low for both test.
- There are more 100% participation rate for ACT than SAT

**Colorado, Illinois, Ohio study**
- Colorado and Illinois had participation rate reaches 100% in 2018, 90% improvement from 2017. They are the 2 states out of 10, which state covered the cost of SAT from 2017-18.
- Opportunity arises as ACT's contract of 15 years ended. SAT won the contract to administer SAT test for 2017 onwards. However, there is still significant participation rate observed for ACT test in 2018. This is due to schools had commited ACT training/test to students previously during the first 2 years.
- Likewise, Ohio state's ACT 2018 participation rate rose due to state paid for the test. Their total composite dipped because it was the first time many students went for the test.

**Recommendation:**
- After studying the improvement of participation rates of 3 states (Colorado, Illinois and Ohio), it was observed that participation rate will increase to 100% if state covers the cost of the test and also made a test mandatory.
- From the Illionis example, window of opportunity swung open after ACT's contract ended. Hence, it is important to identify similar opportunities in oher states to replicate the Illinois's participation rate increase.
- Another suggestion will be substituting/partnering with Smarter Balanced test as many states still using PARCC and Smarter Balanced test. Examples are, California, Hawaii, Montana, Nevada, Oregon, South Dakota, Vermont, and Washington.
- With that, state to be selected to improve partipation rate will be California. Reason is:

1) No mandatory test assigned.

2) Califonia is using Smarter Balanced test which can consider for partnership

3) High population density

4) Currently low in particption rate. Hence there is room for participation improvement.

Other possible recomendations includes:
- Improving test structure to prepare students for college 
- Improve affordability by extending income eligible scheme to waive fee to low income households
- Improve accessibility by bringing test location to schools on days that are convenient to students. Also to offer testing and preparation material at a discount to the state
- Launch campaigns to promote SAT test
