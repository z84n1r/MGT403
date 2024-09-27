java c
MGT403: Probability  Statistics
Fall 2023
Statistics Examination - 2023
Analytic Part
Question 1 (29 points)
The US Fisheries and Wildlife Service (FWS) requires that the average meat per mussel in any ship’s mussel catch must be at least 0.5 ounces.
Suppose the FWS draws a simple random sample of 1,000 mussels from a ship with a large mussel catch. The average meat per mussel in the sample is 0.48 ounces, and the sample   standard deviation is 0.3 ounces.
You may use the Normal Distribution approximation for all calculations in this problem because the sample size is sufficiently large.
a.  (4 points). What is the standard error for the estimated average meat per mussel, given the sample size and the estimated standard deviation?
b.  (4 points). Find a 90% confidence interval for the average meat per mussel in the ship’s entire catch. Interpret this confidence interval (in precise words).
c.  (4 points). Suppose that the true average meat per mussel in the ship’s entire catch is 0.5  ounces, and the standard deviation of the meat per mussel in the ship’s entire catch is 0.3 ounces. What is the probability that the average meat per mussel in a simple random sample of 1,000 mussels will be 0.48 ounces or less?The FWS enforces its mussel meat requirement by imposing penalties based on the results of its random sample of 1,000 mussels from each ship’s catch. The penalties for under-weight catches are as follows:
.    If the average meat per mussel is greater than 0.5 ounces, then no penalty is imposed.
.    If the average meat per mussel in the sample is less than 0.45 ounces, then the FWS confiscates the ship’s entire catch.
.    If the average meat per mussel is between 0.45 and 0.5 ounces, then the FWS confiscates a fraction of the ship’s entire catch according to the formula:
Fraction confiscated = 20 ×(0.5 一 average meat per mussel in the sample)
d.  (4 points) Suppose, as in part (c), that the true average meat per mussel in a ship’s entire
catch is 0.5 ounces, and the standard deviation of the meat per mussel in the ship’s entire catch is 0.3 ounces. Find the 5th and the 95th percentile of the probability distribution for the fraction of the catch that will be confiscated by the FWS.
The FWS believes that its current penalty scheme is too arbitrary since its penalties are based on a sample and hence are subject to sampling error. It has also received a complaint from the operator of the above ship who asserts that their catch complies with regulations even though the average meat per mussel in the sample falls short of the FWS’ threshold.
Consider the above sample of 1,000 mussels with an average meat per mussel of 0.48 ounces and a sample standard deviation of 0.3 ounces. The FWS would like to assess the operator’s claim that the average meat per mussel in the ship’s entire catch exceeds the FWS’ threshold of 0.5 ounces: the sample results reflect pure chance. They perform. a hypothesis test at a significance level of α = 1% using the sample data.
e.  (2 points) State the null hypothesis and alternative hypothesis for this test.
f.   (4 points) Draw a graph that shows the set-up to test the null hypothesis. Place the sample average on your graph and use it to indicate the p-value for your test in the graph. Label all relevant elements of your graph.
g.  (3 points) Calculate the test statistic and p-value for your test. Based on your computation, do you reject or fail to reject the null hypothesis?
h.  (4 points) The FWS decides that they are comfortable with their current penalty rule if they can reject the test’s null hypothesis at a 1% significance level for samples like this one. They wonder how large a sample they would need to collect to ensure this is the case.Given the estimated standard deviation of 0.3 ounces and average of 0.48 ounces of meat,  what is the range of values for sample size N for which you would reject the null hypothesis at the 1% significance level?
Question 2 (16 points)
A consultant is working on a project for a client who would like to understand how to allocate advertising budgets across social media platforms to drive sales.The client provides the consultant with three years’ worth of data on weekly units sold (in  thousands) and the fraction of the firm’s weekly advertising budget spent on each of three social media platforms: Facebook, Instagram, and YouTube. Thus, if the client spent $1 on  Facebook out of a budget of $10, they would say the fraction spent on Facebook is 0.10.
The data show the following descriptive patterns:

Average
SD
Sales (000)
14.13
5.26
Fraction Spent, Facebook
0.15
0.14
Fraction Spent, Instagram
0.66
0.22
Thus, the client spent, on average, a fracﬁon of 0.19 of their adverﬁsing budget on YouTube.
The consultant also performs a correlaﬁon analysis. Each entry in the following table corresponds to the correlaﬁon between the corresponding row and column variables, e.g., the correlaﬁon between the fracﬁon of the weekly budget spent on Facebook and weekly sales in  units is -0.31.

