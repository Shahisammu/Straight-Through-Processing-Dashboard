# Straight-Through-Processing-Dashboard
Purpose: Straight Through Processing (STP) Power BI dashboard is designed to automate manual reporting and deliver actionable insights, monitor operational efficiency, identify bottlenecks, and optimize underwriting and claims processes.

Tools & Technologies used: Power BI, Excel, SQL Server(In the original Dashboard), CoPilot

Data Source: Extracted sample data using prompt Engineering - CoPilot

Key Visuals:

Scorecards - Mainly classified into NOP (No. of policies), % of total NOPs, Check for validation (Note that as data is dummy False can be expected) 
Slicers - Slicers like KPI - Overall Fail & Single Fail, Rules, Date (Between), Channels, Zone, Annual Income Slabs, APE Bands, Education, Age Band, Income/APE, SA/APE, Risky Date of Birth, Marital Status, PT>PPT, Smoker Flag, Occupation Class, Sum Assured, Medical Category, Gender, Product Category, Month End Login, Occupation Category, IRSM Category 
Text Boxes - Text boxes are used to display visual headers & details like built & maintained by respective person.
Sample Logo - Replaced original company logo with a sample logo

Users: Risk Control Unit, Underwriting, Branch Operations & Claims department 

Company: Generali Central Life Insurance Company (Earlier known as Future Generali India Life Insurance Company)

Business Impact:
1. STP Rate Analysis: Visual breakdown of STP vs manual interventions across product lines, regions, and channels.
2. Exception Tracking: Drill-down views into cases requiring manual handling, categorized by rules & other KPI parameters.   Identification of which STP Rule can be eliminated based on performance.
3. Trend Monitoring: Time-series analysis of STP performance, highlighting improvements or regressions. Conditional formatting helps identify which data needs to be analyzed. 
4. Business Impact Metrics: Quantifies time saved, cost reduction, and throughput acceleration due to STP adoption. 
5. Dynamic Filtering: Interactive slicers such that if Overall Fail is selected in KPI slicer then no rules will be reflected as it is overall & if Single Fail is selected then a particular rule can be selected for analysis.

Screengrab: "https://github.com/user-attachments/assets/6a444d7d-c555-4fbd-a2df-0d6c2a270f78"
