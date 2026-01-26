# ServiceNow Incident Management Automation

## Project Overview
This project demonstrates the implementation of an ITSM Incident Management automation using the ServiceNow platform.

The goal of the project is to simulate a real-world IT support process where incidents are created by users and automatically routed to the appropriate support team using workflow automation.

This project was developed using a personal ServiceNow developer instance as part of hands-on learning for CSA and CAD certification preparation.

---

## Business Requirement
In many IT service environments, manual assignment of incidents leads to:

- Delay in response time
- SLA breaches
- Increased workload on service desk agents
- Inefficient ticket routing

### Objective
- Automate incident assignment on creation
- Reduce manual effort
- Improve first-response efficiency
- Follow standard ITSM practices

---

## Solution Overview
A Flow Designer–based automation was implemented to handle incident routing automatically.

### Key Features
- Incident creation using standard ITSM process
- Automated assignment group selection
- Workflow execution using Flow Designer
- Validation of incident state during creation
- Tested and verified automation logic

---

## Flow Logic
1. User creates a new incident through the incident form.
2. Flow Designer trigger activates on record creation.
3. System validates incident state as "New".
4. Assignment group is automatically populated.
5. Incident is routed to the appropriate support team.

---

## Tools & Technologies
- ServiceNow Platform
- ITSM Incident Management
- Flow Designer
- Update Sets
- Global Application

---

## Screenshots
- Incident creation form
- Incident list view
- Flow Designer automation
- Auto-assigned incident record

(Screenshots available in repository)

---

## Testing & Validation
Multiple test cases were executed to validate automation behavior.

- Incident created without assignment group
- Flow triggered successfully
- Assignment group populated automatically
- No manual intervention required

Test results are documented in `test-results.md`.

---

## Learning Outcomes
- Practical understanding of ITSM incident lifecycle
- Hands-on experience with ServiceNow Flow Designer
- Improved knowledge of no-code workflow automation
- Experience documenting enterprise application logic
