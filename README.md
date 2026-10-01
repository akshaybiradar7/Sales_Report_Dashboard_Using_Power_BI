# Sales_Report_Dashboard(Using_Power_BI)

This repository contains a comprehensive Power BI dashboard designed for data visualization and business intelligence. The project utilizes a structured internal data model and spans multiple report pages containing distinct visual elements to facilitate data-driven decision-making. 

---

# 🗂️ Project Structure

```text
├── DiagramLayout                                 # Data model diagram relationships layout
├── Settings                                      # Workbook and model configuration
├── Metadata                                      # Report-level metadata
├── DataModel                                     # Tabular data model and DAX schema
├── SecurityBindings                              # Security and role assignments
├── Report/
│   ├── definition/
│   │   ├── sales_report.xlsx                           # Core report-level properties and settings
│   │   ├── pages/                                # Multi-page visual layout definitions
│   │   │   ├── pages.json                        # Report page order and metadata
│   │   │   └── <page-id>/                        # Individual dashboard page definitions & visuals
│   │   └── version.json                          # Report schema versioning
│   ├── LinguisticSchema                          # Q&A / Natural Language schema
│   └── StaticResources/
│       └── SharedResources/
│           └── BaseThemes/
│               └── Fluent2-CY26SU08.json          # Fluent 2 custom report theme
```
---

## Technical Architecture
Based on the file structure of the .pbix report, this project features:

* **Data Modeling:** Contains a defined DataModel and LinguisticSchema for optimized data relationships, calculations, and natural language Q&A capabilities. 

* **Security:** Incorporates SecurityBindings to manage data access, potentially utilizing Row-Level Security (RLS). 

* **Theming:** Utilizes the Fluent2-CY26SU08 base theme for consistent, professional visual design across all elements. 

* **Report Structure:** Features multiple dedicated report pages (including internally defined pages such as 846a71f1e636d00a4908 and 19a9c1cec232d2e6a48c), each hosting an array of custom visual JSON definitions. 

## Installation & Usage
1.	Clone this repository to your local machine:

**Bash**
git clone https://github.com/akshaybiradar7/Sales_Report_Dashboard(Using_Power_BI)

2.	Ensure you have the latest version of Microsoft Power BI Desktop installed.

3.	Open the .pbix file located in the repository root.

4.	If the data is not fully imported, click Refresh on the Home ribbon and provide the necessary data source credentials to load the latest dataset.

## Dashboard Features
* **Interactive Visualizations:** Features complex diagram layouts and multiple visuals per page with cross-filtering enabled. 

* **Metadata Integration:** Embedded metadata handling and settings configurations for automated reporting workflows. 

* **Custom Definitions:** Employs precise layout and visual definitions via static resources to maintain dashboard integrity. 

## Requirements
•	Power BI Desktop (Windows)

•	Data source from Excel sheet.

## Contributing
Contributions are welcome. Please open an issue to discuss proposed changes or submit a Pull Request.

