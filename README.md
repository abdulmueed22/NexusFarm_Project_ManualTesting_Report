# NexusFarm — Manual Testing Report

## Overview
This repository contains the manual software testing documentation for **NexusFarm**, a marketplace designed to connect farmers and suppliers in Pakistan. The report organizes key application features, testing scenarios, test cases, and requirement traceability to support a structured quality assurance process.

## Project Under Test
NexusFarm is a marketplace application that allows farmers to list agricultural products and suppliers to submit bids based on product requirements, quantities, and prices.

## Testing Scope
The report focuses on the following major functional areas:

- **Authentication & Role Access** — Login, validation, and role-based access.
- **Farmer Product Listings** — Creating, viewing, and managing product listings.
- **Supplier Bid Management** — Submitting and validating bids.
- **Product Images & Data Persistence** — Image uploads and saving/retrieving application data.

## Test Documentation
The Excel workbook includes the following sheets:

| Sheet | Description |
|---|---|
| Read Me | Report overview and execution guidance |
| Feature Inventory | List of application features and their testing scope |
| Test Scenarios | High-level scenarios for validating application functionality |
| Test Cases | Detailed test cases with prerequisites, steps, test data, and expected results |
| RTM | Requirement Traceability Matrix linking requirements to test scenarios and cases |

## Testing Summary

- **9** features documented
- **8** test scenarios prepared
- **32** detailed manual test cases
- **8** requirements mapped in the RTM

> **Note:** Test cases are initially marked as `Not Executed`. Actual results and pass/fail statuses should be updated after testing the application.

## Technology Stack
Based on the project's documentation, the application uses:

- HTML and Bootstrap
- C#
- ADO.NET
- Microsoft SQL Server
- AWS S3 for image storage

## How to Use
1. Download the Excel manual testing report from this repository.
2. Review the Feature Inventory and Test Scenarios sheets.
3. Execute the test cases against the application.
4. Record actual results and mark each test case as Pass, Fail, Blocked, or Not Executed.
5. Use the RTM sheet to verify requirement coverage.

## Purpose
This project demonstrates practical skills in manual software testing, test case design, functional testing, test documentation, and requirement traceability.

## Disclaimer
This report is prepared for QA practice and portfolio demonstration. Test coverage and application behavior should be verified against the current version of NexusFarm before drawing conclusions about the application's quality.
