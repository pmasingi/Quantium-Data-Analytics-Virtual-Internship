# Quantium Data Analytics Virtual Internship
Data analysis tasks for the Quantium Virtual Internship using Python
This repository contains my solutions to the Quantium Data Analytics Virtual Internship.

#Task 1: Data Validation and Customer Insights
* *Goal:** Analyze chip purchasing behavior to identify high-value customer segments.
* **Key Tools:** Python (Pandas, Matplotlib).
* **Findings:** Identified "Mainstream Young Singles/Couples" as a target segment, specifically preferring 175g Kettle brand chips.

#Task 2: Store Trial Analysis (A/B Testing & Uplift)
* *Goal:** Evaluate the impact of a new chip category layout in trial stores (77, 86, 88).
* **Action:** * Identified "Control" stores for each trial store by calculating **Pearson Correlation** and **Magnitude distance** based on monthly sales and customer counts.
    * Developed a Python function to automate store matching.
    * Conducted **Uplift testing** to compare trial store performance against control stores during the trial period (Feb 2019 - April 2019).
* **Results:** * Confirmed a significant sales increase across all trial stores.
    * Specifically, Trial Store 88 saw a **36% sales lift**, and Store 77 saw a **29% lift**.
    * Provided statistical evidence that the new layout drives higher revenue.
