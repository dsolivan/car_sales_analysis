# Car Sales Analysis

## Tools: Python, SQL, Tableau

### SQL: Joined Tables and Added Calculated Column
```
SELECT *, savings_amount / (price + savings_amount) AS savings_rate
FROM base
LEFT JOIN accident
ON base.vin = accident.vin
LEFT JOIN fuel_type
ON base.vin = fuel_type.vin
```
### PowerBI Dashboard: https://app.powerbi.com/view?r=eyJrIjoiNWY5YjQyZmItZThhMS00OWNhLWI2N2UtMzVhZjUzZTA0NDJiIiwidCI6ImE2OTg2NjdkLTg4MTctNGFkOS1hN2YyLWJiMjg3Zjg2N2U1ZiIsImMiOjF9#L
