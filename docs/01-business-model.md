<div align="center">

# 🌾 Aapla Kisan Business Model

### Farm-to-Consumer + Farm-to-Business Fresh Supply Chain Operating Model

A strategic business model for connecting farmers, vendors, collection points, dark stores, B2C consumers, and B2B buyers through a structured fresh produce platform.

<br>

![Status](https://img.shields.io/badge/Status-Business%20Model-1E7A34)
![Model](https://img.shields.io/badge/Model-B2C%20%2B%20B2B-2563EB)
![Supply](https://img.shields.io/badge/Supply-3%20Lane%20Sourcing-2E8B57)
![Ops](https://img.shields.io/badge/Ops-Dark%20Store%20Enabled-F59E0B)
![Portfolio](https://img.shields.io/badge/Portfolio-Strategy%20Case%20Study-6B7280)

</div>

---

<p align="center">
  <img src="../assets/images/supply_chain_flow.png" alt="Aapla Kisan Supply Chain Flow" width="900">
</p>

---

## 🚀 Executive Summary

Aapla Kisan is designed as a **fresh produce supply chain operating system**, not only as a grocery ordering app.

The model combines farmer/vendor supply, collection-center handling, quality grading, dark-store fulfilment, B2C ordering, B2B recurring demand, admin governance, and KPI-led decision-making.

---

# 🧩 Business Layer Architecture

| Business Layer | Strategic Purpose |
|---|---|
| 🌾 **Supply Layer** | Farmers, vendors, and collection points declare and supply produce |
| ✅ **Quality Layer** | Produce is checked, graded, accepted, rejected, or redirected |
| 🏬 **Fulfilment Layer** | Hub/dark store manages inventory, picking, packing, dispatch, returns |
| 🧺 **B2C Demand Layer** | Household consumers generate direct demand and repeat orders |
| 🏪 **B2B Demand Layer** | Restaurants, cafes, hostels, retailers, and institutions create recurring demand |
| 🧑‍💼 **Governance Layer** | Admin manages approvals, pricing, users, reports, roles, and exceptions |
| 📊 **Analytics Layer** | KPIs track wastage, stockouts, fill rate, supplier reliability, and order performance |

```mermaid
flowchart TD
    A[🌾 Supply Layer] --> B[✅ Quality Layer]
    B --> C[🏬 Fulfilment Layer]
    C --> D[🧺 B2C Demand]
    C --> E[🏪 B2B Demand]
    F[🧑‍💼 Governance Layer] --> A
    F --> B
    F --> C
    F --> D
    F --> E
    G[📊 Analytics Layer] --> F
```

---

# 📊 Demand Engine Mix

The model should balance B2C and B2B demand so the platform does not depend only on instant consumer orders.

```mermaid
pie title Strategic Demand Engine Mix
    "B2C Household Orders" : 55
    "B2B Recurring Orders" : 35
    "Pre-Booked / Planned Orders" : 10
```

> These values are planning assumptions for portfolio visualization and should be replaced with real pilot data after execution.

---

# 🧭 Market Problem

Fresh produce supply chains face structural problems because demand, quality, pricing, and fulfilment are difficult to control together.

| Stakeholder | Current Problem | Business Impact | Aapla Kisan Response |
|---|---|---|---|
| **Farmers / Vendors** | Price volatility, uncertain demand, limited structured buyer access | Lower predictability and weak bargaining power | Registration, supply declaration, grade-linked payout, visibility |
| **Consumers** | Inconsistent quality, changing prices, weak freshness trust | Lower repeat orders and poor confidence | Product clarity, delivery slot, tracking, quality cues |
| **B2B Buyers** | Unreliable daily supply, quality variation, procurement uncertainty | Operational disruption | Standing orders, rate card, grade-based supply |
| **Operations Team** | Weak inventory visibility, over-buying, stockouts, wastage | Higher cost and lower service quality | Dark store dashboard, picklist, dispatch queue, SOPs |
| **Platform Team** | Lack of dashboards, governance, and role-based controls | Difficult to scale | Admin panel, KPI rhythm, approvals, issue control |

---

# 🏗️ Proposed Operating Flow

<p align="center">
  <img src="../assets/images/integrated_logistics.png" alt="Integrated Logistics Model" width="850">
</p>

```mermaid
flowchart TD
    A[Farmer / Vendor] --> B[Harvest & Supply Declaration]
    B --> C[Collection Point / Agent]
    C --> D[Quality Check & Digital Grading]
    D --> E[Central Hub / Dark Store]
    E --> F[Inventory Allocation]
    F --> G[B2C Consumer Orders]
    F --> H[B2B Bulk / Recurring Orders]
    G --> I[Delivery + Tracking]
    H --> J[Scheduled Dispatch]
    I --> K[Feedback + Repeat Demand]
    J --> K
```

---

# 🔁 End-to-End Operating Model

## 1. Harvest and Supply Declaration

Farmers or vendors declare produce type, expected quantity, delivery date/time, expected grade, collection location, and price expectation before stock movement.

**Strategic value:** Early supply visibility improves procurement planning and reduces last-minute buying.

---

## 2. Collection and Digital Grading

<p align="center">
  <img src="../assets/images/cluster_hub_grading.png" alt="Collection Hub Grading" width="850">
</p>

Produce is received through local collection points or trained field agents.

| Grading Step | Purpose |
|---|---|
| Quantity verification | Confirms declared vs actual supply |
| Grade assignment | Separates Grade A, B, C, and rejected stock |
| Photo proof | Reduces disputes |
| Batch tagging | Creates traceability |
| Supplier score update | Measures reliability over time |

---

## 3. Hub / Dark Store Operations

<p align="center">
  <img src="../assets/images/dark-store-preview.png" alt="Dark Store Platform Preview" width="850">
</p>

The dark store becomes the operational control center for stock inward, sorting, storage, picking, packing, dispatch preparation, returns, stock adjustment, and wastage tracking.

---

## 4. B2C and B2B Distribution

| Demand Engine | Use Case | Strategic Benefit |
|---|---|---|
| **B2C** | Household fresh produce ordering | Builds direct demand and brand trust |
| **B2B** | Restaurants, cafes, hostels, retailers, institutions | Creates predictable recurring volume and stabilizes procurement |

---

# 📱 Product Ecosystem

| Product Layer | Primary User | Main Purpose | Preview |
|---|---|---|---|
| **Consumer App** | B2C customers | Discovery, ordering, tracking, repeat purchase | <img src="../assets/images/consumer-app-preview.png" width="160"> |
| **Farmer / Vendor App** | Farmers, vendors | Onboarding, listing, stock, pricing, payout | <img src="../assets/images/farmer-vendor-app-preview.png" width="160"> |
| **Admin Panel** | Admin team | Governance, approvals, pricing, orders, reports | <img src="../assets/images/admin-panel-preview.png" width="160"> |
| **Dark Store Platform** | Ops team | Picklist, packing, dispatch, inventory, returns | <img src="../assets/images/dark-store-preview.png" width="160"> |

---

# 💼 Revenue and Value Streams

```mermaid
pie title Potential Business Value Streams
    "B2C Order Margin" : 35
    "B2B Supply Margin" : 35
    "Delivery / Fulfilment Fee" : 10
    "Standing Order / Subscription" : 10
    "Value-Added Producer Services" : 5
    "Data-Led Planning Value" : 5
```

| Revenue / Value Stream | Description |
|---|---|
| **B2C Order Margin** | Margin on fresh produce sold to household customers |
| **B2B Supply Margin** | Margin on bulk/recurring supply to restaurants, cafes, retailers, hostels, institutions |
| **Delivery / Fulfilment Fee** | Fee based on delivery model, distance, or order size |
| **Subscription / Standing Order Model** | Recurring B2B supply arrangements for predictable demand |
| **Value-Added Producer Services** | Future scope: packaging, grading, digital listing, market access support |
| **Data-Led Planning Value** | Demand and supply insights for procurement planning and wastage control |

---

# 💰 Pricing Model Summary

Aapla Kisan uses a **fixed-price + market-linked pricing approach**.

| Pricing Element | Purpose |
|---|---|
| Assured floor price | Gives farmers/vendors minimum price confidence |
| Market reference benchmark | Keeps pricing realistic |
| Grade-based payout | Better quality earns better rates |
| Stable selling price band | Reduces customer price shock |
| Pre-booking advantage | Encourages predictable demand |
| B2B rate card | Supports recurring buyers with clear pricing |

---

# 🧪 Pilot Model

| Area | Recommended Scope |
|---|---|
| City / Zone | One city or selected delivery zones |
| Supply Side | Selected farmers, vendors, collection points |
| Demand Side | Selected B2C households and B2B buyers |
| B2B Segments | Restaurants, cafes, hostels, retailers, institutions |
| Operations | One central hub or dark store |
| SKU Range | Limited fresh produce catalog |
| Technology | MVP-level platform, dashboard, or manual-assisted workflow |
| Duration | 3 to 6 months |

---

# 📊 Pilot Success Metrics

```mermaid
xyChart-beta
    title "Pilot Success Metric Target Areas"
    x-axis ["Fulfilment", "On-Time", "Repeat B2C", "B2B Repeat", "Supplier Reliability", "Wastage Control"]
    y-axis "Target %" 0 --> 100
    bar [90, 85, 30, 60, 80, 90]
```

| KPI Category | Metrics |
|---|---|
| **Demand** | Total orders, repeat rate, B2B order frequency, average order value |
| **Supply** | Active suppliers, declared vs actual supply, supplier reliability |
| **Quality** | Accepted stock, rejected stock, complaint rate |
| **Inventory** | Wastage %, shrinkage, stockout frequency, SKU availability |
| **Operations** | Fulfilment rate, picking time, packing time, dispatch time |
| **Delivery** | On-time delivery, delayed orders, failed deliveries |
| **Finance** | Procurement variance, margin, delivery cost per order |

---

# ⚠️ Key Risks and Controls

| Risk | Business Impact | Control Mechanism |
|---|---|---|
| Supplier inconsistency | Stockouts and poor fulfilment | Multiple sourcing lanes and supplier reliability score |
| Poor quality produce | Complaints and returns | Digital grading and QC checkpoints |
| Over-buying | Wastage and margin loss | Pre-booking and demand forecasting |
| Delivery delays | Poor customer experience | Zone-wise batching and SLA tracking |
| B2B payment delays | Cash flow pressure | Clear buyer terms and credit checks |
| Weak SOP adoption | Operational inconsistency | Training, checklists, and weekly reviews |
| Low repeat demand | Weak unit economics | Feedback loop, retention offers, product mix optimization |

---

# 🧠 Strategic Differentiation

Aapla Kisan is stronger than a basic grocery delivery model because it combines:

- Predictive supply
- Predictive demand
- Farmer/vendor onboarding
- Local collection
- Digital grading
- Dark-store fulfilment
- B2C ordering
- B2B recurring supply
- KPI-based governance

---

# 🏆 Skills Demonstrated

| Skill Area | Demonstrated Through |
|---|---|
| **Business Strategy** | B2C + B2B model, stakeholder mapping, value proposition |
| **Product Strategy** | Multi-sided platform, role-based product layers, MVP thinking |
| **Operations Planning** | Collection, grading, dark store, inventory, dispatch |
| **Go-To-Market Thinking** | Pilot-first rollout, demand validation, buyer segmentation |
| **Supply Chain Thinking** | Procurement, pricing, wastage, fulfilment, supplier reliability |
| **Analytics** | KPI framework, weekly review model, performance tracking |
| **Data Visualization** | Business layer map, demand mix, value stream pie chart, KPI bar chart |

---

# 📝 Public Portfolio Note

This document is a public-safe business model version created for portfolio presentation. Sample chart values are planning assumptions for visualization and should be replaced with verified pilot data after execution.
