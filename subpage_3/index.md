---
layout: default
---
# **OM_621**
* * * 

This subpage is the README file for a new repository with previous homework assignments done in Python, **OM_621**. It is not in your interest to utilize any of the information, there are errors. I am learning. Again, this repository is for homework assignments for Dr. Karimi, California State University of San Marcos. 

**GitHub Homework Repository, OM_621** [github.com/aeczuniga/OM_621_assignments](https://github.com/aeczuniga/OM_621_assignments)

***
# VIDEO walk-through
**WATCH FIRST**
[]()

***

# Assignments | Python
***

The **first Python assignment** is addressing basic data exploration.

**Question 1** looks into invoicing delays according to a company experiecning delayed invoicing. This question addresses my process for the entire project. Ultimately, there is a seasonality and mode factor influencing delayed invoicing but I think contractual terms should be looked over to ensure all is well.
    
**Question 2** looks missing values and basic calculations like average and minimum, starting simple. Only three columns have null, empty, nan values, it is interesting that all columns have an invoice amount. I decide drop empty cells that are not bound by a make to stock "MTS" invetory type. The code is interesting, non-null and is-null values, identifying empty vales and counting them. 
    
**Question 3** creates a ggplot to visualize the data, making it easy to identify information instead of calculations. The geom_bar makes it easy to identify what I looking for, sites and mode of transportation.
    
**Question 4** I format (tarnsform) column types to ensure they are workable, converting dates. I still use a ggplot to visualize the data and expand. Some sites do seem to have greater delays, site US77 seems to be the main culprit followed by US62. There seems to be a correlation between delay and invoice amount. The delay increases as the invoice amount increases but it does not occurr as much past invoice amount of $100,000.
    
**Question 5** Looks further into invoicing delays according to transportation mode. Utilzing a **facet_grid** makes it obvious that **less_container_load** (LCL) and **full_container_load** (FCL) have the greatest delays. LCL is delayed by more than 16 weeks whereas FCL is under 10 weeks.


***

The **second Python assignment** creates data analysis by looking into causation and correlation.

**Question 6** utilizes boxplots to address the delay according to mode of transportation. The boxplot confirms the LCL as having the greatest delay, like the **facet_grid** from **Question_5**. 

**Question 7** explores invoice delays by time, comparing shipping dates to invoice amounts. There seems to be a correlation, as the year progesses the delay increases. parcel_ground seems to be the most volatile but LCL has been getting worse over three years. Most transportation modes reset once the new year begins according to how I am filtering the data but not LCL. I would suggest looking further into that mode of transportation.

**Question 8** finishes up the assignment with a discussing on invoice amounts and delays. There is monthly seasonality and trends, I think certain modes of transportation must looked into further, looking into the operating procedure and comparing against the standard operating procedure. I still beleive it is crucial to know contractual terms.


# Assignments | Story
***



# **Project Portfolio**
Again, please understand I am learning and I am documenting my experience.


[Static Github Page](https://aeczuniga.github.io/)

[How I deployed a static webpage and the challenges I experieced.](https://aeczuniga.github.io/subpage_1/)

[Homework repository, OM_620.](https://aeczuniga.github.io/subpage_2/)

[Homework repository, OM_621.](https://aeczuniga.github.io/subpage_3/)