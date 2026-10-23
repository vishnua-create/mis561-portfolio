# mis561-portfolio

Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, Power BI through DataCamp, Adobe Express, and various AI tools. 

Advancing in Excel and Tableau Pt. 1 | Which product subcategory is the highest priority for our recovery plan? | https://public.tableau.com/app/profile/vishnu.akumalla/viz/AdvancinginExcelandTableauPt_1/ExploratoryDash | One thing I would change would be the formatting: right now the dashboard with the map and the scatter don't clearly display text. 

Advancing in Excel and Tableau Pt. 2 | Which single change to the FY2026 account service policy should Sales fund to stop losing money on low-revenue accounts? | https://public.tableau.com/app/profile/vishnu.akumalla/viz/AdvancinginExcelTableauPt_2/AccountPortfolioDashboard#1 | One thing I would change is marking the $4,000 threshold directly on the bar chart with a reference line, since that break point is the whole recommendation and right now the reader has to infer it from where the bars turn positive.

Introduction to Power BI | Completed on September 28, 2026. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/PowerBITrainingCertifications_17905794516940/PowerBIStory

Introduction to DAX in Power BI | Completed on October 04, 2026. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/PowerBITrainingCertifications_17905794516940/PowerBIStory
In Flex 4, I calculated net contribution per account by hand in a Pivot Table (SUM(Profit) minus the Cost to Serve for that account's tier, computed once for all 793 accounts in the Account Summary tab). I would build this as a measure, not a calculated column, because the Cost to Serve isn't a fixed property stored on each row. It depends on a lookup against the account's tier and the number has to re-aggregate correctly whenever someone filters by tier, region, or a revenue band rather than being computed once per account and left static. A measure also avoids storing a row-by-row value that silently goes stale if tier assignments or cost-to-serve rates change next year. For Marcus, this means he stops asking me to rerun the Pt. 2 analysis every time he wants to test a different cut. Now he can filter by region or rep himself and watch net contributions recalculate live in the meeting, instead of waiting on a new Pivot Table and a new Tableau publish each time the question changes. 

Data Visualization in Power BI | Completed on October 12, 2026. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/PowerBITrainingCertifications_17905794516940/PowerBIStory
Sarah, 
I'm ready to take on BI work at Southwest because I've now built the same kind of analysis three different ways and can tell you when each tool earns its place. In Flex 4, I calculated net contribution per account by hand in a PivotTable, subtracting each tier's cost-to-serve from account profit to find that low-revenue Inside Sales accounts were losing money despite looking healthy on revenue alone. In Power BI, that same logic becomes a DAX measure rather than a static column, so it recalculates live as Marcus filters by region or rep instead of waiting on a new PivotTable each time his question changes. From this course specifically, I'd rebuild my Flex 3 subcategory margin table as a conditionally formatted matrix, so the losing lines are visually unmissable to Anita without a separate chart competing for her attention. 
Here is how I would divide my labor: Excel for one-time investigation and ad hoc questions, Tableau when a single polished chart needs to carry a specific recommendation to a decision-maker in one meeting, and Power BI when the same report will be reopened and resliced repeatedly by someone who isn't an analyst. 
My gap is real: I've never published a report to the Power BI Service or maintained one that other people depend on and refresh independently of me. I'd close it by asking to own a small recurring Southwest report end-to-end, including the refresh schedule, so I learn what breaks after I've moved on to the next thing. 
Vishnu
Please note: AI was used to edit and formalize this note, while the content and thoughts are original. 

Advancing in Excel & Tableau - Pt. 3 (Card Portfolio Review - Contactless Readiness): Which non-contactless cards should Bear Down Bank replace early in one batch, how many are there, and what will it cost? If I did it again, I would add a view showing the fallback batch of cards with more than 12 months left (211 cards, $1,688), so Renee could see a smaller option side by side. 
https://public.tableau.com/app/profile/vishnu.akumalla/viz/CardPortfolioReview_17924780898620/ExploratoryDash

Advancing in Excel & Tableau - Pt. 4 (Card Growth Analysis - Wildcats Rewards Offer): Which group of Bear Down customers should receive the pilot mailing of the Wildcat Rewards card, based on where the most customers qualify under Credit Risk's guardrails?
https://public.tableau.com/app/profile/vishnu.akumalla/viz/CardGrowthAnalysis-WildcatRewardsOffer/ExploratoryDashboard
If I did it again, I would add a minimum-customers control to the state chart, so a viewer could see small, high-rate states like Colorado (13 of 23 customers) instead of my fixed 50-customer cutoff hiding them. 
