# ServiceNow Incident Management Automation

## Project Overview
This project demonstrates automated incident assignment using ServiceNow Flow Designer.

When a new incident is created, the system automatically assigns it to a predefined assignment group without manual intervention.

---

## Business Requirement
Manual assignment of incidents causes:
- Delays in response
- SLA breaches
- Increased workload for service desk agents

### Objective
- Auto-assign incidents on creation
- Reduce manual effort
- Improve response time

---

## Solution Overview
A ServiceNow Flow Designer automation was implemented with the following logic:

- **Trigger:** Incident Created
- **Condition:** State = New
- **Action:** Update Assignment Group

---

## Flow Logic
1. User creates a new incident
2. Flow Designer trigger executes
3. System validates incident state
4. Assignment group is updated automatically

---

## Tools & Technologies
- ServiceNow Flow Designer
- Incident Management (ITSM)
- Update Sets
- Global Application

---

## Testing & Validation
The flow was tested by creating new incidents with
