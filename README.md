
<h1>Electric Grid Station Project Management Dashboard</h1>

<p>
  This Power BI dashboard provides an end-to-end view of a large project portfolio, combining delivery performance,
  schedule tracking, risk exposure, and financial forecasting in one place.
</p>
<p>
  It is designed to help leadership, PMOs, and delivery teams quickly understand the health of projects, identify risks early,
  and make informed decisions using real-time insights.
</p>
<p>
  The dashboard brings together operational and financial metrics across regions, workstreams, and time periods, enabling both
  high-level monitoring and detailed root-cause analysis through interactive visuals and drill-downs.
</p>

<h2>🎯 What Problem This Dashboard Solves</h2>
<p>
  Large infrastructure or program portfolios often face challenges such as fragmented reporting, delayed issue identification,
  and limited visibility into financial performance. This dashboard addresses these challenges by:
</p>

<ul>
  <li><b>Providing a single source of truth:</b> Consolidates project, schedule, risk, and financial data into one unified view</li>
  <li><b>Improving decision speed:</b> Leadership can quickly identify underperforming projects and take action</li>
  <li><b>Highlighting delivery risks early:</b> Pinpoints late milestones, delay drivers, and high-risk areas</li>
  <li><b>Enhancing financial control:</b> Shows budget vs actuals, forecast overruns, and remaining spend</li>
  <li><b>Enabling root-cause analysis:</b> Interactive drilldowns reveal why delays or variances are happening</li>
  <li><b>Supporting proactive management:</b> Helps teams prioritise interventions before issues escalate</li>
</ul>

<h2>💡 Value Delivered</h2>
<ul>
  <li>Better portfolio visibility</li>
  <li>Faster issue identification</li>
  <li>Stronger governance and accountability</li>
  <li>Data-driven planning and forecasting</li>
  <li>Improved stakeholder reporting</li>
</ul>

<hr/>

<h2>🟦 Page: Executive Summary</h2>
<h3>🎯 Purpose</h3>
<p>
  This page gives a high-level overview of the entire project portfolio so stakeholders can quickly understand overall
  performance, risks, and financial status without going into detailed reports.
</p>

<img width="1868" height="1033" alt="Executive Summary" src="https://github.com/user-attachments/assets/dbbea6a0-9f0c-477b-bd50-c4f484f4efd3" />

<h3>🔎 Filters</h3>
<ul>
  <li><b>Region:</b> View projects for a specific geographic region</li>
  <li><b>County:</b> Drill down to a county level</li>
  <li><b>Workstream:</b> Filter by type of work or program</li>
  <li><b>RAG Status:</b> Show projects by health status (Red, Amber, Green)</li>
  <li><b>Clear Filter:</b> Reset all selections to default</li>
</ul>
<p><i>Helps users quickly focus on a specific subset of projects.</i></p>

<h3>📊 KPI Cards</h3>
<ul>
  <li><b>Projects:</b> Total number of projects in scope</li>
  <li><b>On Track Projects:</b> Projects currently performing well</li>
  <li><b>Late Milestones:</b> Total delayed milestones across projects</li>
  <li><b>Milestones Due Next 90 Days:</b> Upcoming workload indicator</li>
  <li><b>Budget (€):</b> Total planned budget</li>
  <li><b>Actual (€):</b> Actual spend to date</li>
  <li><b>Variance (%):</b> Over or under budget percentage</li>
  <li><b>High Open Risks:</b> Count of critical risks needing attention</li>
</ul>
<p><i>Gives leadership a quick health check of the portfolio.</i></p>

<h3>📋 Project Table</h3>
<ul>
  <li><b>Project Name:</b> Identifier of each project</li>
  <li><b>RAG Status:</b> Visual health indicator (🟢 On track, 🟠 Needs attention, 🔴 At risk)</li>
  <li><b>Attention Score (0–100):</b> Priority level (higher = more attention needed)</li>
  <li><b>Late Milestones:</b> Number of delayed milestones</li>
  <li><b>Variance (%):</b> Budget deviation for the project</li>
  <li><b>Risk Exposure (€):</b> Financial impact of risks</li>
  <li><b>Readiness Score:</b> Overall preparedness level</li>
</ul>
<p><i>Enables users to quickly identify problem projects and investigate further.</i></p>

<h3>💡 What Users Can Do</h3>
<ul>
  <li>Get a portfolio-level health snapshot in seconds</li>
  <li>Identify projects that need immediate attention</li>
  <li>Understand financial performance vs plan</li>
  <li>Spot risk concentration areas</li>
  <li>Filter to analyse specific regions or programs</li>
</ul>

<hr/>

<h2>🟦 Page: Delivery &amp; Milestones</h2>
<h3>🎯 Purpose</h3>
<p>
  This page helps users understand where project delays are happening, how serious they are, and who owns them.
  It is mainly used by delivery teams and PMOs to track schedule risks and take corrective action.
</p>

<img width="1851" height="1058" alt="Delivery &amp; Milestones" src="https://github.com/user-attachments/assets/7607a8ef-f01b-4c31-94b3-bba7b118243e" />

<h3>🔎 Filters</h3>
<ul>
  <li><b>Region:</b> View delays for a specific region</li>
  <li><b>County:</b> Drill down to local level</li>
  <li><b>Workstream:</b> Focus on a specific type of work</li>
  <li><b>RAG Status:</b> Filter by project health</li>
  <li><b>Clear Filter:</b> Reset filters</li>
