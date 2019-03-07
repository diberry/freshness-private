Steps to complete Freshness report

1. Automate
  a. Current docs metadata
    i. get metadata information from azure-docs-pr
    ii. parse metadata
    iii. create CSV report
  
  b. get KUSTO information for each file in CSV report from Cube
    1. get data from Cube
    2. create CSV report
    
  c. put all data in sql server
  
  d. create web-based UX
    power-bi or angular
    allow export to xls
    
  e. update data daily
  
  f. create communication mechanism to join for information and access

[Add AAD to SQL server](
https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication-configure)