Sales (000)
Fraction Spent
Facebook
Instagram
Sales (000)
Fraction Spent, Facebook Fraction Spent, Instagram
1代 写MGT403: Probability & Statistics Fall 2023R
代做程序编程语言.00
-0.31 0.48


1.00 -0.78



1.00
The consultant runs a regression of sales (left hand side) on fraction spent on Instagram (right hand side).
a.  (3 points). What is the coefficient on fraction spent on Instagram for this model?
b.  (3 points). What is the intercept for this model?
c.  (2 points). What is the model’s R-square?
After running this regression, the consultant decides that it is easier to think in percentages than fractions. She therefore expresses spending on Instagram as a percentage of the total budget.
That is, suppose now:
percentage, Instagram = 100 × Total Budget/Instagram Budget
The consultant then runs a new regression of sales (left hand side) on percentage spent on Instagram (right hand side).
Answer the questions in parts (d) through (g), providing a one-sentence explanation for your answer.
d.  (2 points). How would the slope of this new model change relative to the slope you estimated in part (a)?
e.  (2 points) How would the intercept change relative to the intercept you estimated in part (b)?
f.   (2 points) How would the regression standard error change relative to the regression standard error from the model using the fraction spent on Instagram?
The consultant also worries that sales do not reflect only Instagram advertising in isolation, but also advertising on the other social media platforms. She therefore considers estimating the following model:
sales = a + b1  × Fraction, Instagram + b2  × Fraction, Facebook + e
g.  (2 points) Using the information from this problem, determine how the inclusion of the variable fraction spent on Facebook would affect the coefficient on fraction spent on
Instagram, relative to the coefficient in part (a).
The coefficient on Fraction spent on Instagram (check one answer only):
o Increases                                              Decreases
o Remains the same                                 o Too little information to tell
Provide a concise explanation for your choice.
Question 3 (18 points)
Steve has just accepted a job in San Francisco and will soon put his house in New Haven up for  sale. However, before purchasing a new home in the Bay Area, he wants to get an idea of what price he can expect to get for his New Haven house. He is also considering what, if any, renovations might be worthwhile before selling the house.
Steve has obtained the prices of 50 homes that were sold in New Haven County in the past month. The data set includes the following variables:
Price:                Actual selling price of the house in thousands of dollars.
Square Footage:  Size of the home’s living area in square feet.
Bedrooms:          Number of bedrooms in the house.
Bathrooms:        Number of bathrooms (“half” baths count as 0.5).
Garage Size:        Number of cars that can park in the home’s garage.
He runs a regression of Price on the other variables and obtains the following results:

a.  (5 points) Steve’s house is 1900 square feet, has three bedrooms, one and a half
bathrooms, and a small one-car garage. Based on the regression model above, what is the predicted selling price for his house?
b.  (5 points) Steve is considering renovating the front half-bathroom before selling the
house. Specifically, he could break down the exterior wall to his half-bath and expand it to a full-sized bathroom. This will add 20 square feet to the house. The project will cost $15,000. What is Steve’s expected net profit from this plan?
c.  (4 points) Alternatively, Steve could spend $10,000 to remodel his garage to
accommodate two cars instead of one. This plan will leave the home’s living area and other features unchanged. What is Steve’s expected net profit from this plan?
d.  (4 points) Because Steve has only 50 observations in his regression, he is concerned that sampling error may cause him to make the wrong decision with respect to the garage
remodel. Does the regression provide evidence at the 5% level that Steve should expect to make a positive net profit on the garage remodel? (I.e., can you reject the hypothesis that he should expect to make a negative profit?) Provide the test-statistic, p-value, and conclusion for this test.
Even though Steve has only 50 observations, assume for the purposes of this problem that you can use the Normal distribution to calculate the p-value for this test.
e.  (3 points extra credit) Steve believes that the effect of the number of bedrooms on sale price is nonlinear. Specifically, he believes that the sale price increases for each additional bedroom at a constant amount for the first, second, and third bedroom. He believes that the sale price increases by a smaller constant amount for the fourth and fifth bedroom, but that any additional bedrooms beyond five do not generate any value.
Steve would like to construct one or multiple variables that would allow him to test his beliefs about the impact of the number of bedrooms on sale price (in addition to the remaining variables he controls for – square footage, bathrooms, and garage size).
Define the appropriate variable or variables; be clear and precise.



         
加QQ：99515681  WX：codinghelp
