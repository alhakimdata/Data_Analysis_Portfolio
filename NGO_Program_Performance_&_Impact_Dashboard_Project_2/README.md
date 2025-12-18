# NGO Program Performance & Impact Dashboard
## Subtitle: Financial accountability, efficiency, outcomes, and coverage by program

# Introduction
### What problem are we trying to solve?
NGOs operate multiple programs with limited resources, donor restrictions, and high accountability requirements. However, performance data is often fragmented across financial reports, monitoring frameworks, and beneficiary tracking sheets. This fragmentation makes it difficult for decision-makers to clearly understand:

* Whether programs are spending within approved budgets
* How efficiently resources are converted into beneficiary reach
* Which programs are achieving intended outcomes
* Where gaps exist between affected populations and actual coverage

This dashboard addresses the problem of disconnected reporting by integrating financial, operational, and outcome indicators into a single decision-support view.

### Who is this dashboard designed for?
This dashboard is designed for:
* **Program Managers** — to monitor efficiency and outcomes at the program level

* **Finance and Grants Teams** — to ensure budget compliance and spending transparency

* **Senior NGO Leadership** — to support strategic prioritization and resource allocation

* **Donors and Funding Partners** — to assess accountability, impact, and unmet needs

The design intentionally avoids technical complexity, enabling non-technical stakeholders to interpret insights quickly.

## Data Source and Preparation
* **Source:** Cleaned Excel dataset (tbl_EMDAT)

* Preparation completed prior to Power BI:

    * Verified numeric data types (USD, population, rates)

    * Validated budget variance values

    * Ensured outcome rates stored as decimals

    * Confirmed program-level aggregation

No further transformation was required inside Power BI.

## Analytical Approach
Key performance indicators were implemented using **DAX measures** to ensure correct aggregation and donor-aligned calculations:

* Total Budget (USD)

* Total Actual Spending (USD)

* Budget Variance (USD)

* Cost per Beneficiary (USD – weighted)

* Average Outcome Rate (%)

* Total Affected Population

* Total Beneficiaries Served

Measures were prioritized over raw columns to avoid misleading totals.

## Homepage
![Homepage](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/NGO_Program_Home.png)



## Dashboard Overview

![Dashboard 1](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/NGO_Program_Dashboard.png)

The dashboard presents **four integrated visuals** on a single page:

1. Budget vs Actual Spending

2. Cost per Beneficiary

3. Outcome Rate by Program

4. Total Affected vs Beneficiaries Served

Four KPI cards provide executive context at the top of the dashboard.


## Visual Analysis & Insights

### Budget vs Actual Spending (by Program)
![Chart-1](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/Budget_vs_Actual_Spending.png)

#### Insight
Spending closely aligns with approved budgets across programs, demonstrating strong financial control and accountability.

### Cost per Beneficiary (by Program)
![Chart-2](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/Cost_per_Beneficiaries.png)

#### Insight
Cost efficiency varies by program type, reflecting differences in operational complexity and intervention scope.

### Outcome Rate (%) by Program
![Chart-3](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/Outcome_Rate.png)

#### Insight
Most programs meet or exceed outcome benchmarks, with slight underperformance in recovery-focused interventions.

### Total Affected vs Beneficiaries Served
![Chart-4](https://github.com/alhakimdata/Data_Analysis_Portfolio/blob/main/NGO_Program_Performance_%26_Impact_Dashboard_Project_2/Images/Total_Affected_vs_Beneficiaries_Served.png)

#### Insight
Significant coverage gaps remain, highlighting unmet needs and supporting justification for additional funding.

## Conclusion (Evidence-BAsed)

Based on the analysis, the dashboard reveals **uneven program performance and coverage across NGO interventions**, despite similar funding or activity presence.

Key conclusions drawn from the visuals are:

1. **Program scale does not automatically translate to effectiveness**

    Some programs serve a large affected population but convert only a portion into actual beneficiaries. This suggests operational, access, or targeting constraints rather than funding shortages alone.

2. **Outcome rates vary meaningfully across programs**

    While outcome rates cluster between approximately **74%–81%**, the differences are material in an NGO context. Programs with lower outcome rates may require:

    * Process improvements

    * Better targeting criteria

    * Stronger monitoring and follow-up mechanisms

3. **Coverage gaps are visible and measurable**

    The comparison between _Total Affected and Beneficiaries Served_ highlights a **consistent service gap**, indicating unmet needs that are not immediately obvious in narrative reports alone.

4. **High-performing programs provide benchmarks, not conclusions**

    Programs with higher outcome rates should be treated as **learning benchmarks**, not final success stories. Their practices can inform underperforming programs, but context (location, population, risk exposure) must be considered.

5. **The data supports prioritization, not judgment**

    The dashboard does not label programs as “good” or “bad.” Instead, it enables decision-makers to:

    * Identify where marginal improvements could yield the greatest impact

    * Allocate monitoring, capacity-building, or funding support more strategically

------------------
Also, this Power BI dashboard transforms static Excel reporting into a decision-grade NGO analytics tool. It enables transparent financial oversight, performance comparison, and evidence-based funding discussions.