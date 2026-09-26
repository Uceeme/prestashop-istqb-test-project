# PrestaShop Demo Store – Manual Testing Project (ISTQB CTFL v4.0)

End-to-end manual system testing of the [PrestaShop demo store](https://demo.prestashop.com) front office (Hummingbird theme), following the ISTQB test process: planning, analysis, design, implementation, execution and completion.

**Tester:** Uche · **Programme:** GoMyCode – ISTQB CTFL v4.0 Final Project · **Test period:** 23–24 September 2026

## Deliverables

| Document | Description |
|---|---|
| [Test Plan](PrestaShop_Test_Plan.docx) (PS-TP-001) | Objectives, scope (features F01–F10), approach and techniques, entry/exit criteria, environment, schedule, risks, defect management |
| [Test Cases & Traceability Matrix](PrestaShop_Test_Cases_and_Traceability.xlsx) | 73 test cases (steps, test data, expected/actual results, status), defect log and the traceability matrix linking features ↔ test cases ↔ defects |
| [Defect Reports](PrestaShop_Defect_Reports.docx) (PS-DR-001) | 10 defect reports with steps to reproduce, expected vs actual result, severity and priority |
| [Test Summary Report](PrestaShop_Test_Summary_Report.docx) (PS-TSR-001) | Execution metrics, results by feature, evaluation against exit criteria, lessons learned and recommendations |

## Features in scope

| ID | Feature | Test cases |
|---|---|---|
| F01 | Account registration | 13 |
| F02 | Sign-in, sign-out & password recovery | 9 |
| F03 | Product search | 8 |
| F04 | Catalogue navigation, filters & sorting | 8 |
| F05 | Product details page | 8 |
| F06 | Shopping cart | 6 |
| F07 | Checkout & order placement | 9 |
| F08 | Customer account area | 3 |
| F09 | Contact form & newsletter | 5 |
| F10 | UI, usability & compatibility | 4 |

Feature coverage: **10/10** – every feature is traced to at least one test case in the bidirectional traceability matrix.

## Results at a glance

- **73** test cases planned · **72** executed · **62** passed · **10** failed · **1** not run (cross-browser – only Chrome available)
- Pass rate of executed tests: **86.1 %** · High-priority pass rate: **89.3 %**
- **10** defects logged: 0 Critical, 4 Major, 6 Minor

## Test design techniques

Equivalence partitioning, boundary value analysis, decision tables, state transition testing, error guessing and exploratory testing (ISTQB CTFL v4.0, Chapter 4).

## Environment

Google Chrome (latest) on Windows desktop; mobile layout checked at 375×667. Test data uses dummy `@example.com` accounts and offline payment methods only.
