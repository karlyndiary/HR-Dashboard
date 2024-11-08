- Create Hirerachy for Department and Job title

## Calculated Fields
- Generating to display the total number of hired employees, active employees, and terminated employees.
```
Total Hired: COUNT([Employee ID])
Total Active: COUNT(IF ISNULL([Termdate]) THEN [Employee ID] END)
Total Terminated: COUNT(IF NOT ISNULL([Termdate]) THEN [Employee ID] END)
```
