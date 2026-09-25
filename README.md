# AI-Driven Reporting Automation | Microsoft Copilot

A sanitized portfolio case study of an enterprise reporting automation project developed during my Navarro-ATL internship in 2026.

> \*\*Portfolio note:\*\* This repository contains only a public-facing reconstruction of the project's design and capabilities. It does \*\*not\*\* contain internal prompts, employee information, proprietary data, actual report content, screenshots, or other non-public Navarro-ATL/DOE materials.

## Overview

This project used Microsoft Copilot and governed Microsoft 365 data sources to streamline recurring leadership reporting. The goal was to make reports more consistent, easier to generate, and easier for leadership to interpret while preserving a standardized DOE-aligned structure.

The reporting workflow supported weekly, biweekly, monthly, bimonthly, quarterly, and custom reporting periods.

## Key Features

* Built a structured Microsoft Copilot reporting prompt to automate consistent DOE-aligned reports across weekly, biweekly, monthly, bimonthly, and quarterly reporting cycles.
* Integrated governed Outlook, Teams, and SharePoint/OneDrive data sources to retrieve relevant activity and generate accurate, time-bound report content.
* Implemented acronym validation, standardized technical language, and an 8-section report structure to produce clear, leadership-ready reporting.
* Added automated cadence selection and dynamic date-window logic, including custom start and end dates for non-standard reporting periods.
* Standardized reporting workflows to reduce manual effort and formatting inconsistencies, improve readability, and support adoption of the structure by other departments.

## Technologies \& Concepts

* Microsoft Copilot
* Microsoft Outlook
* Microsoft Teams
* SharePoint
* OneDrive
* Prompt engineering
* Enterprise AI
* Reporting automation
* Date-window and cadence logic
* Acronym validation
* Standardized technical reporting
* Governed enterprise data retrieval

## Workflow

The public workflow below is intentionally high-level:

**Governed Microsoft 365 Sources → Microsoft Copilot → Reporting Period Logic → Validation \& Standardization → Structured Leadership Report**

## Reporting Logic

At a high level, the workflow:

1. Determines the requested reporting cadence or accepts a custom date range.
2. Establishes the appropriate reporting window.
3. Retrieves relevant activity from authorized Microsoft 365 sources.
4. Organizes the retrieved information into a standardized report structure.
5. Applies acronym validation and consistent technical language.
6. Produces a reader-friendly report for leadership review.

The original production prompt and internal implementation details are intentionally excluded from this repository.

## Example

A fictional example showing the type of sanitized output this workflow could produce is available in [`examples/fictional-report-example.md`](examples/fictional-report-example.md).

The example contains no real employee names, assignments, internal activities, or company data.

## Outcome

The workflow reduced repetitive report preparation and inconsistent formatting while making recurring updates easier to interpret. The standardized structure was useful enough to support adoption by other departments.

## Confidentiality

This repository is a **sanitized portfolio representation**, not the production implementation.

It intentionally excludes:

* Employee names or identifying information
* Actual employee assignments or tasks
* Internal emails, Teams messages, or SharePoint/OneDrive content
* Production prompts or proprietary instructions
* Internal screenshots
* Actual report outputs
* Credentials, links, IDs, permissions, or access details
* Sensitive or non-public Navarro-ATL/DOE information

## Author

**Colin Holdeman**  
B.S. Information Technology — University of Washington Tacoma, 2026

