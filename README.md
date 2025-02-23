# 🎓 University Finance Power BI Dashboard

## 📌 Project Overview
This **University Finance Dashboard** provides an interactive visualization of financial transactions, cash flow trends, and expenditure breakdown across different departments, programs, and funding sources. It enables university administrators and financial analysts to track **incoming receipts, outgoing payments**, and overall budget utilization efficiently.

## 📊 Key Features & Insights
- **Cash Flow Overview**: Incoming and outgoing transactions categorized by different financial sub-systems.
- **Department-Wise Expenditure Analysis**: Breakdown of fund utilization across university departments.
- **Top Sponsors & Funding Sources**: Identifies major research sponsors and financial contributors.
- **Vendor Performance**: Tracks payments to vendors and receipts from suppliers.
- **Trend Analysis**: Shows financial activities over different fiscal months & years.

## 🛠 Tools & Technologies Used
- **Power BI**: For interactive data visualization & analysis.
- **SQL**: For data extraction and transformation.
- **Excel**: For preprocessing financial data.


## 📂 Dataset Overview
The dataset consists of **financial transactions recorded over multiple fiscal years**. Below are some of the key columns in the dataset:

| Column Name             | Description |
|-------------------------|-------------|
| **Jrnl Date**            | Journal entry date of the transaction |
| **Fiscal Year**          | Year in which the transaction occurred |
| **Accounting Period**    | Monthly accounting period for tracking cash flow |
| **Sub-System Source**    | Financial sub-system category (e.g., AP, GL, TMS) |
| **Journal ID**          | Unique ID for each financial transaction |
| **Transaction Detail**   | Detailed transaction description |
| **Fund Code**           | Unique fund identifier |
| **Fund Descr**         | Fund name/description (e.g., "Research Grants", "Academic Funds") |
| **Project Code**       | Unique code assigned to university projects |
| **Project Title**      | Title of the funded project |
| **Dept ID**            | Department identifier for the transaction |
| **DeptID Desc**       | Description of the department (e.g., Science, Arts) |
| **Award ID**          | Unique award identifier (if applicable) |
| **Sponsor**          | Funding source (e.g., NSF, NASA, US Dept. of Education) |
| **Account Code**       | Finance ledger account code |
| **Outgoing Payments**  | Amount spent by the university |
| **Incoming Receipts**  | Funds received from grants, sponsors, or tuition |

---

## 📷 Dashboard Screenshots

### **1️⃣ Cash Flow Overview**
![Dashboard Overview](Images/dashboard_overview.png)

### **2️⃣ Detailed Cash Flow Insights**
![Detailed Cash Flow](Images/detailed_cash_flow.png)

### **3️⃣ Cash Flow by Sources & Sponsors**
![Sources and Sponsors](Images/cash_flow_sources.png)

---

## 📊 **Key Business Insights from the Dashboard**
- **Highest Transactions in AP Sub-System**: Most payments are processed through **Accounts Payable (AP)**.
- **Research Funding Dominates**: The **"Individual or Project Research"** program accounts for **75.54% of outgoing payments** and **93.04% of incoming receipts**.
- **Top Sponsor - NSF (National Science Foundation)**: NSF funds the highest portion of university projects (~ **0.72M**).
- **Seasonal Trends in Cash Flow**: A **spike in payments occurs in August**, likely due to budget allocations before the new academic year.
- **Vendor Performance Monitoring**: The **top 5 vendors by payments include Citrus North Hospitality LLC, Dell Marketing LP, and The Ohio State University**.

---

## 🔍 **How to Use This Project**
1. **Download the `.pbix` file** and open it in Power BI Desktop.
2. Connect your dataset (`university_finance_data.csv`) if available.
3. Explore **interactive filters** to analyze specific departments, sponsors, and financial years.
4. Modify **Power Query transformations** or **DAX measures** as needed.

---




