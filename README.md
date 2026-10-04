# mis561-portfolio

Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, Power BI through DataCamp, Adobe Express, and various AI tools. 

Advancing in Excel and Tableau Pt. 1 | Which product subcategory is the highest priority for our recovery plan? | https://public.tableau.com/app/profile/vishnu.akumalla/viz/AdvancinginExcelandTableauPt_1/ExploratoryDash | One thing I would change would be the formatting: right now the dashboard with the map and the scatter don't clearly display text. 

Advancing in Excel and Tableau Pt. 2 | Which single change to the FY2026 account service policy should Sales fund to stop losing money on low-revenue accounts? | https://public.tableau.com/app/profile/vishnu.akumalla/viz/AdvancinginExcelTableauPt_2/AccountPortfolioDashboard#1 | One thing I would change is marking the $4,000 threshold directly on the bar chart with a reference line, since that break point is the whole recommendation and right now the reader has to infer it from where the bars turn positive.

Introduction to Power BI | Completed on September 28, 2026. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/PowerBITrainingCertifications_17905794516940/PowerBIStory

Introduction to DAX in Power BI | Completed on October 04, 2026. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/PowerBITrainingCertifications_17905794516940/PowerBIStory
In Flex 4, I calculated net contribution per account by hand in a Pivot Table (SUM(Profit) minus the Cost to Serve for that account's tier, computed once for all 793 accounts in the Account Summary tab). I would build this as a measure, not a calculated column, because the Cost to Serve isn't a fixed property stored on each row. It depends on a lookup against the account's tier and the number has to re-aggregate correctly whenever someone filters by tier, region, or a revenue band rather than being computed once per account and left static. A measure also avoids storing a row-by-row value that silently goes stale if tier assignments or cost-to-serve rates change next year. For Marcus, this means he stops asking me to rerun the Pt. 2 analysis every time he wants to test a different cut. Now he can filter by region or rep himself and watch net contributions recalculate live in the meeting, instead of waiting on a new Pivot Table and a new Tableau publish each time the question changes. 
