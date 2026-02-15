# Azure Cost Management Lab: Budgets + Alerts (Subscription Scope)

This repository supports my lab walkthrough video on using **Azure Cost Management** to create a **subscription budget**, configure **alert thresholds**, and review spend using **Cost analysis**.  
📺 **Watch the lab video on YouTube:** 

---

## 🔍 Lab Overview

In this lab, you’ll learn how to:

- Create a **budget** at **subscription scope**
- Configure budget **alerts** at common thresholds (50%, 80%, 100%)
- Add email recipients (and optionally action groups)
- Verify the budget configuration in the **Budgets** blade
- Use **Cost analysis** to review spend and investigate cost drivers

These tasks are foundational for cost governance and preventing unexpected Azure charges.

---

## 🧪 Lab Scenario

Your organization wants better cost visibility and guardrails for cloud spending. You are responsible for creating a subscription budget and setting up alerts so the team is notified when spend reaches specific thresholds, enabling quick action before costs exceed expectations.

---

## 🛠️ Key Tasks

✅ **Task 1: Open Cost Management + Billing**
- In the Azure portal, search **Cost Management + Billing**
- Navigate to **Cost Management**

✅ **Task 2: Create a Subscription Budget**
- Go to **Budgets**
- Set **Scope** to your **Subscription**
- Create a budget named `budget-az104-lab`
- Set reset period to **Monthly**
- Set a small amount (example: `$10`)
- Set an expiration date (end of year or next few months)

✅ **Task 3: Configure Budget Alerts**
- Add threshold alerts:
  - **50%** (Actual)
  - **80%** (Actual)
  - **100%** (Actual)
- Add **email recipients**
- (Optional) Configure an **Action group**

✅ **Task 4: Verify Budget + Review Cost Analysis**
- Confirm `budget-az104-lab` appears in **Budgets**
- Open it and review:
  - Amount, time period, thresholds
- Use **Cost analysis** to:
  - Confirm the scope
  - Change date range
  - Group by resource group/service (optional)

---

## 📁 Suggested Files

- `lab-guide.md`: Full lab steps in markdown format for offline use  
- `screenshots/`: Budget creation, alert thresholds, and cost analysis views  
- `notes.md` (optional): Quick “exam takeaways” like budget scope + alert behavior  

---

## 🔗 Learn More

- [Cost Management overview](https://learn.microsoft.com/azure/cost-management-billing/costs/overview-cost-management)  
- [Tutorial: Create and manage budgets](https://learn.microsoft.com/azure/cost-management-billing/costs/tutorial-acm-create-budgets)  
- [Cost alerts (monitor usage and spending)](https://learn.microsoft.com/azure/cost-management-billing/costs/cost-mgt-alerts-monitor-usage-spending)  
- [Cost analysis (learn more)](https://learn.microsoft.com/azure/cost-management-billing/costs/cost-analysis-common-uses)

---

## 🧵 Tags

`#Azure` `#CostManagement` `#Budgets` `#Governance` `#AZ104` `#AzureLabs`

Created by: **Zion Spearman**  
Use and modify this lab freely for study and practice.
