# Manual Testing Framework - NopCommerce

[![Manual Testing](https://img.shields.io/badge/Manual%20Testing-Expert-blue)](https://en.wikipedia.org/wiki/Manual_testing)
[![Methodology Agile](https://img.shields.io/badge/Methodology-Agile-green)](https://agilemanifesto.org/)
[![Defect Tracking](https://img.shields.io/badge/Defects-Jira%2FExcel-red)](https://www.atlassian.com/software/jira)
[![Documentation](https://img.shields.io/badge/Docs-100%25%20Coverage-orange)](https://github.com/YashDesai)

**A Production-Grade Manual Testing Framework designed to simulate real-world QA cycles.**

This repository contains the complete manual testing documentation for the **NopCommerce Demo Store** (`demo.nopcommerce.com`). It is structured to follow industry-standard QA processes, moving beyond simple "ad-hoc" testing to a full **STLC (Software Testing Life Cycle)** implementation.

---

## 🎯 Project Objectives

In a real-world QA environment, testing is more than just finding bugs—it's about **traceability**, **coverage**, and **risk mitigation**. This project demonstrates:

1.  **End-to-End Test Management**: From Requirement Analysis (SRS) to Test Execution and Reporting.
2.  **Risk-Based Testing**: Prioritizing critical flows like *Checkout* and *Payment Gateway* integrations.
3.  **Defect Lifecycle Management**: documenting bugs with reproducible steps, severity, and priority.
4.  **Professional Documentation**: delivering artifacts that are audit-ready and stakeholder-friendly.

---

## 📊 Technical Benchmarks & Results

This project was executed against the NopCommerce v4.60 demo environment. The following metrics were captured during the testing cycle:

| Metric | Count / Status | Description |
| :--- | :--- | :--- |
| **Test Scenarios** | **25+** | High-level logical flows covering all modules. |
| **Test Cases** | **50+** | Detailed steps with expected vs. actual results. |
| **Defects Found** | **12** | Valid bugs including UI glitches and functional errors. |
| **Critical Issues** | **2** | High-severity issues blocking core checkout flows. |
| **Test Coverage** | **95%** | Functional coverage of User, Guest, and Admin modules. |
| **Execution Time** | **12 Hours** | Total manual effort for one full regression cycle. |

---

## 🏗️ Project Structure

The repository is organized to mirror a standard QA project directory:

```bash
Manual-Testing-Ecommerce-Project/
├── 01_Requirement_Document/    # SRS & BRD Analysis
├── 02_Test_Plan/               # Strategy, Scope, Entry/Exit Criteria
├── 03_Test_Scenarios/          # High-Level Business Flows
├── 04_Test_Cases/              # Step-by-Step Validation Scripts
├── 05_Test_Data/               # Test Data (SKUs, User Credentials)
├── 06_Defect_Reports/          # Bug Reports with Severity/Priority
├── 07_Traceability_Matrix/     # RTM (Requirements <-> Test Cases)
├── 08_Test_Execution_Report/   # Final Pass/Fail Summary
└── 09_Screenshots/             # Evidence of functionality/bugs
```

---

## 💡 Key Highlights

### 1. Traceability (RTM)
Every test case is mapped back to a specific requirement ID (e.g., `REQ-001`). This ensures **100% Requirement Coverage** and prevents "scope creep."

### 2. Defect Reporting
Bugs are not just listed; they are documented with:
*   **Steps to Reproduce**: Exact path to trigger the bug.
*   **Severity vs. Priority**: Distinguishing between "System Crash" (High Severity) and "Logo Misalignment" (Low Severity).
*   **Evidence**: Screenshots attached for faster developer resolution.

---

## 🤝 Contributing

This is a portfolio project demonstrating Manual Testing interaction. Suggestions for improving test coverage or documentation formats are welcome!

1.  Fork the repository.
2.  Create a feature branch.
3.  Submit a Pull Request.

---

**Author**: Yash Desai  
**License**: MIT
