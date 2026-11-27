# Evidence Register

**Project:** Tourist Place Search and Ranking System  
**Repository:** https://github.com/shri030306/Mini-project-Engine04

This index describes the evidence currently present in the repository. The spreadsheet contains 150 planned test cases and a first limited execution update.

## Available evidence

| ID | Artifact | What it supports | Limit |
| --- | --- | --- | --- |
| E1 | `Tourist_Place_Search_150_Test_Cases.xlsx` | Test plan with 150 scenarios, preconditions, steps, and execution fields; includes a separate `Failed Cases` worksheet. | Current status: 4 `Pass`, 9 `Partial`, and 137 `Not Run`. No failed cases have been recorded in the current run; the separate worksheet has its headers and is ready for actual failures. |
| E2 | Engine 2 automated test run (27 November 2026) | `npm run check` passed and `npm test` passed in an isolated copy using the suite's mock database. Four matching workbook cases are marked `Pass`; nine related cases are marked `Partial`. | This run did not connect to the live MySQL database or test the Engine 3 browser UI. No implementation files were modified. Partial results do not certify the full test steps. |
| E3 | This GitHub repository | Shared project location and the workbook/evidence files. | The repository snapshot does not include the Engine 2/Engine 3 implementation source; the automated run used the source files supplied in the local project folder. |

## Case coverage

- Data & Integrity: 32
- Ranking Logic: 34
- Engine 2 API: 30
- Engine 3 User Interface: 30
- System Integration & Quality: 24
- **Total: 150**

The workbook includes positive, negative, edge, boundary, integration, security, accessibility, resilience, and regression scenarios.

## To add execution evidence

1. Continue with the remaining `Not Run` cases and complete every `Partial` case; fill Actual Result, Status, Tested By, and Test Date.
2. For failures, add a Bug ID and a screenshot or log of the observed result.
3. Add available implementation evidence, such as source files, database scripts, or an application screenshot.

**Evidence basis:** the 150-case workbook, Engine 2 test suite results from 27 November 2026, and repository file list. The live MySQL database and Engine 3 browser flow have not yet been verified in this run.
