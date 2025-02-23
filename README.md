# 🎓 University Finance Power BI Dashboard

## 📌 Project Overview
This **University Finance Dashboard** provides an interactive visualization of financial transactions, cash flow trends, and expenditure breakdown across different departments, programs, and funding sources. It enables university administrators and financial analysts to track **incoming receipts, outgoing payments**, and overall budget utilization efficiently.
## 📷 Dashboard Overview

### **1️⃣ Cash Flow Overview**
![Dashboard Overview](https://github.com/KeshavaYada/University-Finance-Power-BI-Dashboard/blob/main/Cash%20flow%20overview.png)

### **2️⃣ Detailed Cash Flow Insights**
![Detailed Cash Flow](https://github.com/KeshavaYada/University-Finance-Power-BI-Dashboard/blob/main/Detailed%20Cash%20Flow.png)

### **3️⃣ Cash Flow by Sources & Sponsors**
![Sources and Sponsors](https://github.com/KeshavaYada/University-Finance-Power-BI-Dashboard/blob/main/Cashflow%20by%20Sources%20%26%20Sponsors.png)

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

## 🔍 Summary Insights
- The **AP system** processes the highest number of transactions.
- The **General Ledger (GL)** system handles the largest financial volume.
- **Research Programs** receive the majority of funding and expenditures.
- **National Science Foundation (NSF)** and **US Department of Defense** are key sponsors.
- **Top departments, vendors, and spending patterns** are visualized for financial analysis.
- **Fiscal trends** highlight peak spending and funding cycles.

---

## 🛠 Advanced Features Used in the Dashboard

### **🎚 1. Dynamic Filters & Slicers**
   - **Multi-Level Slicers**: Users can filter by **Sub-System Source, Department, Fiscal Quarter, Fund Description, Sponsor, and Vendor**.
   - **Cascading Filters**: Filters dynamically update based on other selections, ensuring relevant data visualization.
   - **Date Slicer (Fiscal Year & Quarter)**: Allows easy navigation between different financial periods.

### **🎨 2. Dynamic Color Grading & Conditional Formatting**
   - **Color-coded Financial Metrics**:
     - Incoming Receipts vs. Outgoing Payments are **color-coded** for easy differentiation.
     - High cash flow values are highlighted in **blue**, while lower values fade to **lighter shades**.
   - **Heatmap-style Data Tables**:
     - Program-level cash flow data is **color-graded dynamically**.
     - **Higher expenditures are darker, while lower ones are lighter**, making key financial insights easily visible.

### **📈 3. Trends with Drill-Down & Drill-Up Features**
   - **Drill-Down for Fiscal Trends**:
     - Users can **drill down from yearly trends to quarterly and monthly trends**.
     - Clicking on a **fiscal year** in the cash flow trend chart **breaks down into quarters**.
     - Further drill-down shows **month-over-month trends**.
   - **Drill-Up for Aggregate Analysis**:
     - Users can **move up from detailed month-level data to a yearly summary** for high-level analysis.


### **🔄 4. Dynamic Titles & KPI Cards**
   - **Auto-Updating Titles**: Dashboard titles **change dynamically** based on selected filters.
   - **Dynamic KPI Cards**:
     - Show **total incoming receipts and outgoing payments**.
     - **Real-time updates** based on selected fiscal periods.
   - **Adaptive Labeling**:
     - If a type of cash is selected, the title updates to reflect its **specific financial summary**.


### **🔄 6. Interactivity & Drill-Throughs**
   - **Drill-Through Pages**:
     - Clicking on a **department, fund, or vendor** provides **detailed insights**.
   - **Interactive Pie & Bar Charts**:
     - Clicking a segment of a **departmental spending chart filters all visuals** dynamically.
    
---

## 🔍 **How to Use This Project**
1. **Download the `.pbix` file** and open it in Power BI Desktop.
2. Connect  to dataset (`Comprehensive Finance data.xlsx`).
3. Explore **interactive filters** to analyze specific departments, sponsors, and financial years.
4. Modify **Power Query transformations** or **DAX measures** as needed.

---




