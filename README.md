# 📊 Superstore Sales & Profit Dashboard

<p align="center">

<img src="https://img.shields.io/badge/POWER%20BI-DASHBOARD-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/POWER%20QUERY-TRANSFORMATION-CC0000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DATA%20ANALYTICS-PROJECT-374151?style=for-the-badge"/>
<img src="https://img.shields.io/badge/STATUS-COMPLETED-2E7D32?style=for-the-badge"/>

</p>

<p align="center">

### 🚀 An Interactive Business Intelligence Dashboard Built with Power BI

**Transforming Superstore data into clear, interactive and meaningful business insights.**

</p>

---
# 🎥 Project Demonstration

A complete walkthrough of the Power BI project is available below.

### ▶️ Watch the Project

https://drive.google.com/file/d/1mVpOO4KFwHFW8V0FeW3TjgaIKH7ttLSM/view?usp=sharing

The demonstration covers:

📥 Data Import
🔄 Power Query
🧹 Data Cleaning
🔢 Data Types
💳 KPI Cards
📊 Charts
🎛️ Slicers
🚚 Page Filters
🔄 Visual Interactions
📋 Order Details
🎨 Final Dashboard

---

## 📌 About the Project

The **Superstore Sales & Profit Dashboard** is a Power BI project created using the **Sample Superstore dataset**.

In this project, I worked on the data from the beginning — starting with **data preparation in Power Query** and ending with a **fully interactive Power BI dashboard**.

The dashboard focuses on:

💰 **Sales**
📈 **Profit**
📦 **Quantity**
🏷️ **Discount**
🌎 **Regions**
🗂️ **Categories & Sub-Categories**
📋 **Order Details**

---

## 🛠️ Tools & Technologies

| 🧰 Tool                 | 🎯 Purpose                       |
| ----------------------- | -------------------------------- |
| 📊 **Power BI Desktop** | Dashboard and report creation    |
| 🔄 **Power Query**      | Data cleaning and transformation |
| 📁 **CSV Dataset**      | Source data                      |
| 🎨 **Power BI Theme**   | Dashboard formatting and styling |

---

# 🔄 Data Preparation with Power Query

Before creating the dashboard, I prepared and explored the dataset using **Power Query Editor**.

### 🔍 Data Exploration

I used Power Query features such as:

* 📊 **Column Quality**
* 📈 **Column Distribution**
* 🔎 **Column Profile**
* 📝 **Applied Steps**
* ⚙️ **Formula Bar**

This helped me understand the data before using it for visualization.

---

### ✏️ Column Renaming

I renamed columns where required to make the dataset cleaner and easier to understand.

**Example:**

```text
Sub-Category → Sub Category
```

---

### 🔢 Data Type Conversion

I assigned suitable data types to important columns.

| 📌 Column  | 🔢 Data Type    |
| ---------- | --------------- |
| Order Date | 📅 Date         |
| Sales      | 💰 Decimal      |
| Quantity   | 🔢 Whole Number |
| Discount   | 🔢 Decimal      |
| Profit     | 💰 Decimal      |

This ensures that the fields work correctly during analysis and visualization.

---

### 🧹 Data Cleaning

I checked the dataset for data-quality issues and prepared important fields before building the report.

The data was reviewed for blank/null values and unnecessary information.

---

### 🎯 Row Filtering

I applied the required filters to the dataset so that the report contains the required records for analysis.

---

### ✂️ Split Column

I used the **Split Column** feature with a delimiter to separate information from the **Order ID** field.

This helped prepare the field according to the project requirements.

---

### 🗑️ Removing Unnecessary Columns

Columns that were not required for the analysis were removed.

For example:

```text
Row ID
Country
Postal Code
```

This keeps the dataset focused on the information required for the dashboard.

---

# 📊 Dashboard Development

After preparing the dataset, I created the main **Sales Performance Dashboard** in Power BI.

The dashboard combines **KPIs, charts, slicers and filters** so users can explore the data interactively.

---

# 💳 KPI Cards

I created **4 important KPI cards** for a quick overview of business performance.

### 💰 Total Sales

Shows the overall sales value from the dataset.

### 📈 Total Profit

Shows the overall profit generated.

### 📦 Total Quantity

Displays the total quantity represented in the dataset.

### 🏷️ Average Discount

Shows the average discount applied across the data.

These KPI cards provide a quick summary before going into detailed analysis.

---

# 📈 Sales Analysis

## 🗂️ Sales by Category

I created a **Clustered Bar Chart** to compare sales across different product categories.

This makes category-level sales performance easy to compare visually.

---

## 🌎 Profit by Region

I created another **Clustered Bar Chart** to compare profit across different regions.