</ul>
<p><i>Lets users analyse delays for any slice of the portfolio.</i></p>

<h3>📊 Visual 1: Where Schedule Slips</h3>
<p><b>Late Projects by Milestone Phase</b></p>
<ul>
  <li>Construction</li>
  <li>Planning &amp; Consents</li>
  <li>Commissioning</li>
  <li>Procurement</li>
  <li>Design</li>
</ul>
<p><i>Helps identify which stage of the lifecycle causes the most delays.</i></p>

<h3>📊 Visual 2: Delay Severity</h3>
<p><b>Late Projects by Workstream and Delay Days</b></p>
<ul>
  <li>15–30 days</li>
  <li>31–60 days</li>
  <li>60+ days</li>
</ul>
<p>
  Workstreams include examples like Substation Build, Overhead Line, Underground Cable, Grid Automation, etc.
</p>
<p><i>Helps teams understand not just where delays happen but how big they are.</i></p>

<h3>📊 Visual 3: Delay Ownership Heatmap</h3>
<p><b>Late Projects by Phase and Owner</b></p>
<ul>
  <li><b>Rows:</b> Milestone phases</li>
  <li><b>Columns:</b> Responsible roles (Commercial Manager, Construction Manager, Engineering Manager, PMO Lead, Stakeholder Manager, etc.)</li>
  <li><b>Colour intensity:</b> Higher concentration of delays</li>
</ul>
<p><i>Helps identify which teams or roles need focus.</i></p>

<h3>🧠 Drillthrough / Insight Panel</h3>
<img width="2153" height="1045" alt="Delay Drillthrough" src="https://github.com/user-attachments/assets/8e8e3b51-a341-4606-b9c7-969a62aaae0d" />
<p>When users click a data point, a detailed insight appears showing:</p>
<ul>
  <li><b>Top Delay Reason</b> (e.g., Permits/Consents)</li>
  <li><b>Milestone Name</b> (e.g., Planning Approval)</li>
  <li><b>Suggested actions</b> to address the issue</li>
  <li><b>Impacted projects list</b> including workstream, region, county, and slippage days</li>
</ul>
<p><i>Enables quick root-cause analysis and action planning.</i></p>

<h3>💡 What Users Can Do</h3>
<ul>
  <li>Identify which project phase drives delays</li>
  <li>Understand delay severity across workstreams</li>
  <li>See who owns the delays</li>
  <li>Perform root cause analysis using drillthrough</li>
  <li>Prioritise corrective actions</li>
</ul>

<hr/>

<h2>🟦 Page: Forecast and Controls</h2>
<h3>🎯 Purpose</h3>
<p>
  This page helps finance and delivery teams understand how spending is tracking against plan, whether projects are expected
  to overrun or underrun, and what the future cost outlook looks like.
</p>
<img width="1870" height="1044" alt="image" src="https://github.com/user-attachments/assets/7c948c92-9923-44a6-9b71-84772fdce7a9" />

<h3>🔎 Filters</h3>
<ul>
  <li><b>Region:</b> View financial performance by geography</li>
  <li><b>County:</b> Drill down to local level</li>
  <li><b>Workstream:</b> Focus on a specific program or type of work</li>
  <li><b>Year:</b> Analyse a specific financial year</li>
  <li><b>Quarter:</b> Compare performance for a selected quarter</li>
  <li><b>RAG Status:</b> Filter by project health</li>
  <li><b>Clear Filter:</b> Reset all filters</li>
</ul>
<p><i>Enables financial analysis at different levels of detail.</i></p>

<h3>📊 KPI Cards</h3>
<ul>
  <li><b>EAC variance vs baseline (%):</b> Shows whether the forecasted final cost is above or below the original budget</li>
  <li><b>Actual variance %:</b> Indicates how much actual spend differs from plan</li>
  <li><b>Remaining Forecast (€):</b> Amount still expected to be spent until project completion</li>
</ul>
<p><i>Gives a quick view of overall cost performance and outlook.</i></p>

<h3>📉 Visual 1: Forecast vs Baseline</h3>
<p><b>Baseline Budget vs EAC Variance</b></p>
<ul>
  <li>Baseline Budget</li>
  <li>EAC Variance (increase or decrease)</li>
  <li>Final EAC</li>
</ul>
<p><i>Helps answer: Are we expecting a cost overrun or savings?</i></p>

<h3>📉 Visual 2: Budget vs Actual (Selected Quarter)</h3>
<p><b>Actual Spend vs Planned Spend</b></p>
<ul>
  <li>Actual Spend</li>
  <li>Variance</li>
  <li>Planned Spend</li>
</ul>
<p><i>Helps answer: Did we spend more or less than planned this quarter?</i></p>

<h3>🧠 Interpretation Section</h3>
<ul>
  <li>Explains the difference between quarterly overspend vs overall forecast</li>
  <li>Explains how remaining forecast reflects future expected costs</li>
</ul>
<p><i>Helps non-finance users interpret the numbers correctly.</i></p>

<h3>💡 What Users Can Do</h3>
<ul>
  <li>Understand cost performance vs plan</li>
  <li>Identify potential overruns early</li>
  <li>Analyse quarterly spending behaviour</li>
  <li>Track remaining financial exposure</li>
  <li>Support budget control and forecasting decisions</li>
</ul>

