# Open Community Land & Food

Open-source data architectures and digital infrastructure designed for agroecological stewardship, cooperative governance, and resilient local food economies.

---

## Overview

The **Community Land & Food** project provides open-source systems designed to meet the operational, ecological, and governance needs of land-based communities, agroecological holdings, and regional food networks. 

Conventional agricultural and commercial software often assumes monocultural production, corporate structures, and linear supply chains. This project develops data models and software capable of representing polycultures, permaculture zonation, complex tenure arrangements, and cooperative distribution models with structural integrity.

---

## Three-Tier Architecture

The platform architecture is structured across three foundational tiers:

```text
┌────────────────────────────────────────────────────────┐
│  Tier 3: Federated Knowledge Pool                      │
│  Multi-organisation graph model for regional insights, │
│  agroecological benchmarking, and recommendations.     │
└───────────────────────────▲────────────────────────────┘
                            │ (Federated sync)
┌───────────────────────────┴────────────────────────────┐
│  Tier 2: Holding Digital Twin                          │
│  Secure, holding-level graph model representing spatial│
│  relationships, material flows, and ecological state.  │
└───────────────────────────▲────────────────────────────┘
                            │ (Deterministic sync)
┌───────────────────────────┴────────────────────────────┐
│  Tier 1: Relational Data Architecture (Active)         │
│  PostgreSQL system of record managing transactional    │
│  operations, tenure, people, production, and metrics.  │
└────────────────────────────────────────────────────────┘

```

* **Tier 1 (Local Operational Application):** A 20-schema PostgreSQL transactional database providing the operational system of record for individual holdings and community initiatives.
* **Tier 2 (Holding Graph Digital Twin):** A graph model providing an expressive digital twin of each holding’s spatial entities, living assets, and operational workflows.
* **Tier 3 (Federated Knowledge Pool):** A privacy-preserving, federated graph pool aggregating shared ecological metrics, benchmarking, and collaborative intelligence across participating holdings.

---

## Repositories & Current Work

* **[`tier1-relational-model`](https://www.google.com/search?q=https://github.com/community-land-food/tier1-relational-model):** Master pgModeler data architecture, automated data dictionary build pipeline, and relational architectural decision records (ADRs). *(Active development)*

---

## Architectural Commitments

* **Open Standards & Interoperability:** Grounded in normalised relational foundations and extensible Entity-Attribute-Value (EAV) dynamic observation engines.
* **Agroecological Realism:** Native schema support for intercropping mixtures, biological succession, holistic grazing rotations, and multi-layered agroforestry.
* **Decentralised Sovereignty:** Data sovereignty remains rooted at the holding level, with opt-in federated pooling for community intelligence.
