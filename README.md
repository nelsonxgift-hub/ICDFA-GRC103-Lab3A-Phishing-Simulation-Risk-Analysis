# ICDFA-GRC103-Lab3A-Phishing-Simulation-Risk-Analysis
# ICDFA GRC103 — Lab 3A: Phishing Simulation Metrics and Quantitative Risk Analysis

**Prepared by:** Rosemary Gift Nelson
**Registration Number:** C11/26/CGRCE-17216
**Cohort:** 11 / Batch A
**Scenario:** GlobalTech Inc. — Phishing Simulation Metrics and Quantitative Risk Analysis
**Submission date:** 01 November 2026

## Scope

This lab's submission instructions explicitly require independently verifying the brief's own worked example and correcting any calculation errors or unsupported assumptions found in it, rather than reproducing the brief's figures as-is. Four such corrections were identified and are documented in full in both deliverables below (Assumptions sheet of the workbook; Appendix of the report).

Summary of the key correction: the brief's worked example reports an Annualized Loss Expectancy (ALE) of $652,500,000 by treating 600 employees with compromised credentials as 600 separate full-scale breaches. The dataset's own 25% figure is the Annual Rate of Occurrence (ARO) itself, applied once at the organizational level: **ALE = SLE × ARO = $4,350,000 × 25% = $1,087,500** — roughly 600× smaller than the brief's figure.

## Files in this repository

| File | Description |
|---|---|
| `GRC103_Lab3A_Calculation_Workbook_Rosemary_Nelson_C11-26-CGRCE-17216.xlsx` | Completed calculation workbook — Phases 1–3: Executive Dashboard, Assumptions & Corrections, Campaign Metrics, Financial Risk Calculations (SLE/ARO/ALE with live formulas), Control Recommendation Table, Risk Assessment Matrix, Statistical Analysis (95% confidence intervals). 136 live formulas, 0 recalculation errors. |
| `GRC103_Lab3A_Executive_Report_Rosemary_Nelson_C11-26-CGRCE-17216.docx` | Executive briefing memo (To: Board of Directors, CISO, CFO) — Executive Summary, Key Quantitative Findings, Detailed Financial Analysis, Strategic Recommendations, Expected Risk Posture After Controls, Bonus Challenge break-even analysis, and full corrections/assumptions appendix. |

## Deliverable mapping (per the brief)

1. **Completed Calculation Worksheets (Phases 1 & 2)** — Workbook, "Campaign Metrics" and "Financial Risk Calcs" sheets
2. **Risk Assessment Matrix (Phase 3)** — Workbook, "Risk Assessment Matrix" sheet
3. **Statistical Analysis with confidence intervals** — Workbook, "Statistical Analysis" sheet
4. **Executive Briefing with specific financial calculations** — Executive Report (.docx)
5. **Control Recommendation Table with ROI calculations** — Workbook, "Control Recommendations" sheet
6. **Bonus Challenge (break-even analysis)** — Workbook, "Control Recommendations" sheet (bottom) and Executive Report, Section 6

## Key results

| Metric | Value |
|---|---|
| Overall Credential Theft Rate (corrected) | 24.4% |
| Current-state ALE (corrected) | $1,087,500 |
| Highest-risk campaign | Campaign B – IT System Password Reset (30.0%, CRITICAL) |
| Combined control investment | $240,000 |
| Combined 1-year ROI (sum of independent effects) | 987.0% |
| Rigorous combined-deployment ROI (controls applied sequentially) | 453% (residual ALE $87) |
