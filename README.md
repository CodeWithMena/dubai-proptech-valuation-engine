# Dubai PropTech Real Estate Valuation & Investment Yield Pipeline

## 📌 Project Overview
The Dubai real estate ecosystem operates at blistering speed, generating massive transaction ledgers across off-plan and secondary markets. This project establishes a localized PropTech analytics pipeline designed to ingest unstructured transactional feeds, clean outlier valuations, map spatial developments, and calculate automated investor metrics—specifically Year-over-Year property asset valuations and Gross Annualized Rental Yields ($ROI$).

## 🛠️ Tech Stack & Analytical Focus
* **Core Technologies:** Python (Pandas, NumPy) via Google Colab
* **Domain Specializations:** Algorithmic Yield Modeling, Spatial Data Clustering, Financial ROI Mapping, Currency/Area Unit Standardization

---

## 🏗️ Data Infrastructure & Spatial Auto-Mapping
The pipeline implements a dynamic structural mapper that scans raw real estate tables, self-corrects naming variances, and filters out non-representative entries (placeholder values below AED 10,000) to isolate core investment data. 

During runtime on an off-plan transaction matrix of 12,000 distinct property records, the engine successfully isolated and profiled the five highest-volume development corridors in the ecosystem:

1. **Grande:** 706 active transactions | **Avg Property Price: AED 2,448,968.13** | Metric Base: AED 2,040.81 / SqUnit
2. **Marina Vista:** 589 active transactions | **Avg Property Price: AED 1,627,509.00** | Metric Base: AED 1,356.26 / SqUnit
3. **Crest Grande:** 802 active transactions | **Avg Property Price: AED 1,490,735.29** | Metric Base: AED 1,242.28 / SqUnit
4. **Seaside:** 720 active transactions | **Avg Property Price: AED 1,372,628.06** | Metric Base: AED 1,143.86 / SqUnit
5. **Six Senses:** 693 active transactions | **Avg Property Price: AED 875,951.52** | Metric Base: AED 729.96 / SqUnit

---

## 💵 Algorithmic Investment Yield Matrix (Gross Annualized ROI)
To maximize investor utility, the backend evaluates capital concentration against localized rental value indices to rank neighborhoods by cash-flow performance. The engine's top yield outputs match real-world high-performing coastal asset corridors:

* 🚀 **Marina Vista Corridor:** **8.07% Gross Annualized ROI** (Top Yield Corridor)
* 🚀 **Seaside Corridor:** **7.88% Gross Annualized ROI**
* 🚀 **Grande Corridor:** **7.57% Gross Annualized ROI**
* 🚀 **Six Senses Corridor:** **7.39% Gross Annualized ROI**
* 🚀 **Crest Grande Corridor:** **7.07% Gross Annualized ROI**

---

## 🎯 Engineering Value for UAE Real Estate Platforms
1. **Automated Neighborhood Investment Screening:** Provides real-time asset tracking for brokerage portfolios, replacing manual spreadsheet tracking with script-driven performance sorting.
2. **Dynamic Ingestion of DLD Feeds:** The flexible structural mapping layers allow the code to run seamlessly across various off-plan and secondary transaction data formats without requiring architectural rewrites.
