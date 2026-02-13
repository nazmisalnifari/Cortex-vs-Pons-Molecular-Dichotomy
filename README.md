# 🧠 Transcriptomic Divergence: Cortex vs. Pons

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Platform-GPL6104-blue?style=for-the-badge)
![Study](https://img.shields.io/badge/Study-Differential_Expression-orange?style=for-the-badge)

> **"Deciphering the molecular machinery that differentiates the 'Thinking Brain' (Frontal Cortex) from the 'Surviving Brain' (Pons)."**

## 📌 Project Overview
This repository hosts the documentation for a differential gene expression (DEG) analysis comparing two functionally distinct human brain regions: the **Frontal Cortex** (Executive function) and the **Pons** (Vegetative function).

* **Dataset:** [GSE15745](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE15745)
* **Platform:** GPL6104 (Illumina humanRef-8 v2.0)
* **Design:** Multi-tiered replication (General, Male-specific, Female-specific).

---

## 📂 Data Availability & Full Report

### 1️⃣ Full Research Report (PDF)
For detailed biological interpretation and methodology, please refer to the full report:
👉 [**READ FULL REPORT (PDF)**](91_Nazmi%20Soufi%20Alnifari_Week%202.pdf)

### 2️⃣ Raw Data (Excel)
The differential expression data for all three replication scenarios can be accessed here:
👉 [**📂 OPEN DATA FOLDER**](data/)

* `01_General_Replicate.xlsx` (Mixed Sex)
* `02_Validation_Male.xlsx` (Male Only)
* `03_Validation_Female.xlsx` (Female Only)

---

## 📊 Replication Data (Top Differentially Expressed Genes)

### 1️⃣ Primary Analysis: General Replicate (Mixed Sex)
*Objective: To capture the universal, sex-independent regional signature.*
* **Comparison:** Frontal Cortex vs. Pons
* **Sample Size:** **n = 20** (10 Cortex vs 10 Pons)

| Gene Symbol | Region Enriched | Biological Role |
| :--- | :--- | :--- |
| **`CX3CL1`** | **Frontal Cortex** | **Fractalkine** - Critical for neuron-microglia communication and synaptic pruning (Gray Matter signature). |
| **`RGS7BP`** | **Frontal Cortex** | Regulator of G-protein signaling; modulates synaptic transmission efficiency. |
| **`SPP1`** | **Pons** | **Osteopontin** - Key regulator of myelination; reflects the dense "White Matter" architecture of the Pons. |
| **`CRABP1`** | **Pons** | **Retinoic Acid Binding Protein 1** - Defines posterior (Hindbrain) positional identity during development. |

### 2️⃣ Validation: Male-Specific Cohort
* **Age Range:** **18 - 20 Years**
* **Sample Size:** **n = 10** (5 Cortex vs 5 Pons)

| Gene Symbol | LogFC | Region | Interpretation |
| :--- | :--- | :--- | :--- |
| **`PPEF1`** | 2.13 | Cortex | Protein phosphatase with EF-hand domain (Male-specific enrichment). |
| **`PI4KAP2`** | 1.82 | Cortex | Phosphoinositide signaling; suggests specific metabolic requirement in male cortex. |
| **`HEYL`** | -0.70 | Pons | Notch signaling effector; structural development. |
| **`LGALS3BP`** | -0.69 | Pons | Structural/channel protein specific to male dataset. |

### 3️⃣ Validation: Female-Specific Cohort
* **Age Range:** **16 - 29 Years** *(Expanded due to sample availability)*
* **Sample Size:** **n = 10** (5 Cortex vs 5 Pons)

| Gene Symbol | LogFC | Region | Interpretation |
| :--- | :--- | :--- | :--- |
| **`GABRA2`** | 2.13 | Cortex | **GABA Receptor** - Suggests robust inhibitory signaling network in the more mature female cohort. |
| **`OTP`** | -0.95 | Pons | **Orthopedia Homeobox** - Critical developmental gene for hypothalamus/brainstem. |
| **`BAG3`** | -0.58 | Pons | Anti-apoptotic protein involved in protein quality control. |

---

## 🛠️ Methodology & Study Design

The study employed a robust replication strategy to validate findings:

| Parameter | **Replicate 1 (General)** | **Replicate 2 (Male)** | **Replicate 3 (Female)** |
| :--- | :--- | :--- | :--- |
| **Total Sample Size** | **n = 20** | **n = 10** | **n = 10** |
| **Group Dist.** | 10 Cortex vs 10 Pons | 5 Cortex vs 5 Pons | 5 Cortex vs 5 Pons |
| **Age Range** | Mixed | **18 - 20 Years** | **16 - 29 Years** |
| **Control** | Balanced Sex | Sex-Controlled | Age-Expanded* |

*\*Note: The female age range was expanded (16-29) to strictly maintain a balanced sample size (n=5 per group) due to repository limitations.*

---
**Author:** Nazmi Soufi Alnifari  
*OmicsLite - Transcriptomics Course (Week 2 Assignment)* *February 2026*
