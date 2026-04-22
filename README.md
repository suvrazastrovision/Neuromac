# 🧠 Neuromac: SVZ Neuroimmune Interaction Mapping

> Translating single-cell neurobiology into therapeutic insights

---

## 🔬 Overview
After a stroke, the neurogenic response from the subventricular zone (SVZ) to repair the brain is limited. Microglia, as an integral part of the distinctive SVZ microenvironment, control neural stem / precursor cell (NSPC) behavior. Here, we show that discrete stroke-associated SVZ microglial clusters negatively impact the innate neurogenic response, and we propose a repository of relevant microglia–NSPC ligand–receptor pairs. After photothrombosis, a mouse model of ischemic stroke, the altered SVZ niche environment leads to immediate activation of microglia in the niche and an abnormal neurogenic response, with cell-cycle arrest of neural stem cells and neuroblast cell death. Pharmacological restoration of the niche environment increases the SVZ-derived neurogenic repair and microglial depletion increases the formation and survival of newborn neuroblasts in the SVZ. Therefore, we propose that altered cross-communication between microglial subclusters and NSPCs regulates the extent of the innate neurogenic repair response in the SVZ after stroke.

---

## 📄 Associated Publication
📰 *Nature Communications (2024)*  
👉 https://www.nature.com/articles/s41467-024-53217-1

---

## 🧑‍🔬 My Contribution
- Designed and executed single-cell RNA-seq analysis pipeline  
- Performed clustering and annotation of SVZ cell populations  
- Characterized microglial states and NPSC subtypes  
- Conducted differential gene expression analysis  
- Mapped ligand–receptor interactions driving NPSC–microglia crosstalk  
- Integrated external datasets for validation and robustness  
- Identified enriched pathways linked to neuroinflammation and regeneration  

---

## 🧠 Key Biological Impact
The SVZ niche is a dynamic microenvironment where neural stem cells and microglia engage in bidirectional signaling. This analysis uncovers key molecular interactions that may be leveraged to modulate neurogenesis and develop therapeutic strategies for neurological disorders.

---

## ⚙️ Analysis Pipeline

```mermaid
graph TD
A[Raw scRNA-seq Data] --> B[QC & Filtering]
B --> C[Normalization]
C --> D[Clustering]
D --> E[Cell Type Annotation]
E --> F[Differential Expression]
F --> G[Ligand-Receptor Analysis]
G --> H[Pathway Enrichment]
H --> I[Drug Target Insights]
