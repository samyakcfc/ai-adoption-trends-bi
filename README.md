AI Adoption Trends & Automation Risk Analysis (Power BI)
Project Overview

This Business Intelligence project analyzes AI adoption levels and automation risk across industries, job roles, and company sizes.

The purpose of this analysis is to evaluate how AI integration varies across business segments and how it relates to workforce automation exposure.

Business Question

How does AI adoption differ across industries and company sizes, and what is its relationship with automation risk?

Tools & Technologies

Power BI

DAX (Calculated Measures)

Data Modeling

Data Visualization

GitHub for Documentation

Dashboard Preview
Executive KPI Overview

This page provides a high-level summary of AI adoption and automation risk, including key performance indicators and filtering capabilities by industry and company size.

Industry-Level Analysis

This section compares AI adoption intensity and automation risk across industries, highlighting sector-level differences in AI maturity.

Company Size Impact

This page evaluates how AI adoption varies between small, medium, and large organizations, identifying patterns in enterprise-level AI integration.

Automation Risk vs AI Adoption

The scatter analysis visualizes the relationship between AI adoption and automation exposure, demonstrating that higher AI adoption does not always eliminate automation risk.

Key DAX Measures
% High Adoption =
DIVIDE(
    CALCULATE(COUNTROWS(Data), Data[AI_Adoption_Level] = "High"),
    COUNTROWS(Data)
)

Average Automation Risk =
AVERAGE(Data[Automation_Risk])
Key Insights

AI adoption is strongest in technology-focused industries.

Medium-sized companies demonstrate accelerated AI integration.

Automation risk varies significantly across job categories.

Increased AI adoption does not uniformly reduce workforce automation exposure.

Repository Structure

data/ → Raw dataset

dashboard/ → Power BI (.pbix) file

screenshots/ → Exported dashboard images

Author

Samyak Pratap Shah
MBA in Business Analytics
