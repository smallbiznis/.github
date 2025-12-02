# ⭐ SmallBiznis Billing API
### *Modern, Modular, and Fully Self-Hosted Billing Engine for SaaS & Platforms*

SmallBiznis Billing API is a developer-first, event-driven billing engine designed for **multi-tenant SaaS**, **platform businesses**, and **usage-based applications**.  
Deliver subscription, metering, invoicing, and credit-based trials — all with clean APIs and production-ready infrastructure.

---

## 💡 What We Solve

Modern platforms need flexible billing:

- **Subscriptions for tenants or organizations**
- **Usage-based metering (per seat, per execution, per API call, etc.)**
- **Automated invoicing**
- **Trial & credit balance management**
- **Plan upgrades, downgrade, proration, and cancellation**
- **Event-driven internal billing**
- **Multi-tenant isolation**

SmallBiznis Billing API provides a **complete foundation** so you never have to build a billing system from scratch again.

---

## 🧩 Core Capabilities

### **1. Subscription Management**
- Flat-rate, per-seat, and usage plans  
- Trialing, active, past_due, canceled  
- Scheduled cancellation & renewal windows  
- Multi-tenant subscription isolation  
- Plan upgrade/downgrade workflows  

### **2. Usage-Based Billing**
- Metered billing using internal usage events  
- Workflow executions  
- Rule engine evaluations  
- Notification sends  
- Voucher & loyalty operations  
- Custom usage events  
- Accurate usage aggregation per tenant & billing cycle  

### **3. Trials & Free Credit System (GCP-Style)**
- Time-boxed, credit-based trials  
- Credits deducted automatically from plan/usage  
- Trial exhaustion detection  
- Smooth transition to pay-as-you-go or paid plan  

### **4. Invoicing Engine**
- Automated billing cycles  
- Combine subscription + usage charges  
- Line items with detailed metadata  
- Draft → Open → Paid → Void  
- Proration support  
- Webhook events for invoice lifecycle  

### **5. Balance & Quotas**
- Credit balance (like GCP free tier)  
- Quota enforcement per module or feature  
- Optional throttling integrations  

### **6. Developer-First API**
- gRPC  
- REST via gRPC-Gateway  
- OpenAPI 3.1  
- Strongly typed SDKs (Go, TypeScript, Python)  

---

## 🏗 Platform Architecture

SmallBiznis Billing API is built using modern, scalable components:

- **Go** microservices  
- **PostgreSQL + SQLC** for transactional data  
- **ClickHouse** for usage analytics  
- **NATS / Kafka** for event ingestion  
- **Temporal** for billing cycles & retries  
- **Nomad + Consul + Vault** for production orchestration  
- **OpenTelemetry** for metrics & tracing  

Designed for:
- High-throughput metering  
- Multi-tenant scalability  
- Isolated data boundaries  
- Event-driven billing workloads  

---

## 📚 Documentation

### 🔗 API Reference  
https://docs.smallbiznis.io/billing/api

### 🔗 Subscription Concepts  
https://docs.smallbiznis.io/billing/subscriptions

### 🔗 Usage Metering Guide  
https://docs.smallbiznis.io/billing/usage

### 🔗 Invoice Specification  
https://docs.smallbiznis.io/billing/invoices

---

## 📦 Repositories in This Organization

| Repository | Description |
|-----------|-------------|
| **billing-service** | Core subscription + balance engine |
| **billing-usage** | Usage metering consumer + aggregator |
| **invoice-service** | Invoice generator + billing cycle management |
| **billing-proto** | Protobuf schemas for all billing services |
| **billing-frontend** | Next.js UI for billing dashboard & tenant billing portal |
| **sdk-go / sdk-js** | Developer SDKs |
| **examples** | Integration examples (SaaS, multi-tenant, workflows) |

---

## 🧭 Roadmap

### **Near Term**
- Complete invoice engine  
- Add proration logic  
- Add Stripe/Midtrans payment connectors  
- Add webhook signing + callback system  
- Add analytics dashboards  

---

## 🚀 Our Vision

To make **world-class, self-hosted billing infrastructure** accessible to every SaaS, startup, and platform — without vendor lock-in.

Whether you're building:
- a SaaS,  
- a marketplace,  
- a workflow automation platform,  
- or a modular multi-tenant system…

SmallBiznis Billing API gives you a **scalable, extensible billing core** you can trust.
