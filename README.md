# FBI NICS Firearm Background Check Data Investigation
## by Olamide SHOGBAMU

### Introduction
The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase.

The FBI provides data on the number of firearm checks by month, state, as a PDF and later converted to comma seperated values for analysis purpose, which currently covers November 1998 – July 2022 [Click here](https://raw.githubusercontent.com/BuzzFeedNews/nics-firearm-background-checks/master/data/nics-firearm-background-checks.csv) to view the csv.

**Objective of the analysis**
- Examines the overall trend of the different types of gun purchase,
- Predict the type of gun that will be acquired more in the coming years, and
- solves the problem of which which type of gun is most used in the millitary.


## Features
- **Data Wrangling**
    - Data gathering
    - Data Assessment
    - Data Cleaning
- **Exploratory Data Analysis**
- **Data Visualization**

## Summary and Conclusion
The project analyse data of the FBI NICS Firearm Background Check. The data presented useful infromation such as date, states, permit, and the various types of gun. The data was cleaned and normalize. We found out that other gun does not have a rental column leaving us with the information that other guns are not available for rent.

We explored the line trend of each type of gun to find the gun trends. From the analysis we can conclude that though long gun has the highest peak, the hand gun is more consistent in growth meaning that in the coming years more of the hand gun will be adopted.

Also looking at the line graph of the other gun, we notice a relative low patronage in its usage except for a particular time when it sky rocketed and come down again leaveing us with a conclusion that other gun are most needed in demanding spceial cases.

## Installation

This project requires [Jupyter Notebook](https://jupyter.org/) and [python 3](https://www.python.org/downloads/) to run.

Install the dependencies and libraries and start the server.

```sh
pandas as pd
numpy as np
matplotlib.pyplot as plt
seaborn as sns
```