This helps users understand how profit varies between regions.

---

# 🎛️ Interactive Slicers

To make the dashboard interactive, I added slicers.

### 🌎 Region Slicer

The **Region Slicer** allows users to select a particular region and analyze the dashboard based on that selection.

### 🗂️ Category Slicer

The **Category Slicer** allows users to focus the analysis on a selected product category.

These slicers make the dashboard more dynamic and user-friendly.

---

# 🚚 Shipping Mode Filter

I added a **Page-Level Filter** for Shipping Mode.

The available selections include:

* 🚚 **Standard Class**
* 🚚 **Second Class**

This allows the report to be viewed based on the selected shipping mode.

---

# 🔄 Visual Interactions

I configured **Edit Interactions** in Power BI to control how different visuals respond to user selections.

For example:

**Category Selection → Charts + KPI Cards**

**Region Selection → Related Dashboard Visuals**

This makes the report interactive instead of simply displaying static charts.

---

# 📋 Order Details

I created a separate **Order Details** page to provide a more detailed view of the data.

While the main dashboard focuses on summarized information, this page allows users to explore individual order-level records.

### 🔎 Information included

🆔 **Order ID**
👤 **Customer Name**
🗂️ **Category**
📦 **Quantity**
💰 **Sales**
📈 **Profit**

This creates a detailed view alongside the main dashboard analysis.

---

# 🗂️ Sub-Category Analysis

A dedicated visual is included for **Sub-Category analysis**.

This provides a more detailed level of product analysis beyond the main Category view.

The analysis can therefore move from:

**🗂️ Category → 🔎 Sub-Category → 📋 Order Details**

---

# 🎨 Dashboard Design

The dashboard was designed with a clean and professional **white/light background**.

The visual theme uses:

⚪ **White / Light Canvas**
🟥 **Red Accent Elements**
⚫ **Charcoal / Dark Elements**

### ✨ Design Focus

📐 Clean alignment
📊 Clear visual hierarchy
💳 Highlighted KPI cards
🏷️ Meaningful titles
🎛️ Easy-to-use slicers
📏 Consistent spacing
🖥️ 16:9 report layout

The goal was to keep the dashboard **simple, readable and business-focused**.

---

# 📸 Dashboard Preview

## 🏠 Sales Performance Dashboard

<img width="960" height="542" alt="image" src="https://github.com/user-attachments/assets/a407216b-1646-41d0-af95-560737bac306" />

<p align="center">


</p>

---

## 📋 Order Details

<img width="960" height="538" alt="image" src="https://github.com/user-attachments/assets/db4fc117-803a-4f29-ba6e-839b3d57387c" />


<p align="center">


</p>

---


# 🧠 Skills Demonstrated

### 📊 Power BI

`Dashboard Design` · `KPI Cards` · `Bar Charts` · `Tables` · `Slicers` · `Filters` · `Visual Interactions`

### 🔄 Power Query

`Data Exploration` · `Data Cleaning` · `Data Types` · `Column Renaming` · `Row Filtering` · `Column Splitting` · `Column Removal`

### 📈 Data Analysis

`Sales Analysis` · `Profit Analysis` · `Regional Analysis` · `Category Analysis` · `Sub-Category Analysis` · `Quantity Analysis` · `Discount Analysis`

---

# 🌟 Project Highlights

### 💰 KPI-Based Analysis

Important business metrics are presented through dedicated KPI cards for quick understanding.

### 📊 Visual Business Analysis

Sales and profit are analyzed through category and regional visualizations.

### 🎛️ Interactive Reporting

Slicers and filters allow users to explore different parts of the dataset dynamically.

### 🔎 Detailed Analysis

The Order Details page provides a deeper view of individual records.

### 🎨 Professional Dashboard

A clean white dashboard with red and charcoal accents keeps the report visually consistent and easy to read.

---

# 💡 What I Learned

Through this project, I gained practical experience in taking a raw dataset and converting it into an interactive Power BI report.

I practiced:

🔄 Preparing data with Power Query
📊 Creating business KPIs
📈 Selecting suitable visualizations
🎛️ Adding interactive filters
🔄 Managing visual interactions
🎨 Designing a professional dashboard
📋 Creating detailed report pages

---

# 👩‍💻 Author

## **Simran Gohel**

📊 **Data Analytics**
📈 **Power BI**
🗄️ **SQL**
📗 **Excel**
🐍 **Python**

> **Turning data into meaningful insights through practical analytics projects.**

---

<p align="center">

### ⭐ Superstore Sales & Profit Dashboard

**Power BI • Power Query • Data Analytics**

<br>

🚀 **From Data → Visualization → Insights**

</p>
