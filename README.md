# It's a Timesheet App tracking employees' overtime

## Key requirement:
The client needs documentation that salaried employees did or did not get overtime each week

## Models:
- Post -> date:date rationale:text
- User -> Devise
- AdminUser -> STI (Single Table Inheritance)

## Features:
- Approval Workflow
- SMS sending mechanism -> link to approval or overtime input
- Administrate admin dashboard
- email summary to managers for approval
- needs to be documented if employee did not log overtime

## UI:
- Bootstrap -> formatting