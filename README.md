# BigQuery: Qwik Start - Console - GSP072

## Tasks
- Query a public dataset
- Create a new dataset
- Load data into a new table
- Query a custom table


### 1. Open BIgquery
### 2. Compose new query
```sql
#standardSQL
SELECT
 weight_pounds, state, year, gestation_weeks
FROM
 'bigquery-public-data.samples.natality'
ORDER BY weight_pounds DESC LIMIT 10;```
jjs
