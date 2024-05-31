### Find a column by column name across all tables in a kusto database
`.show schema 
| where ColumnName contains "path"
`

### Find a value across full kusto database
` Find "query-term" `
