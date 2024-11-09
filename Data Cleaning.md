- Create Hirerachy for Department and Job title

## Calculated Fields
- Generating to display the total number of hired employees, active employees, and terminated employees.
```
Total Hired: COUNT([Employee ID])
Total Active: COUNT(IF ISNULL([Termdate]) THEN [Employee ID] END)
Total Terminated: COUNT(IF NOT ISNULL([Termdate]) THEN [Employee ID] END)
```

- To return which states are HQ else Branch
```
CASE [State] WHEN 'New York' THEN 'HQ' ELSE 'Branch' END
```

- % Total Hired
```
[Total Hired] / TOTAL([Total Hired])
```

- Age
```
DATEDIFF('year', [Birthdate], TODAY())
```

- Age Groups
```
IF [Age] < 25 THEN '<25' 
ELSEIF [Age] >= 25 AND [Age] < 35 THEN '25-34'
ELSEIF [Age] >= 35 AND [Age] < 45 THEN '35-44'
ELSEIF [Age] >= 45 AND [Age] < 55 THEN '45-54'
ELSEIF [Age] >=55 THEN '55+'
END
```

- Staus
```
IF ISNULL([Termdate]) THEN 'Hired'
ELSE 'Terminated'
END
```
