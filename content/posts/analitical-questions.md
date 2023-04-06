---
title: "Analytical questions (PM prep #3)"
date: 2023-03-26T23:12:15+02:00
draft: false
---

_NOTE: This is part of the series on PM interview prep_

The goal of these questions is to test your ability in understanding and reasons with metrics. Some common questions in this category fall under the following categories: 
- Metrics & Data
- A/B testing
- Execution (separate post)

# Metrics questions
The GAME framework can be useful to answer these types of questions.
- **G**oal: Make sure to clarify the goals for the product. Things you might want to touch upon are the vision of the product, or where the product should be in say 5 years time.
- **A**ctions: Define the action you will need your users to make in order to support the above goals. For example, what are the features will drive engagement? Maybe we want to focus on users upgrading their accounts?
- **M**etrics: Identify the metrics that will help us capture those actions. Number of upgrades could be an example. This will ensure we have a way of measuring the actions that drive us towards our goals.
- **E**valuate: As usual, you should try to reflect on the given answer. How could the metrics drive to false-negatives or false-positives? Could the metrics incentivise the wrong behaviours?

# A/B testing questions
- **Hypothesis**: Start off by stating the hypothesis you are planning to validate via the A/B test. Use the following structure: by X I expect to see an increase/decrease in Y.
- **Methodology**: Describe how the experiment will take place. Typically, you will want to split the user population in 2 groups, 50% will see the current experience, while the other 50% will see an altered version of the experience. Take some time to explain who should be the target for this experiment: should all the use population be exposed, or should it target a subset of users?
- **Metrics**: On top of the main metric you included in your hypothesis, what other metrics do you think you want to keep track of? There should be a list of metrics you want to keep an eye on. 
- **Impact**: Explain to the interviewer how the results from the experiment will be useful. How should the results be interpreted? How do they tie to the overall goals of the company?
- **Tradeoffs**: Identify potential pitfalls to launching the proposed feature that won't be evident via a quantitative test? Qualitative aspects here are important.
