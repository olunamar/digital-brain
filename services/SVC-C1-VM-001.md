---
type: VirtualMachineServiceInstance
title: Northwind Retail Iberia VM Service
id_unico: SVC-C1-VM-001
customer_id: CUST-000184
offering_id: VM-GOLD
status: Active
ssot_principal: Service Management
tags:
  - service-instance
  - managed-infrastructure
---

# Northwind Retail Iberia VM Service

Concrete managed service instance delivered to one customer.

## Relationships

- CONSUMED_BY: [Northwind Retail Iberia](../customers/CUST-000184.md)
- INSTANCE_OF: [Managed Virtual Machine Gold](../catalog/service-offerings/VM-GOLD.md)
- DELIVERED_BY: [Northwind Retail Iberia VM 01](../infrastructure/resources/VM-C1-PROD-01.md)
- SUPPORTS: [ERP Workload](../workloads/WL-NW-ERP.md)
