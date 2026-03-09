# Project Overview
This project analyzes a realistic enterprise-grade dataset from a global B2B SaaS and Professional Services company, covering thousands of sales deals, customer accounts, rep activities, and pipeline stages across multiple regions and industries.
The goal is to build a report that functions as a daily operational tool, not a monthly summary. Sales managers need to see which deals need attention today, which reps are carrying the pipeline, and where forecast accuracy is at risk.
The final deliverable is a three-page interactive Power BI dashboard built for sales managers, account executives, and business leadership; incorporating ZoomCharts Drill Down visuals for deeper, faster data exploration.

---

# 🎯 Why This Project Matters
A €606M pipeline sounds healthy until you look inside it.
6,769 deals are flagged high risk. Deals sit idle for an average of 401 days before they're lost. And accounts with hundreds of logged activities have zero open opportunities attached to them signifying engagement without conversion.
This dashboard was built to answer the questions that keep sales leaders up at night:

- 🚨 Which deals are about to die and who owns them?
- 📉 Where exactly in the pipeline does momentum go to stall?
- 🏆 Which reps are genuinely performing, and which are just busy?

Because a pipeline report that only shows totals isn't a management tool. It's a comfort blanket.

---

## Business Questions
1. How do pipeline value and deal volume change over time?
2. Which industries and regions contribute most to pipeline value and revenue?
3. At what specific stages do deals tend to slow down or get stuck?
4. Which sales reps consistently manage the healthiest pipelines?
5. How does client engagement activity frequency impact deal success?
6. Which open deals are currently at high risk due to lack of activity?
7. What are the distinct seasonal patterns in deal closures and value?
8. How does average sales cycle length compare between SMB and Enterprise deals?
9. What is the current forecast accuracy based on pipeline stage probabilities?
10. Which specific products or services drive the highest win rates?

---

## Dataset
- Source: FP20 Data Challenge 35 - Feb - Mar 2026
- Business Type: Global B2B SaaS & Professional Services
- Region: Europe, North America, Asia-Pacific, Latin America
- Industries: Healthcare, Financial Services, Technology, Logistics, Retail & E-commerce, Education, Manufacturing.

---

## Tools and Technologies

| **Tool/Technique** | **Usage** |
|---------------|-------------|
| **PowerBI desktop** | Dashboard design, Report publishing |
| **ZoomCharts visual drilldown** | Interactive drill-through on pipeline and stage analysis charts |
| **DAX - Data analysis expression** | Win rate, high risk flag, idle days calculation, forecast accuracy, pipeline-to-revenue ratio |
| **Power Query** | Data cleaning, Data transformation |
| **Data Modelling** | Star schema linking deals, reps, companies, activities, and date dimensions |

---

## 💡 Key Insights
- €606M in pipeline but only €240M converted. A 60.21% win rate means nearly 40% of pipeline value is either stalling or dying.
- 6,769 deals are simultaneously open and high risk. Every single open deal is flagged at risk, which means the pipeline health issue is systemic, not isolated.
- Deals sit idle for an average of 401 days before being lost; nearly 14 months of inactivity before a deal is formally abandoned. This is a management and process failure, not just a rep performance issue.
- Negotiation and Closing stages bleed the most time, averaging 158 and 152 idle days respectively.
- Company 267 (Healthcare) has logged 715 activities with zero open opportunities. High-engagement accounts without attached deals represent a significant missed conversion opportunity hiding in plain sight.
Europe dominates pipeline and revenue while Latin America contributes the least. However, Asia-Pacific's pipeline-to-revenue gap warrants investigation as a potential growth or execution problem.

---

## 🔑 Key Takeaways
- The pipeline is large but fragile. €606M sounds strong until you realize 100% of open deals are high risk and the avg deal sits untouched for over a year.
- Stage friction is predictable and fixable. Negotiation and Closing aren't failing randomly, They failed systematically, which means a process intervention will have measurable impact.
- Top reps are massively outperforming the average. Isabelle Pereira's 73.08% win rate vs. the 60.21% average is a 13-point gap that should be studied and replicated, not ignored.
Cloud Migration and Security are the highest-conviction products at 64.51% and 61.57% win rates. These two products close more than they lose and should anchor sales conversations.
Engagement ≠ progress. Accounts with hundreds of logged activities and no open opportunities are a symptom of relationship management without commercial intent.
Forecast accuracy at 95.20% is the one clear bright spot. The business can predict what will close. The problem is not forecasting. It's execution.

---

## ✅ Strategic Recommendations
- Implement a 30-day inactivity trigger for all open deals. Any deal without activity in 30 days gets an automatic manager alert. The current average of 401 idle days is a process gap, not a rep gap and discouraging.
- Document and distribute Isabelle Pereira's pipeline methodology — a 73.08% win rate is not luck. Identifying what she does differently in Negotiation and Closing stages and turning it into a playbook can lift the entire team.
- Lead with Cloud Migration and Security in all new conversations. These products have the highest win rates and should be the entry point for new accounts, with other services introduced as expansions.
- Convert high-engagement, no-opportunity accounts immediately. Company 267 (715 activities), Company 295 (425 activities), and others represent warm relationships with no commercial structure. Assigning formal opportunities to these accounts is a near-zero-effort revenue action.
- Build stage-specific exit criteria for Negotiation and Closing. Deals stalling 150+ days at these stages need defined conditions to either advance or be formally disqualified.
- Investigate Asia-Pacific's pipeline-to-revenue gap. If pipeline is building and revenue is not converting at the same rate as Europe, then there is either a product-market fit issue, an execution gap, or a data quality problem that needs resolution.

---

## Dashboard Visualization  

[**View pbix, pdf snapshot excel and docs file**](https://drive.google.com/drive/folders/1h0o__4EHKsW3FI8TjsdjbTRpp5tZXQKU?usp=drive_link)

---

## 🤝 Connect & Feedback
If you found this project useful or have suggestions, feel free to:

- ⭐ Star this repository
- 🐛 Open an issue for feedback or questions
- 🔗 Connect on LinkedIn — [Opeyemi Ayodeji](https://www.linkedin.com/in/opeyemi-ayodeji-86a696b0/)
