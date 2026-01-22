# ServiceNow Incident Management Automation

## Project Overview
This project demonstrates automatic assignment of incidents using ServiceNow Flow Designer.

When a new incident is created, the system automatically assigns it to a predefined assignment group.

## Business Requirement
Manual assignment of incidents causes delay and SLA breach.

The goal is to:
- Automatically assign incidents on creation
- Reduce manual effort
- Improve response time

## Solution
A Flow Designer automation was created with:

- Trigger: Incident Created
- Condition: State = New
- Action: Update Assignment Group

## Flow Logic
1. Incident is created
2. Flow is triggered
3. System checks incident state
4. Assignment group is automatically updated

## Tools Used
- ServiceNow Flow Designer
- Incident Management
- Update Sets

## Result
- Assignment group populated automatically
- No manual intervention required
- Flow tested successfully

## Screenshots
Screenshots are available in the `/screenshots` folder.
