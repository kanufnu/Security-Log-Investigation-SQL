# Security Log Investigation Using SQL 

## Project Overview

This project demonstrates how SQL queries can be used to investigate authentication logs and identify suspicious login activity within an organization. The analysis focuses on detecting unsual login behaviour, 
failed login attempts, and identifying systems requiring security updates.

## Objectives
- Investigate login activity occurring outside normal business hours
- Identify suspicious login attempts on specific dates
- Detect login attempts from unexpected geographic locations
- Retrieve employee records requiring security updated
- Support targeted system patching and incident invedtigation

## Dataset Description
The investigation uses two primary datasets:
-  **Login Activity Table:** Contain login timestamps, usernames, success/failure status, and geographic login information.
-  **Employee Information Table:** Contains employee department, building location, and assigned system requiring updates.

## SQL Investigating Tasks
**1. Retrieve After-Hours Failed Login Attempts**

  SQL queries were used to filter login records occuring after standard business hours and identify failed authentication attempts that may indicate suspicious activity.

**2. Investigate Login Activity on Specific Dates**

  Queries were applied to identify login attempts occuring on designated investigation dates to support incident review.


**3. Identify Login from Unexpected Geographic Locations**

  Filtered login activity originating from location outside the organiztion's expected operational regions.

  **4. Retrieve Employee Systems Requiring Security Updates**

  SQL filtering was used to identify employee systems in specific departments and buildings that required targeted patching and security updateds.

  ## SQL Techniques Used

  - WHERE clause filtering
  - AND / OR / NOT logical operators
  - Date and time filering
  - IN operator
  - LIKE operator with wildcard filtering
## Screenshots

 Screenshots of SQL queries and query results demonstrating the investigation steps are included in this repository to show the analysis process and findings.

## Security Value

This project demonstrates how SQL can be applied to support security monitoring, authentication log investigation, and vulnerability management by enabling targeted analysis of login activity and 
organizational system records.The investigation approach reflects foundational skills used in Security Operations Center (SOC) environments for detecting suspecious activity and supporting incident response.


    


   

   
   
   
