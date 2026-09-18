---
type: DatabaseServiceInstance
title: Contoso Manufacturing Spain Database Service
id_unico: SVC-C2-DB-001
customer_id: CUST-000185
offering_id: POSTGRES-GOLD
status: Active
ssot_principal: Service Management
tags:
  - service-instance
  - managed-infrastructure
---

# Contoso Manufacturing Spain Database Service

Concrete managed service instance delivered to one customer.

## Relationships

- CONSUMED_BY: [Contoso Manufacturing Spain](../customers/CUST-000185.md)
- INSTANCE_OF: [Managed PostgreSQL Gold](../catalog/service-offerings/POSTGRES-GOLD.md)
- DELIVERED_BY: [Contoso Manufacturing Spain PostgreSQL Instance](../infrastructure/resources/DBI-C2-PG-01.md)
- SUPPORTS: [Manufacturing Execution Workload](../workloads/WL-CT-MES.md)
- SUPPORTS: [Supply Chain Workload](../workloads/WL-CT-SUPPLY.md)
