# Synthea Cancer Cohort Analysis

This project reconstructs **patient journeys for cancer patients** using synthetic EHR data generated from [Synthea](https://synthetichealth.github.io/synthea/). The goal is to modernize the traditional SQL-based workflow for patient journey analytics with reproducible **Python + ML/AI pipelines**.

## Objectives
- Filter and define a cancer patient cohort from synthetic EHR data  
- Identify and categorize **oncology drugs and procedures**  
- Reconstruct **regimens** by grouping therapies in clinical windows  
- Define and track **Lines of Therapy (LoT)** using clinically informed rules  
- Generate patient-level and line-level outputs for downstream ML/AI exploration  

## Why this project?
In pharma analytics, understanding the **sequence of treatments** patients receive is critical for market research, real-world evidence, and strategy. Traditionally this has been done with **SQL and manual rules**. This project demonstrates how the same process can be:
- **Automated** with Python  
- **Flexible** through configuration tables (drug/procedure mappings)  
- **Extensible** with ML/AI (e.g., clustering journeys, LLM summarization)  

## Repo Structure
