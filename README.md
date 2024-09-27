java c
MGT403: PROBABILITY  STATISTICS
FALL 2024
Statistics Assignment #1
Due Monday, Sept. 30 at 6:00 pm via Canvas
Logistics and Reminders.
• Problem sets turned in after the deadline will receive no credit.
• Round each final answer to four decimal places.
• Please enter your answers into the corresponding entries of Canvas’ quiz form. and attach your detailed work as either a PDF or Excel file in response to the last question of the form. Your answers can be handwritten or typed. If you have handwritten answers, please scan them, e.g., on your phone, before uploading them to Canvas. If you have Excel work, please submit as an Excel file.
• Please use the Excel template found in the Canvas folder for the assignment to record your work and answers for questions that require Excel. It may be difficult to give partial credit to work that is not clearly labeled and organized. Answers without Excel work will receive a score of zero.
• You can discuss the problems with your Learning Team, as well as the professor and TAs. You need to prepare your own write-up, however, which has to represent your own work. Collaboration with ChatGPT or other AI composition software is not permitted in this assignment. Include your first name, last name, and cohort, as well as a list of the students you worked with on page 1 of your answers.
Question I
FIFA-approved soccer balls have a circumference of between 68 cm and 70 cm. The English Pre-mier League EPL is considering switching its official match ball supplier, but worries about the ability of a new supplier to meet the FIFA guidelines reliably. The potential new supplier sources its soccer balls from several factories in Sialkot, Pakistan. EPL representatives visited two of these factories and received a batch of soccer balls from each factory for inspection.
The EPL obtained 125 balls from Factory A and 82 balls from Factory B. For each soccer ball, they measure and record the circumference in centimeters. The table below contains summary statistics for the balls by factory:
Circumference
Sample Standard
Sample Average                           Deviation                           Sample Size
Factory A                        69.85 cm                         0.75 cm              125
Factory B                             69.85                          cm 0.5            cm 82
Question I Part I [15 points]
Consider, for now, only Factory A.
1. Find a 95% and a 99% confidence interval for the average circumference of Factory A’s soccer balls.
2. What is the meaning of the 95% confidence interval in the context of this problem? Choose all answers that are correct.
❏ We are 95% confident that Factory A’s true mean soccer ball circumference falls in the range that you calculated above.
❏ Of the total number of balls produced by Factory A, 95% have a circumference in the range that you calculated above.
❏ The probability that the mean circumference of Factory A’s balls falls in the range that you calculated above is 0.95.
❏ There’s a 95% chance that a ball from Factory A has a circumference in the range that you calculated above.
❏ If we obtained 100 samples of soccer balls from Factory A and calculated a confidence interval for each sample, 95% of the intervals would contain Factory A’s true mean.
3. The EPL is satisfied with the initial inspection results: the average circumference of balls from Factory A is within FIFA’s specifications. They worry nevertheless that the average circumference is just barely below the 70 cm cutoff. Does the sample from Factory A present evidence at the 1% significance level against the hypothesis that the factory’s soccer balls’ true average circumference exceeds 70 cm? Support your conclusion by:
(a) Formulating the null and alternative hypotheses.
(b) Calculating the appropriate test statistic.
(c) Calculating the associated p-value.
(d) Interpreting the p-value.
Question I Part II [8 points]
Consider now the size of Factory A’s sample.
4. The EPL wants to be more sure that the factory meets FIFA’s match ball standards: It would like to bring the margin of error down to only 0.1 cm at the 95% confidence level.
How many additional soccer balls should the EPL inspect to achieve this level of precision? Assume that the sample standard deviation would remain unchanged.
5. Why do we need to 代 写MGT403: PROBABILITY & STATISTICS FALL 2024 Statistics Assignment #1R
代做程序编程语言increase the sample size to reduce the margin of error? Explain briefly the intuition for the change in sample size.
Question I Part III [7 points]
7. The EPL decides that the sample average circumference is not useful in assessing the facto-ries’ compliance with FIFA rules: even if the balls are correctly sized on average, there may still be individual balls whose circumference falls outside of the correct range; only a small number of soccer balls is used in each game.
The EPL therefore manipulates its data on ball circumferences. It first determines, for each ball, whether the ball’s circumference is non-compliant (that is, for ball i, it checks whether circumferencei < 68 or circumferencei > 70) and then calculates, for each factory, the share of non-compliant balls in the sample.
It finds that the share of non-compliant balls among Factory A’s 125 balls is 20.6%. The EPL is willing to tolerate a non-compliance rate of at most 15% – the rate of its current supplier. Can you conclude from the sample evidence that the factory’s true non-compliance rate is unlikely to fall below 15%? Support your conclusion by:
(a) Formulating the null and alternative hypotheses.
(b) Calculating the appropriate test statistic using a 5% significance level. Hint : What is the standard error of the sample average under the assumed null-hypothesis?
(c) Calculating the associated p-value.
(d) Interpreting the p-value.
Please enter your answers in decimal form. (i.e., use 0.5 for 50%).
Question II [20 points]
Every summer, there is considerable coverage of wildfires in the United States, and the sever-ity and extent of wildfires is a climate change indicator tracked by the Environmental Protection Agency (EPA).
The EPA publishes data on wildfire acres burned annually by state, for states that experience a wildfire in a given year, and has just released data for 2023. The dataset ”EPA Wildfires Data”, found as a separate tab in the Problem Set 1 Template Excel file, contains four variables - year, state, acres, and landarea, where acres is the number of acres burnt by wildfires in that year in the state and landarea is the state’s area in square miles, which is constant across years. The sample covers the period 1984-2023.
Use the dataset to answer the following questions.
1. Create a new variable called acrespermile, defined as acres divided by landarea. For each observation – each year and state combination – , the variable measures the number of acres burnt per square mile; going forward, the problem calls this variable “normalized acres burnt”. Determine the sample mean and sample standard deviation of the variable acrespermile. What is the mean normalized number of acres burnt over the time period? What is the sample standard deviation of the normalized number of acres burnt?
2. The EPA asserts that in the average state and year, wildfires burn 1.32 acres per square mile. Use the data to test this hypothesis at the 5% level by:
(a) Formulating the null and alternative hypotheses.
(b) Calculating the test static for your test in Excel (be sure to show the relevant formula in Excel).
(c) Calculating the p-value for your test in Excel (be sure to show the relevant formula in Excel).
(d) Interpreting your test results: based on the test statistic and the p-value, do you reject the null hypothesis, and if so why?
3. The EPA also believes that the extent of wildfires has increased over time: the average size of wildfires – in terms of acres burnt per square mile – since 2010 is larger than the average size of wildfires over prior years. The year-over-year variation in wildfire size may also have changed in the period since 2010 relative to the earlier years. Run a two-sample t test in Excel to explore the possibility that the mean normalized acres burnt after and including 2010 exceeds the mean normalized acres burnt in wildfires pre-2010. Again, use a 5% significance level.
Hint : This test requires you to have two samples, as in the Lecture 3 Excel workbook.
As above:
(a) Formulate the null and alternative hypotheses.
(b) Run the appropriate test in Excel (do not forget to show the output in your Excel work-book).
(c) Interpret your test results: based on the results, what is the p-value? Do you reject the null hypothesis, and if so why?





         
加QQ：99515681  WX：codinghelp
