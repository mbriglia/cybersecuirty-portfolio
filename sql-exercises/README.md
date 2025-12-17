# SQL Exercises
This section contains SQL exercises completed as part of the Google Cybersecurity Certificate. These exercises focus on filtering, alayzing, and investigating data in security-related scenarios
---
## Example: Identifying Failed Login Attempts
**Scenario:**
Reviewed login activity to identify failed login attempts that could indicate suspicious behavior.

**Query Used:**
```sql
SELECT *
FROM log_in_attempts
WHERE success = 0;
**Explanation:**
This query filters login data to display only failed login attempts, which can help identify potential unauthorized access or brute-force activity.
