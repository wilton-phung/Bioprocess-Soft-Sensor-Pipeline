# Bioprocess Soft Sensor Pipeline

End-to-end data engineering and machine learning workflow for soft sensor development in bioprocessing, with applications to process monitoring and digital twins.

---

## Overview

Modern bioprocesses generate large volumes of high-frequency online sensor data (e.g., pH, dissolved oxygen, temperature), while critical quality attributes (CQAs) such as product titer are often measured offline with significant delays. This mismatch limits the ability of engineers to monitor, control, and optimize processes in real time.

This project demonstrates how raw bioprocess data can be transformed into modeling-ready datasets for **soft sensors**—inferential models that estimate unmeasured or infrequently measured variables using readily available process signals.

Rather than emphasizing model novelty, the focus is placed on the **data engineering and preprocessing challenges** that dominate real-world machine learning efforts in Process Development (PD), Manufacturing Science & Technology (MSAT), and digital twin applications.

---

## Project Structure

The repository is organized into a small set of focused notebooks, each serving a distinct role in the overall workflow:

- **📘 `00_preface_and_context.ipynb`**  
  Introduces the biological, business, and machine learning context for soft sensor development in bioprocessing.

- **🛠️ `01_data_engineering_pipeline.ipynb`**  
  Exploratory analysis, visualization, and construction of a reproducible data processing pipeline for batch-wise bioprocess data.

- **🤖 `02_soft_sensor_modeling.ipynb`**  
  Application of machine learning models to the processed data, with discussion of soft sensor deployment and digital twin integration.

Readers primarily interested in implementation may proceed directly to the data engineering notebook. Readers seeking motivation and context are encouraged to begin with the preface.

---

## Key Topics Covered

- Batch-wise time-series data handling  
- Exploratory data analysis (EDA) and visualization  
- Data quality assessment and preprocessing  
- Process vs analytical (PAT) data separation  
- Soft sensor formulation and assumptions  
- Connections to digital twin workflows  

---

## Data Source

This project uses **IndPenSim**, a synthetic industrial penicillin fermentation simulator commonly used for academic research and education. The simulator generates realistic batch bioprocess data, including process variables, analytical measurements, and product titer, while avoiding the confidentiality constraints associated with proprietary industrial datasets.

The IndPenSim simulator and example datasets are available at:

- https://github.com/act-ehu/indpensim

### Citation

If using IndPenSim data, please cite the original work:

> Goldrick, S., Zamamiri, A., McAuley, K. B., & Doyle, F. J. (2015).  
> *A novel soft sensor design for batch processes using Just-in-Time learning.*  
> **Journal of Process Control**, 33, 1–13.

Raw data files are **not included** in this repository. Users are expected to generate or download the dataset independently.

---

## Intended Audience

- Process Development (PD) engineers  
- Manufacturing Science & Technology (MSAT) teams  
- Bioprocess and biochemical engineers  
- Data scientists working in regulated manufacturing environments  
- Students learning applied machine learning in biopharma  

---

## Author

**Wilton Phung**  
M.Eng. Biopharmaceutical Processing  
Keck Graduate Institute
