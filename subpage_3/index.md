---
layout: default
---
# **OM_621**
* * * 

This subpage is the README file for a new repository with previous homework assignments done in Python, **OM_621**. It is not in your interest to utilize any of the information, there are errors. I am learning. Again, this repository is for homework assignments for Dr. Karimi, California State University of San Marcos. 

**GitHub Homework Repository, OM_621** 
[github.com/aeczuniga/OM_621_assignments](https://github.com/aeczuniga/OM_621_assignments)

[PowerBI dashboard for repository](https://app.powerbi.com/groups/me/reports/bfebf438-371b-459a-b0bd-3ab190c083a4?ctid=128753ab-cb28-4f82-9733-2b9b91d2aca9&pbi_source=linkShare)

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

**`STEP 1`**

_Who_

Hollandia Dairy, a local company in Escondido. They have reached out to my employer for assistance, the problem is that Hollandia Dairy is receiving delayed invoices. As a consulting firm, it is my responsibility to present a solution that solves their problem. As someone specializing in supply chain, this problem can be solved, it is part of the supply chain.

_What_

I want Hollandia Dairy to know the terms & conditions of the different shipping providers, what is viewed as late may be stipulated in the terms & conditions. Using visual analytics, I can show how some shipping providers may be within an acceptable industry average

_How_

I would like to have an initial and follow-up meetings with the stakeholders requesting the consulting service, virtual meetings will give me the opportunity to engage with the staff at Hollandia Dairy and understand their concern. Then, a report discussed in person, at Amazon, managers discuss reports in person, it allows stakeholders to ask questions, and the author can address all concerns, mention why certain processes will not work or what else has been implemented elsewhere that works and the factors that contributed to success. A report is given more thought into what is written, how it is phrased, it is concise, whereas discussing a report is more informal, responses can be tailored in a manner that is easily understood in the moment. The value of discussion is the contribution of people.

**`STEP 2`**

I want to read the company’s standard operating procedures (SOP) to see if departments are failing to abide by SOPs. If departments are abiding by SOP’s, documents may provide insight into conflicting processes needing to re-evaluate or be more thorough. I want to understand why some departments use 3PL’s and other’s use transportation carriers, it may be that the product being shipped requires climate-controlled temperature but there may be other factors that influence the decision to choose 3PL’s or carriers. The purchasing of shipping services is not happening through one individual or department, it is mentioned that “particular” shipments receive delayed invoices, making me think that departments are not working accounting with accounting to record the liability (purchase) until it is paid. All bids must have a limited acceptable range that is subject to change, a similar policy should be included in the procurement contracts if the business has a procurement department. 

1. Read the company’s and department policies.
2. Look into the shipping providers that send delayed invoices according to Hollandia Dairy, maybe they are within their policy.
3. Look into how departments relay what is being purchased (shipping service) to accounting, the company is having a hard time forecasting expenses to budget.

**`STEP 3`**

To understand the problem in context, I must read. The data I need is standard operating procedures, policies, forms, shipment data, invoicing dates, invoice amounts, and divisions. After obtaining SOP policies, I want to know their contracts with the various shipping providers, identifying if shipping providers are not following their contractual obligations. I may be able to identify if the problem is not with shipping providers, rather it is with Hollandia Dairy, not understanding the contractual commitment. It is important to the data by the different modes of transportation.

**`STEP 4`**

Hollandia Dairy is a local company in San Diego, accounts payable is receiving invoices in a timeframe that inhibits the accounting department from creating a timely budget that tracks their liabilities. Looking at the company’s problem, departments place their own orders, there is no department or person taking ownership for purchasing. The risk is that invoices can get lost if they are not tracked or paid on time, incurring fines. The goal is to create collaboration across departments and centralize Hollandia’s purchasing, making it possible for accounting to have one person or department they can reach out to if invoices are not received on time.

**`STEP 5`** 

**Potential Recommendations**

1. Get procurement to see if better pricing is obtainable by choosing to create partnerships instead of purchasing services from different shipping providers. Procurement can establish a person of contact within the shipping providers to assist Hollandia Dairy with documents needed, estimated expenses. By partnering with one or two shipping providers, shipping times can improve, improving lead times for consumers. Procurement can reach out to the legal department and establish contracts where estimates must be submitted within “x” amount of time after placing an order and cannot be greater than “x” percent, improving accounting’s tracking of liabilities. 
2. Centralize all buying one person or department assume the responsibility of purchasing to work with accounting.
3. Have the person or department taking the responsibility of purchasing work with accounting, providing estimated expenses to create a budget, forecast.

***

# **Project Portfolio**
Again, please understand I am learning and I am documenting my experience.


[Static Github Page](https://aeczuniga.github.io/)

[How I deployed a static webpage and the challenges I experieced.](https://aeczuniga.github.io/subpage_1/)

[Homework repository, OM_620.](https://aeczuniga.github.io/subpage_2/)