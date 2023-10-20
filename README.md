**UCB Data Analysis Module 5**
## Data Visualization Challenge: Analysis of Capomulin Study: 45-day Trial

---------------
#### Purpose:
Process raw data from a pharmaceutical study to determine the performance of a new drug, Capomulin, for the treatment of cancerous tumors in mice. The study also examines 8 competitor drugs marketed for the same treatment as well as a placebo for baseline comparison.  The analysis will either support or disprove Pymaceuticals' claims about the efficacy of Capomulin as a potential cancer treatment.  

  
   
IMPORTANT: Upon reaching the section of the analysis for "Quartiles, Outliers and Boxplots" I made the decision to exclude data from the following [4] research subjects: b447, t573, u153, x226.  Each of these subjects was treated with Ceftamin, however only one datapoint was recorded for each mouse.  The instructions indicate to "Calculate the final tumor volume of each mouse across four of the treatment regimens" to show efficacy of the treatment over time.  This is not possible with only one datapoint.  By including the "final" tumor weight for these 4 subjects (which was actually the initial weight prior to the start of treatment) we risk introducing data that could unfairly skew the results one way or another.  In my opinion, it's best to exclude incomplete data that doesn't contribute to our end goal.

--------------
#### Contents of Repository:
1 x Jupyter notebook (pymaceuticals_FINAL.ipynb)  
2 x .csv files (data source for analysis)  
4 x jpg images (also embedded in .ipynb markdown)  
1 x README file

-------------------
#### Contributions:  
Just blood, sweat and tears!

------------------
#### License:
[MIT](https://choosealicense.com/licenses/mit/)


