### JMSC 1003 Statistics for Journalists
Journalism and Media Studies Centre
The University of Hong Kong

Prepared by Chung-hong Chan (https://github.com/chainsawriot)  chainsawtiney@gmail.com

# Problem Set #7

Central Limit Theorem and confidence intervals

# Problem statement

Understand the mechanics of CLT

# Task 1

(5 marks)

Random number generator (RNG) is a computational or physical device to generate a sequence of numbers that lack any pattern. For example, six-sided dice is a common RNG. Tabletop role-playing games such as Dungeons & Dragon may need to use obscure dices such as "d20" (20-sided dice) or even "d100".

Excel function RANDBETWEEN() is also a RNG that can generate a sequence of (pseudo-)random numbers with uniform distribution. Computer RNG is the essential component of Monte Carlo simulation.

Using RANDBETWEEN() to simulate 1, 5 and 20 six-sided dice for 5000 times, plot the sample mean of the score from each trial as a histogram. (i.e. there should be 3 histograms, each for one simulations)

Calculate the mean and standard deviation (hint: using STDEVPA) of sample means from 3 simulations. Do they have the same "mean of sample means"? Why do they have different standard deviations? Explain your answer using the Central Limit Theorem.

# Task 2

(6 marks, Exam 2012)

The Public Opinion Programme, University of Hong Kong (HKUPOP) study the approval rating of the Chief Executive every two weeks using "random digit dialing" telephone survey. The question asked in the telephone survey is:

__If a general election of the Chief Executive were to be held tomorrow, and you had the right to vote, would you vote for Leung Chun-ying?__

In the latest survey, the (effective) sample size is 1008.There are 60.3% of the respondents said No.

1. What is the margin of error for this survey? (assuming 95% confidence)
2. What is the 95% Confidence Intervals of the 60.3% percentage reported above?
3. Extract all the approval rates of CY Leung from 2015 and Calculate the 95% CI of the above all results (percentage answer "No") and plot them as a line chart. Comment on when did the approval rating of CY Leung changed significantly recently. What happened during that week?
4. State all the assumptions and conditions on how and why the result from this survey can be used to infer the overall approval rating of CY Leung in the entire Hong Kong population?

LINK TO THE CLEANED DATA: https://docs.google.com/spreadsheets/d/1B-Fw-d2RbvHDQcQ7O9d6Pajg4vgr0H0tuDKrpCJuj5Y/edit?usp=sharing

# NOTE

* Please turn in one single PDF file with your name and your student ID clearly marked. Anything not in PDF (such as docx or xlsx) will not be graded. PDF converted from Excel workbook will not be graded.
