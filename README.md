# Financial Data Entry & Verification Project

A self-guided practice project that simulates real-world financial data entry
and verification tasks — the core responsibilities in most Data Entry
Clerk / Data Entry Operator job postings.

## What this demonstrates
- Accurate, high-volume data entry into a structured database
- Verifying completeness and accuracy before/after entry
- Identifying and resolving data entry issues (duplicates, missing fields,
  inconsistent formatting)
- Maintaining organized, audit-ready financial records
- Spreadsheet proficiency (formulas, filters, data validation)

## Contents
The workbook (`Mock_Financial_Data_Entry_Project.xlsx`) contains:

| Sheet | Purpose |
|---|---|
| **Instructions** | Project overview and step-by-step practice guide |
| **Raw Data (Unverified)** | 320 vendor transaction records, ~41 with intentional data-entry errors (missing fields, negative amounts, duplicate invoice numbers, inconsistent vendor names, out-of-range dates, inconsistent casing) |
| **Cleaned Data (Answer Key)** | The same 320 records, fully verified and corrected |
| **Error Log (Answer Key)** | Every planted error, listed by field, issue type, and correct value |

## How to use it
1. Review `Raw Data (Unverified)` row by row.
2. Flag suspected errors using the built-in `Flag` and `Your Notes` columns.
3. Use the `Duplicate Invoice?` helper column (COUNTIF formula) to catch
   duplicate invoice numbers automatically.
4. Compare your findings against `Error Log (Answer Key)`.
5. Track your error-catch rate (errors found ÷ 41) as a measurable accuracy metric.

## Tools used
- Microsoft Excel / Google Sheets
- Formulas: `SUM`, `COUNTIF`
- Manual data verification and cleaning
