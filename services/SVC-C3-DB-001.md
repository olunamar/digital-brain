---
type: DatabaseServiceInstance
title: Fabrikam Professional Services Database Service
id_unico: SVC-C3-DB-001
customer_id: CUST-000186
offering_id: POSTGRES-GOLD
status: Active
ssot_principal: Service Management
tags:
  - service-instance
  - managed-infrastructure
---

# Fabrikam Professional Services Database Service

Concrete managed service instance delivered to one customer.

## Relationships

- CONSUMED_BY: [Fabrikam Professional Services](../customers/CUST-000186.md)
- INSTANCE_OF: [Managed PostgreSQL Gold](../catalog/service-offerings/POSTGRES-GOLD.md)
- DELIVERED_BY: [Fabrikam Professional Services PostgreSQL Instance](../infrastructure/resources/DBI-C3-PG-01.md)
- SUPPORTS: [Customer Portal Workload](../workloads/WL-FB-PORTAL.md)
- SUPPORTS: [Reporting Workload](../workloads/WL-FB-REPORT.md)
