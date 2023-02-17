# ****Indian Election Analysis****

> **India's lower house of Parliament, the Lok Sabha, has 543 seats in total. Members of Lok Sabha (House of the People) or the lower house of India's Parliament are elected by being voted upon by all adult citizens of India, from a set of candidates who stand in their respective constituencies. Every adult citizen of India can vote only in their constituency. Candidates who win the Lok Sabha elections are called 'Member of Parliament' and hold their seats for five years or until the body is dissolved by the President on the advice of the council of ministers.**
> 
> 
> **There are more than 700 million voters with more than 800,000 polling stations.**
> 
> **The Lok Sabha election is a very complex affair as it involves a lot of factors. It is this very fact that makes it a perfect topic to analyze.**
> 
> **Currently there are two major parties in India, Bhartiya Janta Party(BJP) and Indian National Congress(INC).**
> 
> **As India is country of diversities, and each region is very different from every other region, there are a lot of regional or state parties having major influences. These parties can either support any of the alliance to make a government or can stay independent.**
> 
> **There are two major alliances, the NDA led by BJP and the UPA led by INC.**


### **There are two datasets:**

### **1. 2009 Candidate dataset:**

The candidate dataset has 15 features namely 'ST_CODE', 'State_name', 'Month', 'Year', 'PC_Number', 'PC_name', 'PC_Type', 'Candidate_Name', 'Candidate_Sex', 'Candidate_Category', 'Candidate_Age', 'Party_Abbreviation', 'Total_Votes_Polled', 'Position','Alliance'.

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings
import seaborn as sns
warnings.filterwarnings("ignore")

### **2. 2009 Electors dataset**

The elector dataset consist of 8 features namely 'STATE CODE', 'STATE', 'PC NO', 'PARLIAMENTARY CONSTITUENCY','Total voters', 'Total_Electors', 'TOT_CONTESTANT', 'POLL PERCENTAGE'.


# **Interesting questions that we can ask**

- State vs Poll Percentage
- Candidate Age Distribution
- Candidate Gender Distribution
- State vs No of contestants in the state
- Total Votes distribution party wise

# Important Insights

- ****As can be seen that the number of female candidates in the elections are significantly less.****
- **Most of the candidates are of the in the age bracket of 40 - 50 but the age bracket of winner candidates is between 50-70.**
- **The vote share of Indian National Congress(INC) is highest followed by the Bhartiya Janta Party(BJP). The interesting observation here is the Bahujan Samaj Party(BSP) despite being a regional party has the third highest number of vote share.[¶])**
- ****Four out of the top five states with respect to polling percentages are a part of the north-east India which is considered to be amongst the least developed parts of India.****
- ****As mentioned earlier regional parties have major influences, the highest number of seats won in UP are by Samajwadi Party(SP). Also Bahujan Samaj Party(BSP) is trailing behind INC only by a few seats.****
- ****Maharashtra is dynamic state with various parties winning seats in the election with UPA getting the highest seats followed by NDA.****
- ****Lakshadweep, Daman & Diu, Dadra & Nagar Haveli and Ladakh have less than 20000 electors.****
- ****INC have won almost 43 % of the total seats followed by BJP with 24% seats.****
