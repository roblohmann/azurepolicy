# SQL Databases should require using GRS backup redundancy

Databases should require using the default geo-redundant storage for backups, if data residency rules require data to stay within a specific region. Note: Azure Policy is not enforced when creating a database using T-SQL. If not explicitly specified, database with geo-redundant backup storage is created via T-SQL.