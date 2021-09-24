# Statistical Experiments and Signficance Testing
The goal of this notebook is to explore an A/B testing dataset found on Kaggle. In this dataset, multiple users are shown the current web page (control group) while other users are shown a new page.A summary of the finding is presented below:
- The conversion of the control group is 12.03% and the conversion of the treatment group is 11.89%.
- There is a 89.5% that there is in fact a effect due to the treatment and that the discrepency is not just a result of chance (ie p-value of 0.105).
- By target in advance what the goal of the experiment is, the sample size can be greatly reduced, for example:
    - A sample of 64602 observations is necessary to have a 95% chance detecting a 5% increase in conversions with an alpha of 0.05.
    - A sample of 20000 observations is enough to have a 50% chance detecting a 5% increase in conversions with an alpha of 0.05.
