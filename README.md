# StockFlow – Inventory Management System (Assessment)

## Candidate
**Name:** Dhanashree  

---

## Overview
This document contains my solutions for the **StockFlow B2B Inventory Management System** take-home assessment.  
The assessment focuses on code review, database design, and API design using incomplete requirements.

The goal of this submission is to demonstrate:
- Logical problem-solving
- Understanding of backend and database concepts
- Ability to work with unclear requirements
- Clear and structured communication

---

## Contents
- **Part 1:** Code Review & Debugging  
- **Part 2:** Database Design  
- **Part 3:** Low Stock Alerts API  
- **Assumptions & Questions**

---

## Part 1: Code Review & Debugging
- Identified technical and business-logic issues in the provided API code
- Explained real-world production impact of each issue
- Suggested high-level fixes and best practices

Key focus areas:
- Product and warehouse relationship
- SKU uniqueness
- Input validation
- Transaction safety
- Price precision handling

---

## Part 2: Database Design
- Designed a relational database schema to support:
  - Multiple companies and warehouses
  - Products stored in multiple warehouses
  - Inventory tracking and history
  - Supplier relationships
  - Product bundles
- Identified missing requirements and listed questions for the product team
- Explained design decisions and trade-offs

---

## Part 3: Low Stock Alerts API
- Designed an API endpoint to return low-stock alerts for a company
- Considered:
  - Multiple warehouses
  - Recent sales activity
  - Product-specific thresholds
  - Supplier information for reordering
- Provided step-by-step API logic and handled edge cases

---

## Assumptions
- Recent sales activity refers to the last 30 days
- Low-stock thresholds vary by product type
- Each product has one primary supplier
- Prices are stored using decimal values
- Inventory and sales data are reliable and up to date

---

## Notes
- This submission focuses on **design, reasoning, and clarity** rather than full runnable code
- Some decisions were made based on assumptions due to incomplete requirements
- Questions and assumptions are explicitly documented where clarification is needed

---

## Final Remark
This assessment reflects my current understanding and learning approach as a student, with an emphasis on clear thinking, maintainability, and real-world applicability.

Thank you for reviewing my submission.
