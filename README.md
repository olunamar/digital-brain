# Digital Brain OKF MVP

A deterministic example corpus for a managed infrastructure provider. It contains three synthetic customers, two workloads per customer, customer-specific environments and services, and shared or dedicated infrastructure.

Start with [manifest.md](manifest.md).


# Markdown structure

The Markdown files use consistent YAML frontmatter and relative links between entities, making the corpus suitable as an initial deterministic knowledge source for a basic AI agent.

```
digital_brain_okf_mvp/
├── README.md
├── manifest.md
├── catalog/
│   ├── README.md
│   ├── service-offerings/
│   └── service-tiers/
├── customers/
├── workloads/
├── environments/
├── services/
└── infrastructure/
    ├── README.md
    ├── clusters/
    ├── database-platforms/
    └── resources/

```

# Content

| Element                 | Quantity |
| ----------------------- | -------: |
| Customers               |        3 |
| Workloads               |        6 |
| Workloads per customer  |        2 |
| Customer environments   |        5 |
| Service instances       |        9 |
| Services per customer   |        3 |
| Infrastructure elements |       15 |
| Example relationships   |      114 |
| Markdown files          |       50 |


# Model

Each customer has:

```
Customer
├── Workload 1
├── Workload 2
├── VM Service
├── Web Service
└── Database Service

```

The complete navigation path is:

```
Customer
→ Workload
→ Environment
→ Service Instance
→ Catalog Offering
→ VM / Web Instance / Database Instance
→ Hypervisor Cluster / Database Platform

```