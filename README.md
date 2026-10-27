# Insurance Analytics Dashboard - SQL | Power BI | Tableau | Excel

Analyzed insurance domain data to find payment failures and claim trends. Built for Data Analyst portfolio - Pune.

## 📊 Project Overview
- **Domain:** Insurance (Customers, Policies, Claims, Payments, Renewals)
- **Database:** MySQL - 5 Tables, 25,000+ Records
- **Tools:** MySQL, Advanced Excel, Power BI (DAX), Tableau
- **Key KPI:** Analyzed ₹25.1 Cr Total Claims, Found 49.7% Payment Failures

## 🗄️ Database Schema
- Customers (CustomerID, Name, Region, Income)
- Policies (PolicyID, CustomerID, Premium, PolicyType)
- Claims (ClaimID, PolicyID, ClaimAmount, ClaimStatus)
- Payments (PaymentID, ClaimID, PaymentStatus, FailureReason)
- Renewals (RenewalID, PolicyID, RenewalStatus)

## 🔍 SQL - 21 Queries Covered
- JOINs: Customer-Policy-Claim mapping
- CTE: Monthly claim trend
- Window Function: LAG() for Renewal gap analysis
- Aggregation: Region-wise failure rate, Policy-type wise claims
- Case Study: Why 49.7% payments failed?

## 📈 Dashboards
**Excel:** 6 Charts, Pivot Table, Slicers for Policy Type & Region
**Power BI:** DAX Measures - Total Claims, Avg Claim, Failure %, YOY
**Tableau:** 12 Sheets, Story for Management - Claim Approval Bottleneck

## 📁 Files in this Repo
- `/sql/` - All SQL queries
- `/excel/` - Excel dashboard
- `/powerbi/` - Power BI file + screenshots
- `/ppt/` - Final presentation

## 👨‍💻 Author
**Aditya Bhoyar** - Data Analyst | Pune
- Skills: SQL, MySQL, Advanced Excel, Power BI, Tableau, Python
- LinkedIn:www.linkedin.com/in/aditya-bhoyar-252a76268
- Email:adityabhoyar160@gmail.com

## 🚀 How to Use
1. Import SQL schema
2. Run queries in MySQL Workbench
3. Open PBIX in Power BI Desktop
