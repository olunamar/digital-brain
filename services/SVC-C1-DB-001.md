---
type: DatabaseServiceInstance
title: Northwind Retail Iberia Database Service
id_unico: SVC-C1-DB-001
customer_id: CUST-000184
offering_id: POSTGRES-GOLD
status: Active
ssot_principal: Service Management
tags:
  - service-instance
  - managed-infrastructure
---

# Northwind Retail Iberia Database Service

Concrete managed service instance delivered to one customer.

## Relationships

- CONSUMED_BY: [Northwind Retail Iberia](../customers/CUST-000184.md)
- INSTANCE_OF: [Managed PostgreSQL Gold](../catalog/service-offerings/POSTGRES-GOLD.md)
- DELIVERED_BY: [Northwind Retail Iberia PostgreSQL Instance](../infrastructure/resources/DBI-C1-PG-01.md)
- SUPPORTS: [E-Commerce Workload](../workloads/WL-NW-ECOM.md)
- SUPPORTS: [ERP Workload](../workloads/WL-NW-ERP.md)
