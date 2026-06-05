# A-B-Testing-a-Search-Ranking-System-for-an-Online-Travel-Agency
In this project, I take on the role of a data scientist at an online travel agency that has developed a new search ranking system intended to improve booking conversion. I evaluate the system through a controlled A/B test, in which users are randomly divided into a control group exposed to the existing system and a treatment group exposed to the new one. Using Python, I examine the experiment data, verify that the test was set up fairly, measure the difference in conversion rates between the two groups, and apply statistical testing to determine whether any observed improvement reflects a genuine effect rather than random chance. I then translate these findings into a clear, evidence-based recommendation on whether the company should roll out the new system

**Approach**

Data preparation: Joined session-level and user-level data into a single analysis-ready dataset and engineered the primary metric, conversion (whether a session ended in a booking).

Experiment validation: Ran a Sample Ratio Mismatch (SRM) check using a chi-square test to confirm the control and variant groups were split as intended.
Statistical testing: Assessed the significance of the treatment effect on the primary metric (conversion) and a guardrail metric (time_to_booking) at a significance level of α = 0.1.

Effect sizing: Quantified relative effect sizes for both metrics to gauge practical, not just statistical, impact.

Decision: Applied predefined roll-out criteria to deliver a clear, evidence-based "full-on" or "pull-back" recommendation.
