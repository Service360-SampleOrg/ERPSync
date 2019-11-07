# ERPSync

Application responsible for data synchronisation to/from ERP and 
Web-enabling services (Order, Customer, Catalog, etc).

Owner|Tier|Status|Contexts
---|---|---|---
ERPTeam|Tier2|Prod|Web,Customers,Orders,Catalog,Payments

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

Staging:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://... 

##### Tech

- Golang 13.x: implementation
- ECS: execution env 
- AWS SQS: transport medium
- AWS SNS: transport medium

