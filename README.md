# Telecom Call Center Performance Dashboard

## Project Overview
An end-to-end operational analytics dashboard built in Power BI to analyze 
call center performance for a telecom company across 12 months (Jan–Dec 2025).
The dashboard helps operations managers identify SLA breaches, CSAT gaps, 
agent underperformance, and systemic training issues.

## Business Problem
The call center was facing declining CSAT scores, high SLA breach rates, and 
no centralized visibility into agent-level performance. Management needed a 
single reporting layer to make data-driven decisions on staffing, training, 
and operations.

## Dashboard Pages
- **Page 1 — Operations Overview:** Monthly CSAT vs target, SLA breach trends, 
call volume by day and channel, issue category breakdown, escalation and 
abandonment by shift
- **Page 2 — Agent Performance:** Agent KPI table with conditional formatting, 
CSAT ranking, team comparison, handle time vs CSAT correlation, tenure vs 
performance analysis, agent rating distribution

## Key Insights
- SLA breach rate was consistently 2–3x above the 0.08 target throughout 2025, 
peaking in mid-year, indicating a systemic handle time management issue
- All 20 agents scored below the CSAT target of 4.20, suggesting a 
center-wide training gap rather than individual performance problems
- Team Delta recorded the lowest SLA breach rate at 0.19, making it the 
best performing team despite similar CSAT scores across all teams
- No significant correlation found between agent tenure and CSAT score, 
meaning experience alone does not predict performance
- Monday recorded the highest call volume, suggesting staffing should be 
optimized for start-of-week demand spikes
- Complaint Escalation was the highest volume issue category, indicating 
first-call resolution needs improvement

## Tools and Technologies
- Power BI Desktop (May 2026)
- Microsoft Excel with Power Query
- DAX (Data Analysis Expressions)
- Data Modeling — Star Schema

## Data Model
- **Fact Table:** Calls (6,000 rows, 14 columns)
- **Dimension Tables:** Agents, Issue Categories, Targets
- **Relationships:** Many-to-one from Calls to all three dimension tables

## DAX Measures Created
- Total Calls, Abandoned Calls, Abandonment Rate
- Resolved Calls, Resolution Rate
- SLA Breached Calls, SLA Breach Rate
- Avg Handle Time, Avg CSAT
- Escalated Calls, Escalation Rate
- Target CSAT, Target SLA Breach Rate, Target AHT
- CSAT vs Target variance, SLA Breach vs Target variance
- Agent CSAT Rating, Top Performer Score

## Dataset
Synthetic dataset built in Excel representing realistic telecom call center 
operations. Includes 6,000 call records across 20 agents, 4 teams, 
10 issue categories, and 3 shifts over 12 months.

## Skills Demonstrated
- End-to-end dashboard design from raw data to final visual
- Star schema data modeling in Power BI
- Advanced DAX measure creation
- Conditional formatting for performance signaling
- Drill-through functionality for agent-level analysis
- Business insight extraction from operational data

## Author
**Sarabdeep Singh Makhija**  
Data Analyst | Power BI | Excel | SQL | Python  
[LinkedIn](https://www.linkedin.com/in/sarabdeepmakhija/)
