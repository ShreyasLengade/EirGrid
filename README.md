# Electric Grid Station Project Management Dashboard
This power Bi fashboard visualises Porject management of electric grid porjects. It utillises the risks,


### 🟦 Page: Executive Summary
🎯 Purpose
This page gives a high-level overview of the entire project portfolio so stakeholders can quickly understand overall performance, risks, and financial status without going into detailed reports.
<img width="1868" height="1033" alt="image" src="https://github.com/user-attachments/assets/dbbea6a0-9f0c-477b-bd50-c4f484f4efd3" />

🔎 Filters (Top Section)
These slicers let users narrow down the data shown on the page.
  Region → View projects for a specific geographic region
  County → Drill down to a county level
  Workstream → Filter by type of work or program
  RAG Status → Show projects by health status (Red, Amber, Green)
  Clear Filter button → Reset all selections to default
👉 Helps users quickly focus on a specific subset of projects.

📊 KPI Cards (Portfolio Snapshot)
These cards show the most important metrics at a glance:
  Projects → Total number of projects in scope
  On Track Projects → Projects currently performing well
  Late Milestones → Total delayed milestones across projects
  Milestones Due Next 90 Days → Upcoming workload indicator
  Budget (€) → Total planned budget
  Actual (€) → Actual spend to date
  Variance (%) → Over or under budget percentage
  High Open Risks → Count of critical risks needing attention
👉 Gives leadership a quick health check of the portfolio.

📋 Project Table (Detailed View)
This table lists individual projects with key performance indicators:
  Project Name → Identifier of each project
  RAG Status → Visual health indicator
  🟢 Green = On track
  🟠 Amber = Needs attention
  🔴 Red = At risk
  Attention Score (0–100) → Priority level (higher = more attention needed)
  Late Milestones → Number of delayed milestones
  Variance (%) → Budget deviation for the project
  Risk Exposure (€) → Financial impact of risks
  Readiness Score → Overall preparedness level
👉 Enables users to quickly identify problem projects and investigate further.

💡 What Users Can Do on This Page:
Get a portfolio-level health snapshot in seconds
Identify projects that need immediate attention
Understand financial performance vs plan
Spot risk concentration areas
Filter to analyze specific regions or programs

Here’s a simple GitHub-style explanation for the Delivery & Milestones page 👇

### 🟦 Page: Delivery & Milestones
🎯 Purpose:
  This page helps users understand where project delays are happening, how serious they are, and who owns them.
  It is mainly used by delivery teams and PMOs to track schedule risks and take corrective action.

🔎 Filters (Top Section)
  Region → View delays for a specific region
  County → Drill down to local level
  Workstream → Focus on a specific type of work
  RAG Status → Filter by project health
  Clear Filter button → Reset filters
👉 Lets users analyse delays for any slice of the portfolio.

<img width="1851" height="1058" alt="image" src="https://github.com/user-attachments/assets/7607a8ef-f01b-4c31-94b3-bba7b118243e" />

📊 Visual 1: Where Schedule Slips
Chart: Late Projects by Milestone Phase
  Shows how many late projects exist in each project phase:
  Construction
  Planning & Consents
  Commissioning
  Procurement
  Design
👉 Helps identify which stage of the lifecycle causes the most delays.

📊 Visual 2: Delay Severity
Chart: Late Projects by Workstream and Delay Days
  This stacked chart shows delay severity across workstreams:
  15–30 days
  31–60 days
  60+ days
  Workstreams include examples like:
  Substation Build, Overhead Line, Underground Cable, Grid Automation, etc.
👉 Helps teams understand not just where delays happen but how big they are.

📊 Visual 3: Delay Ownership Heatmap
Table: Late Projects by Phase and Owner
  Shows where delays sit across:
  Milestone phases (rows)
  Responsible roles (columns), such as
  Commercial Manager
  Construction Manager
  Engineering Manager
  PMO Lead
  Stakeholder Manager
  Color intensity indicates higher delay concentration.
👉 Helps identify which teams or roles need focus.

🧠 Drillthrough / Insight Panel (Pop-up)
<img width="2153" height="1045" alt="image" src="https://github.com/user-attachments/assets/8e8e3b51-a341-4606-b9c7-969a62aaae0d" />

When users click a data point, a detailed insight appears showing:
  Top Delay Reason (e.g., Permits/Consents)
  Milestone Name (e.g., Planning Approval)
  Suggested actions to address the issue
List of impacted projects with:
  Workstream
  Region and county
  Slippage days
👉 Enables quick root-cause analysis and action planning.

💡 What Users Can Do on This Page:
Identify which project phase drives delays
Understand delay severity across workstreams
See who owns the delays
Perform root cause analysis using drillthrough
Prioritise corrective actions

### 🟦 Page: Forecast and Controls
🎯 Purpose
This page helps finance and delivery teams understand how spending is tracking against plan, whether projects are expected to overrun or underrun, and what the future cost outlook looks like.

🔎 Filters (Top Section)
  Region → View financial performance by geography
  County → Drill down to local level
  Workstream → Focus on a specific program or type of work
  Year → Analyse a specific financial year
  Quarter → Compare performance for a selected quarter
  RAG Status → Filter by project health
  Clear Filter button → Reset all filters
👉 Enables financial analysis at different levels of detail.

📊 KPI Cards (Financial Snapshot)
  EAC variance vs baseline (%):
  Shows whether the forecasted final cost is above or below the original budget
  Actual variance %:
  Indicates how much actual spend differs from plan
  Remaining Forecast (€):
  Amount still expected to be spent until project completion
👉 Gives a quick view of overall cost performance and outlook.

📉 Visual 1: Forecast vs Baseline
  Chart: Baseline Budget vs EAC Variance
  Shows how the final forecast (EAC — Estimate at Completion) compares to the original budget:
  Baseline Budget
  EAC Variance (increase or decrease)
  Final EAC
👉 Helps answer:
Are we expecting a cost overrun or savings?

📉 Visual 2: Budget vs Actual (Selected Quarter)
  Chart: Actual Spend vs Planned Spend
  Displays:
  Actual Spend
  Variance
  Planned Spend
👉 Helps answer:
Did we spend more or less than planned this quarter?

🧠 Interpretation Section (Bottom Text)
  Provides guidance on how to read the visuals, explaining:
  Difference between quarterly overspend vs overall forecast
  How remaining forecast reflects future expected costs
👉 Helps non-finance users interpret the numbers correctly.

💡 What Users Can Do on This Page:
  Understand cost performance vs plan
  Identify potential overruns early
  Analyse quarterly spending behaviour
  Track remaining financial exposure
  Support budget control and forecasting decisions
