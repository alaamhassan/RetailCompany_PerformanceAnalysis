# Sales Performance Analysis - Excel Project

### Table of Contents 

This project consists of:

**four phases**:

1️⃣ [Ask Phase](#ask_phase)  
2️⃣ [Process Phase](#process_phase)  
3️⃣ [Analyze Phase](#analyze_phase)  
4️⃣ [Share Phase](#share_phase)

**four deliverables**:

1️⃣ [Scope of Work](#scope_of_work).<br />
2️⃣ [Changelog Document](#changelog_process_phase) (Process Phase).<br />
2️⃣ [Changelog Document](#changelog_analyze_phase) (Analyze Phase).<br />
3️⃣ [Dashboard](#Dashboard).<br />
4️⃣ [Insights Report](#insights_report).<br />

<a name="ask_phase"></a>
## 1️⃣ Ask Phase:
I went through **5** steps.

❶ **Understand the Business Problem**

The CEO of a retail company that sells bags, shoes, accessories, and other related products has a record of all the orders in the years 2019 and 2020. The CEO wants to know if his business is going in the right direction or not.

❷ **Understand the stakeholders’ expectations**

This helps in identifying the end goals of the project:

🚩 Determine if the company’s sales performance improved in the year 2020 over 2019.

🚩 Identify strategies for improving sales performance.

❸ **Understand the Problem Domain**

This helps in identifying the KPIs and insights needed to achieve the goals of the project.

❹ **Asking the right questions**

Going through the previous steps helps to know which questions to ask. These are the questions that, if answered, the goals of the project will be achieved.

❺ **Making the Scope of Work Report**

<a name="scope_of_work"></a>
📰 Making the [Scope of Work](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Ask_Phase/Scope%20of%20Work.pdf) report is the last step in this phase.
<a name="process_phase"></a>
## 2️⃣ Process Phase:
In this step, I had to make sure that the data is:

📌 Accurate

📌 Complete

📌 Trustworthy

📌 Comprehensive

The data was made sure it:

* aligns with business logic.
* doesn’t contain duplicates.
* doesn’t contain mistyping.
* doesn’t contain blank fields.
* doesn’t have mismatched data types.
  
and many others…

<a name="changelog_process_phase"></a>
📰 if the data violates any of those things, it will be both cleaned and documented in the 
[Changelog Document](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Process_Phase/Changelog%20Documentation.pdf).

✅ The Process phase resulted in **17 Changes** taking the IDs from C1 to C17 in the [Changelog Document](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Process_Phase/Changelog%20Documentation.pdf).

<a name="analyze_phase"></a>
## 3️⃣Analyze Phase:

In this phase, I want through **three** steps:

❶ **Adjusting and Adding any needed column for analysis**

<a name="changelog_analyze_phase"></a>
✅ In this step, I have **adjusted and added 8 columns** for analysis taking the IDs from C18 to C25 in the [Changelog Document](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Process_Phase/Changelog%20Documentation.pdf). 

❷ **Performing EDA (Exploratory Data Analysis)**

I performed EDA to know the distribution of certain columns to determine if average or median was the most appropriate solution to measure the central value.

❸ **making pivot tables**
I used power pivot to make pivot tables.

<a name="share_phase"></a>
## 4️⃣Share Phase:

There are two deliverables in this phase:

<a name="Dashboard"></a>
1. **Dashboard**:
   
  This **dashboard is dynamic**, which changes by:
  *  changing 9 slicers.
  *  show vs revenue or net profit.
  *  show as values or percentages.

  both the labels and the headers change.
  
  The Dashboard Contains four pages:
  
  📃**Page 1 (Profit Page)**:
  
  ![image](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/assets/67596481/865c4e96-5986-4e64-86b0-c9cbe4518bdf)

  This page answers the following 6 questions:
  
  **KPIS**
  * Calculate total net profit growth in 2020 compared to 2019, given in both absolute terms and as a percentage.
  * Determine the average order value in 2020 compared to 2019, given in both absolute terms and as a percentage.
  * Determine the average discounted order in 2019 and 2020 total, given in both absolute terms and as a percentage.
    
  **Graphs**
  * Display net profit/revenue from both old and new consumers for each month during 2020 and 2019.
  * Display the discount category versus the total net profit/revenue.
  * Display net profit/revenue for each month during 2020 and 2019.

  📃**Page 2 (Customers Page)**:
  
  ![image](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/assets/67596481/d566be47-5f8f-4d01-9608-ae895d138072)
  
  This page answer the following 7 questions:
  
  **KPIS**
   * Calculate the customer acquisition rate in 2020 compared to 2019, given in both absolute terms and as a percentage.
   * Determine the customer retention rate in 2020 compared to 2019, given in both absolute terms and as a percentage.
   * Determine the average discounted order in 2019 and 2020 total, given in both absolute terms and as a percentage.
     
  **Graphs**
   * Display the number of unique consumers for both old and new consumers each month during 2019 and 2020.
   * Display the number of orders for both old and new consumers each month during 2019 and 2020.
   * Display the total number of unique consumers per total number of orders made.
   * Display the total net profit/revenue per total number of orders made.
   * Display the top 7 consumers that contributed most to net profit/revenue during 2019 and 2020.

  📃**Page 3 (Products Page)**:
  
  ![image](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/assets/67596481/5572c919-e702-4aa0-9753-1be0b518c8d9)

  This page answer the following 4 questions:
  
  **Graphs**
  * Display the best-selling category each month during 2019 and 2020.
  * Display the number of orders for each category (Line Category).
  * Display net profit/revenue versus category (Line Category) cost for each category.
  * Display the top 5 best and bottom 5 selling products(line SKU) label by category as a percentage for both new and returning customers during 2019 and 2020.

  📃**Page 4 (Reports Page)**:  
  
  ![image](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/assets/67596481/e4b69b12-a520-4fa1-a840-45602b56977a)

  This page contains links to three reports:
  * [Scope of Work](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Ask_Phase/Scope%20of%20Work.pdf).
  * [Changelog Document](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Process_Phase/Changelog%20Documentation.pdf).
  * [Insights Report](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Share_Phase/Insights_Report.pdf).

  it also contains the final suggestions based on the data insights.

2. **Insights Report**:
   
   <a name="insights_report"></a>
   📰 An [Insights Report](https://github.com/alaamhassan/RetailCompany_PerformanceAnalysis/blob/main/Share_Phase/Insights_Report.pdf) which contains a detailed report of the project findings.
  
    



