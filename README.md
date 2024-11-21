java c
SCHOOL OF INFORMATION SYSTEMS AND TECHNOLOGY MANAGEMENT 
TERM 2 2024 
COMM1190: DATA, INSIGHTS,  DECISIONS 
SAMPLE EXAMINATION 
QUESTION 1  10 MARKS 
Suppose you work as an actuary and want to model the 5-year mortality rates (i.e., the probability of death within five years) for a group of 1,000 life insurance policyholders aged 50. You have the following information for each: 
• Gender
• Type of work (manual or non-manual)
• Living area (High affluence, Middle class, Deprived)
• Health condition (Terminally ill, Sick, healthy)
The following classification tree is obtained for the binary variable denoting the Status of the policyholder as observed in the data. The Status variable takes a value equal to 0 if the policyholder is alive at the end of the study (5 years, where the policyholders are observed starting at the age of 50 until age 55) and 1 if dead. 



Required: 
With reference to the above case, please answer all of the following questions:Part A [max 100 words]  (5 marks)  What does each number in a node represent? Please describe the results in the node circled in red.
Part B [max 100 words]  (5 marks)  
What are the most influential variables characterising policyholders’ mortality in order of importance?QUESTION 2  30 MARKS 
A financial institution has decided to implement a Machine Learning (ML) algorithm to automate its loan approval process. The algorithm, developed by a third-party AI solutions provider, is designed to analyse a range of consumer data to determine loan eligibility and terms. To maintain a transparent process, the firm offers applicants the option to discuss the loan outcome decision with a representative. The representatives are well-trained in explaining how the applicant's data influenced the loan decision. 
The third-party developer has provided the firm with two versions of the algorithm. The first version is "gender-blind," designed to exclude any variables that could directly or indirectly reveal an applicant's gender. The second version incorporates gender-specific features, which can enhance the accuracy of loan predictions based on statistical differences in financial behaviour across genders. The third-party developer is also open to feedback on variables to include in the model and how to determine who is loan-worthy.
Required: 
With reference to the above case, please answer all of the following questions:
Part A [max 80 words]  (4 marks)  
Given a choice between the gender-blind version and the gender-specific version of the loan  decision algorithm, identify which option the firm should choose to use and any general adjustments that could be made to make the algorithm more responsible.Part B [max 120 words]  (6 marks) 
Considering the scenario, identify and discuss the issues that raise concerns under the Australian Responsible AI Principles, focusing specifically on fairness, accountability, transparency, and contestability.Part C [max 240 words]  (12 marks)
The firm has a dataset of 15,000 people. The results of the model are graphically presented as follows:

Create confusion matrices to determine the following:
I.          The overall accuracy rate
II.         The overall false positive rate
III.        The accuracy rate for men
IV.       The false positive rate for men
V.        The accuracy rate for women
VI.       The false positive rate for womenPart D [max 160 words]  (8 marks) 
I.       Based on the confusion matrix, explain why you believe or do not believe the predictive model is fair.
II.      1500 new clients (1000 men and 500 females) have applied for loans and need
to be assessed. The third-party developer can adjust the model so that it selects  500 men and 250 females to be selected for loans. What are the advantages and disadvantages of this approach? Should the firm update the model to this approach?QUESTION 3  30 MARKS 
Cookie Cats is a popular puzzle game app. As players progress throug代 写COMM1190: DATA, INSIGHTS, & DECISIONS TERM 2 2024Web
代做程序编程语言h the levels of the game, they occasionally encounter gates that force them to wait a non-trivial amount of time  or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in the player's enjoyment of the game being increased and prolonged.
The question to be explored is whether the placement of the entry-level gate matters. The hypothesis being investigated is whether moving the entry-level gate from 30 to 40 will increase player activity (and hopefully in-game purchases).
Data was collected from an A/B test where a total of 90,198 players were randomly assigned to a treatment group (entered at gate level 40, g_40=1) or a control group (entered at gate level 30, g_40=0). The output variables of interest included in the data are:
ret_ 1 = 1 if the player plays within one day of installing the app; and = 0 otherwise; games = total number of games played in the first 14 days of installing the app.
Note: For this question, the 97.5th percentile of a standard normal distribution is 1.96.Part A. [max 100 words]  (5 Marks) 
Before formally investigating the hypothesis being tested within the experiment, good practice dictates that an analyst determines the key features of the data. See below for selected summary statistics and visual representations. What are your main conclusions about the key variables based on this initial analysis? 
Part B. [max 100 words]  (5 Marks) 
Do you have enough information to test whether the random assignment has been successful? If not, how would you check?
Part C. [max 100 words]  (5 Marks)  
Now consider the regression of ret_ 1 on g_40. The results are given below. What do they indicate? (You can assume random assignment to the two groups has been successful.)
Test the null hypothesis of no treatment effect of using gate 40 as the entry point rather than gate 30.
Part D. [max 100 words]  (5 Marks)  
Given the following regression results test the null hypothesis of no treatment effect using games as the outcome of interest. Results from a second version of this regression are run but only for those in the sample who played less than 3000 games. Is this a sensible regression to run? Why? What do you conclude from these results?
Part E. [max 200 words]  (10 Marks) 
Summarise your results to the management of the game developer Tactile. Given the primary question posed by the developer, recommend to management whether the placement of the entry-level gate has a causal impact on in-game purchases.
QUESTION 4  30 MARKS
Imagine you work for a large department store, which highly values customer service. The following chart shows how customers contact the customer service centres.

You begin to discuss the chart with your manager. Immediately, she has the following queries: “I want to see the overall trends, but it is difficult to see with all the seasonal spikes  in the time series. I’d like a simpler view into the trend.” You decide to create some charts to address your manager’s queries.Part A. [max 100 words]  (5 Marks)  Using the two-question four frameworks typology, identify the type of chart you would use to  address the query and explain why.
Part B. [max 300 words]  (15 Marks)  
Sketch two alternative charts for the query. For each chart, provide a brief explanation of your design choices. To sketch the chart, you can use any tool you want (e.g., you can use a software tool like Excel or R). Alternatively, you can sketch the chart using pencils, pens, or markers on paper, then take a picture of the charts and paste them into your solutions document. You can access the underlying data “customer_service.xlsx” on Ed.
Part C. [max 200 words]  (10 Marks)  
Evaluate your two charts and explain which you would select to further develop to present to  your manager. 









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
