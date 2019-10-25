# Finnq Model CAS

## Chris | Alexander | Samad (CAS)

--- 

### Opening Thoughts

Upon beginning our project to classify users based upon the questions they answered, we realised there was a problem: the amount of data we can collect from questions asked in an on-boarding process is minimal. 

Hence, we decided to reconsider the way we could obtain insights from Finnq users to create targeted experiences.

---

### Project Scope (Working Thesis):

**"We are looking to understand how using a user persona model will allow for greater optimisation and a better, personalised user experience for incoming FinnQ users."**

We seek to achieve this in a three step process:
- Start asking 4-6 questions when a user first opens the Finnq app and signs up. This will classify them into one out of less than 10 classification groups.
- Perform an analysis to understand which services certain users are currently using based on classification data (age, gender, income brackets, time spent on particular screens).
- Use this information to collect insights that can help to adjust and tailor the way we construct our classification groups so that new users can immediately have a better experience.

---

### Variables To Consider:

**Categorical:** 
- Age
- Gender
- Ethnicity
- Income Bracket
- Level of Education

**User variables:**
- Time spent on individual screens
- Type of account linked
- User of particular Features

---

### Potential User Personas:

#### *Either Age Differentiated*

- **Infant** (Savings, largely on behalf of other peers) (High Confidence) 
- **Early Millenial** (Heavy FinTech User, Limited use of Banking) (High Confidence)  
- **Late Millenial** (Larger Savings, Taking Credit) (Middle Confidence) 
- **Mid-Life** (Monitoring Investment Portfolio) (Middle / Low Confidence Variable)  
- **Retiree** (Monitoring Savings, Concerned about Safety) (Low Confidence)

Source: (Rooney, 2015)

#### Or Role Differentiated:

- **Student**  
- **First Time Homebuyer**  
- **Retiree**
- **Investor**  
- **Family Member (Child, Parent, Spouse, etc)**

---

### Technical Approach:

We will be using Python3 for a number of reasons: 
- Readability.
- Support libraries for data science.
- Object oriented.
- Learning opportunity for future.

The types of packages we plan to use include: `statistics`, `random`, `numpy`, `matplotlib`,`seaborn`, `tqdm`, and `networkx`, among others.

*Nota bene:* We will not be using Finnq data, nor will we try to represent Finnq data to a high degree of accuracy. In other words, the model will not tell us information about existing customers.

The point of this model is to provide an example of how a user persona approach could be beneficial for Finnq upon being applied to Finnq data. The data fields provided by Finnq will only be useful in considering the type of data Finnq collects so that we can supplement our model further to make it more accurate in personalisation.

---

### Project Output:

- A white paper: to show the statistical analysis/data gather process, the model used, the rationale behind the model, and a guide for implementing the model on Finnq's data for the future.
- The model itself.
- A short presentation that represents our whitepaper research in a presentable format.
