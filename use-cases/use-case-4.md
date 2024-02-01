# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context
- As an *HR advisor* I want *to produce a report on the salary of employees of a given role* so that *I can support financial reporting of the organisation.*
- As an *HR advisor* I want *to produce a report on the salary of employees in a department* so that *I can support financial reporting of the organisation.*
- As an *HR advisor* I want *to produce a report on the salary of employees in my department* so that *I can support financial reporting for my department.*

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role.  Database contains current employee salary data.

### Success End Condition
A report is available for HR to provide to finance.

### Failed End Condition
No report is produced.

### Primary Actor
HR Advisor.

### Trigger
A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO
1. Finance request salary information for a given role.
2. HR advisor captures name of the role to get salary information for.
3. HR advisor extracts current salary information of all employees of the given role.
4. HR advisor provides report to finance.
5. HR advisor will be able to view, add, update and delete employee and employee's details.

## EXTENSIONS
3. **Role does not exist**:
    1. HR advisor informs finance no role exists.

## SUB-VARIATIONS
None.

## SCHEDULE
**DUE DATE**: Release 1.0
