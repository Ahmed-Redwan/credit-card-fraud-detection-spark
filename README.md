# Credit Card Fraud Detection with PySpark

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/132FQEy9cFOBsGpmo35HQeXtIl10aymN7?usp=sharing)

## Project Overview
This repository contains the official implementation of the research paper:  
**"A Comparative Performance Study of Traditional and PySpark-Based Classification Algorithms for Credit Card Fraud Detection with an LLM-Based Reasoning Layer for Explainability"**

**Author:** Ahmed R. B. Abdelghafoor  
**Supervised by:** Dr. Rebhi S. Baraka  
*A requirement for the Big Data Course (ICTS 6339), Faculty of Information Technology, The Islamic University of Gaza (IUG).*

---

## System Architecture & Methodology
The project is executed in two comprehensive phases:
1. **Phase 1 (Comparative Phase):** Benchmarking centralized machine learning (Scikit-Learn) against distributed computing (Apache Spark/PySpark MLlib) across multiple worker nodes to evaluate execution time, speed-up, and F1-Score stability.
2. **Phase 2 (Explainability Layer):** Integrating a GenAI Core Layer (Gemini-2.5-Flash) via LangChain to act as an automated Financial Audit Expert, translating statistical feature anomalies into human-readable fraud justification reports (in both English and Arabic).

## Dataset Reference
The pipeline utilizes the official **Credit Card Fraud Detection Dataset** (284,807 transactions, PCA-transformed features).  
* **Source:** [Kaggle Dataset Repository](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## How to Run on Colab
1. Click the **Open In Colab** badge at the top of this page.
2. Ensure you add your Google Gemini API Key to the environment or enter it when prompted by the runtime interface to enable the Explainability Layer.
3. Run all cells sequentially to observe the distributed processing pipeline and the generated AI advisory reports.
