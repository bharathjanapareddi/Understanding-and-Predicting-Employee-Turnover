# Understanding-and-Predicting-Employee-Turnover
**Objective:**

1)To understand what factors contributed most to employee turnover.

2)To perform clustering to find any meaningful patterns of employee traits.

3)To create a model that predicts the likelihood if a certain employee will leave the company or not.

4)To create or improve different retention strategies on targeted employees.

The implementation of this model will allow management to create better decision-making actions.


**The Problem:**
One of the most common problems for companies is turnover.

Replacing a worker earning about 50,000 dollars cost the company about 10,000 dollars or 20% of that worker’s yearly income according to the Center of American Progress.

Replacing a high-level employee can cost multiple of that...

Cost include:

*Cost of off-boarding
*Cost of hiring (advertising, interviewing, hiring)
*Cost of onboarding a new person (training, management time)
*Lost productivity (a new person may take 1-2 years to reach the productivity of an existing person)

Annual Cost of Turnover = (Hiring + Onboarding + Development + Unfilled Time) * (# Employees x Annual Turnover Percentage)

Annual Cost of Turnover = (1,000 + 500) x (15,000 * 24%)

Annual Cost of Turnover) = 1500 x 3600

Annual Cost of Turnover) = 5400000

Example
Jobs (earning under 30k a year): the cost to replace a 10/hour retail employee would be 3,328 dollars.
Jobs (earning 30k-50k a year) - the cost to replace a 40k manager would be 8,000 dollars.
Jobs of executives (earning 100k+ a year) - the cost to replace a 100k CEO is 213,000 dollars.

**Conclusion**
**Binary Classification:** Turnover V.S. Non Turnover

**Instance Scoring:** Likelihood of employee responding to an offer/incentive to save them from leaving.

**Need for Application:** Save employees from leaving

In the employee retention problem, rather than simply predicting whether an employee will leave the company within a certain time frame, I would much rather have an estimate of the probability that he/she will leave the company. I would rank employees by their probability of leaving, then allocate a limited incentive budget to the highest probability instances.

Consider employee turnover domain where an employee is given treatment by Human Resources because they think the employee will leave the company within a month, but the employee actually does not. This is a false positive. This mistake could be expensive, inconvenient, and time consuming for both the Human Resources and employee, but is a good investment for relational growth.

Compare this with the opposite error, where Human Resources does not give treatment/incentives to the employees and they do leave. This is a false negative. This type of error is more detrimental because the company lost an employee, which could lead to great setbacks and more money to rehire. Depending on these errors, different costs are weighed based on the type of employee being treated. For example, if it’s a high-salary employee then would a company need a costlier form of treatment? What if it’s a low-salary employee? The cost for each error is different and should be weighed accordingly.

**Solution 1:**

Company can rank employees by their probability of leaving, then allocate a limited incentive budget to the highest probability instances.
OR, company can allocate thier incentive budget to the instances with the highest expected loss, for which they will need the probability of turnover.

**Solution 2:**

Develop learning programs for managers. Then use analytics to gauge their performance and measure progress. Some advice:

Be a good coach
Empower the team and do not micromanage
Express interest for team member success
Have clear vision / strategy for team
Help team with career development
