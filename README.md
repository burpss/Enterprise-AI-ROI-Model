# Enterprise-AI-ROI-Model
Financial model and ETL pipeline for an Enterprise AI implementation
Enterprise AI ROI & Transformation Model
Project Overview
This project provides a comprehensive financial model, data transformation pipeline, and executive dashboard to evaluate the capital allocation for an Enterprise AI integration. It addresses the core business problem of quantifying software ROI by mapping upfront implementation costs against projected long-term efficiency savings.

The Tech Stack
Financial Logic: Microsoft Excel

Data Architecture (ETL): Power Query

Business Intelligence: Tableau

Project Architecture
1. The Financial Engine (Excel)
Built a dynamic, multi-variable financial model to calculate monthly burn rates and returns. Variables include:

Upfront implementation and consulting fees.

Recurring monthly SaaS license expenditures.

Projected employee time-savings and hourly wage offsets.

Staggered user adoption curves to reflect realistic rollout timelines.

2. The Data Pipeline (Power Query)
Engineered an automated Extract, Transform, Load (ETL) pipeline to convert the wide-format financial spreadsheet into a normalized, machine-readable database.

Executed Unpivot commands to collapse 36 months of horizontal data into a clean, vertical 3-column architecture (Line Item, Month, Amount).

Tagged and structured the final output to strictly separate organizational "Costs" from "Benefits".

3. The Executive Dashboard (Tableau)
Connected the transformed dataset to Tableau to build a C-Suite presentation layer.

Engineered custom calculated fields (e.g., Net Cash) to automatically process costs as negative outflows.

Visualized the 3-Year Breakeven Curve using continuous running totals to pinpoint the exact month of profitability.

Built a granular Monthly Cash Flow chart utilizing boolean color-coding to monitor operational runway.
