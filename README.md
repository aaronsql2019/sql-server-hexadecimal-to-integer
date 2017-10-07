# UDF To Convert Hexadecimal to Integer

This is a handy function for converting a hexadecimal value into an integer using a SQL Server user defined function. It was coded for SQL Server 2000.

```sql
SELECT dbo.udfHex2Int('FF') -- 255
SELECT dbo.udfHex2Int('03') -- 3
SELECT dbo.udfHex2Int('FF03') -- 65283
SELECT dbo.udfHex2Int('5544') -- 21828
```

_created: 2003 or 2004_
