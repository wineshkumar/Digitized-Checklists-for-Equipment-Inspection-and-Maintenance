# Digitized Checklists for Equipment Inspection and Maintenance

## Overview
This project digitizes the Daily Inspection (DI) process for aircraft Ground
Support Equipment (GSE), replacing a fully paper-based checklist system with
a centralized digital solution built using Microsoft Power Platform.

The solution supports daily inspections for 262 ground support equipment units
and enables electronic data capture, validation, approval, and reporting.

## Business Context
The Engineering team is responsible for conducting rigorous daily inspections
to ensure the operational readiness and safety of aircraft ground support
equipment. Previously, inspections were recorded using physical paper
checklists, resulting in manual effort, limited visibility, and challenges
in record maintenance and reporting.

As part of a sustainability and operational efficiency initiative, the process
was transformed into a digital platform.

## Solution
A Power Apps-based inspection application was developed to allow engineers
to perform daily equipment inspections digitally. Inspection data is stored
centrally, and an automated verification workflow ensures station- and
function-specific approvals.

The solution was designed after closely reviewing operational pain points and
user workflows to ensure ease of adoption and accuracy.

## System Architecture
- Power Apps: Digital inspection checklist and submission interface
- SharePoint: Centralized storage of inspection records
- Power Automate: Automated verification and approval workflows
- Power BI (optional): Reporting and inspection analytics

## Key Features
- Digital daily inspection checklists for 262 GSE units
- Station- and function-wise inspection tracking
- Real-time daily counters showing inspection completion status
- Bulk checklist marking for common “Yes” responses
- Automated approval routing based on station and function
- Validation to prevent duplicate inspections on the same day
- Mandatory completion checks before submission for verification

## Workflow Summary
1. User performs daily inspections via Power Apps.
2. Inspection data is saved to SharePoint.
3. Real-time counters track inspection completion by station and function.
4. User submits completed inspections for verification.
5. Power Automate routes approvals to the relevant reviewer.
6. Verified records are stored for reporting and audit purposes.

## Impact
- Eliminated paper-based inspection records
- Improved data accuracy and traceability
- Reduced manual effort for engineering teams
- Streamlined verification and reporting processes
- Estimated reduction of ~100kg CO₂ annually through paper reduction
- Enhanced operational efficiency and compliance

## Screenshots
(Add anonymized screenshots of the Power App, approval flow, and dashboards)
