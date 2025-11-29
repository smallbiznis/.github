# 🚀 SmallBiznis Platform

SmallBiznis is a modern, modular platform designed to help businesses build and scale retail, commerce, and loyalty experiences.  
Our architecture is fully API-driven, multi-tenant, and production-ready for SaaS, POS, online stores, and enterprise integrations.

We provide a complete suite of services covering:

- **Identity & Tenant Management**
- **Billing & Subscription**
- **Invoices & Usage-based Charging**
- **Product Catalog & Inventory**
- **Unified Checkout (Online & POS)**
- **Loyalty Points**
- **Vouchers & Promotion Tools**
- **Order Fulfillment**
- **Campaigns, Notifications, Analytics, and more**

This organization hosts all open-source packages, SDKs, documentation, and reference implementations.

---

## 🧩 Platform Architecture

SmallBiznis is built using a **modular microservice** approach organized into clear domains:

- **Identity** — tenant, domain, and organization provisioning  
- **Billing** — subscription, balances, credits, trial management  
- **Catalog** — products, variants, options, inventory  
- **Commerce** — checkout, transaction, payments  
- **Loyalty** — points, movements, expiration  
- **Voucher** — discount codes, validation, redemption  
- **Operations** — fulfillment and delivery pipelines  
- **Growth** — campaign automation and notifications  
- **Intelligence** — audit logs, analytics, dashboards

All services communicate using **gRPC**, with REST exposure via **gRPC-Gateway**.

---

## 🛠 Tech Stack

- **Golang** — microservices  
- **gRPC + Protocol Buffers** — primary interface definition  
- **PostgreSQL / ClickHouse** — OLTP + analytical workloads  
- **Temporal / Asynq** — workflow & background job orchestration  
- **Nomad + Consul + Vault** — production orchestration  
- **OpenAPI v3** — HTTP API documentation  
- **Docusaurus + Redocly** — developer documentation  
- **Nx + Next.js** — frontend applications  
- **MinIO / S3** — asset + media storage  

---

## 📚 Documentation

👉 **API Reference**  
https://docs.smallbiznis.io/api

👉 **Developer Guides & Concepts**  
https://docs.smallbiznis.io/docs

👉 **OpenAPI Specifications**  
All OpenAPI files are stored in:

