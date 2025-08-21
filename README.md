Power BI Dashboard: Financial & Strategic Insights into India’s Defence Sector (2019–2024)
Project Overview

India’s defence sector is rapidly evolving with both government and private players contributing to production, exports, and innovation. To better understand industry trends, I designed and developed a Power BI dashboard that provides a comprehensive 360° analysis of seven major defence companies:

HAL (Hindustan Aeronautics Ltd)

BEL (Bharat Electronics Ltd)

BDL (Bharat Dynamics Ltd)

Cochin Shipyard

Solar Industries

Paras Defence & Space Technologies

Sika Interplant Systems

The dashboard covers financial stability, profitability & valuation, and cash-flow analysis, enabling quick comparisons and insights for stakeholders, analysts, and decision-makers.

 Data & Technology Stack

 Data Source: SharePoint repositories (financial + operational data).
 ETL & Storage: Connected via SharePoint connectors, structured & modeled within Power BI.
 Transformations: Power Query for data cleaning & shaping.
 Modeling & Analytics: Extensive use of DAX functions, field parameters, and dynamic calculations.
 User Experience: Interactive navigation built using bookmarks, slicers, and custom page navigation.

This ensured the dashboard is not just a reporting tool, but a decision-support platform.

Key Insights from the Dashboard
Financial Stability
<img width="900" height="596" alt="image" src="https://github.com/user-attachments/assets/153ba938-53af-4981-b498-e28265335ab8" />
BEL, HAL, and Cochin Shipyard emerged as the most stable players based on weighted capital efficiency and Z-Score.

Dividend payouts and EPS trends highlight consistent shareholder returns by HAL and BEL.

Profitability & Valuation
<img width="900" height="596" alt="image" src="https://github.com/user-attachments/assets/6189744b-de9f-41a1-9cac-4e14845b7b72" />


Solar Industries recorded the highest P/E ratio, reflecting strong investor confidence.

EPS CAGR (2019–24) shows HAL and BEL as leaders in earnings growth.

ROCE and ROA trends suggest HAL is outperforming peers in capital efficiency.

Cash-Flow & Production Trends
<img width="900" height="596" alt="image" src="https://github.com/user-attachments/assets/a47e4cfb-442d-4cb3-a3e3-325607cf7f9b" />


HAL and BEL dominate in operating cash flows, while private sector firms like Solar show strong growth momentum.

Production CAGR highlights shifts between government-led and private sector defence output.

Export contracts (2020–24) increased significantly, indicating India’s growing global defence footprint.

Schema Design

<img width="900" height="365" alt="image" src="https://github.com/user-attachments/assets/598cfdfe-97e2-4759-91a6-fbe5f553c1bd" />


The dashboard follows a star schema to ensure optimized reporting performance and scalability.

Fact Tables:

Balance Sheet Masterfile

Cash Flow Masterfile

P&L (Profit & Loss)

Operating Activity

Defence Import Data

Defence Production

Dimension Tables:

Company Data (CompanyID, CompanyName, Sector, Market Cap, Industry classification)

Fiscal Year Key (Date/Year dimension for time intelligence)

GOC Weight Table (weighted capital efficiency)

Share Data (Market capitalization, EPS, P/E, ROE)

This schema allows one-to-many relationships between dimension tables and fact tables, supporting efficient time-based, company-based, and financial metric-based analysis.

Key Power BI Features Used

DAX Functions (for advanced financial analysis):

CALCULATE() → Context-based calculations for ratios like ROE, ROA, EPS CAGR.

DIVIDE() → Safe division for financial ratios (EPS, P/E, ROCE).

RANKX() → Ranking companies by financial stability, EPS, ROA, ROCE.

TOTALYTD() / DATESYTD() → Year-to-date EPS and dividend payout comparisons.

AVERAGEX() → Rolling average for growth trends (EPS CAGR, Production CAGR).

Z-SCORE calculation → Standardized measure of company stability.

Field Parameters (for dynamic interactivity):

Used to switch between financial KPIs (EPS, P/E, ROCE, ROA, Z-Score) dynamically.

Enabled comparison views across companies with a single slicer instead of multiple visuals.

Added flexibility to toggle between time-period analysis (2019–24) and metric analysis.

Bookmarks & Navigation:

Implemented bookmarks for page navigation (Financial Stability, Profitability & Valuation, Cash Flow & Production).

Created toggle states to switch between detailed analysis and high-level summary views.

Enhanced user experience with interactive storytelling and drill-through options.

Outcome & Impact

The dashboard provides:

Analysts → A structured way to evaluate defence stocks.

Decision-makers → Insights into financial health and growth opportunities.

Industry professionals → Clear trends across 2019–2024, supporting strategic planning.

This project demonstrates the power of data storytelling with Power BI—turning raw financials into actionable intelligence.
