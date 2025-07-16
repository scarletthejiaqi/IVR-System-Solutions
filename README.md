# IVR System Solutions – BZJ Datathon 2024

This repository presents the solution developed for the **BZJ IVR System Optimization Datathon** by team members Brian Eide, Zhehong Lim, and Jiaqi(Scarlett) He. The project aims to improve customer experience and operational efficiency by analyzing call center data and suggesting targeted improvements to the IVR (Interactive Voice Response) system.

## 🧠 Problem Context

The client company is facing a high volume of unresolved calls routed to human agents ("floor"). This project investigates key reasons behind inefficient call resolution and proposes practical IVR enhancements to reduce load and improve user satisfaction.

## 📊 Main Analyses

### 1. Retailer Investigation

* Identified **Retailer 's'** as a key outlier with a disproportionately high number of unresolved cases.
* Suggested targeted investigation into Retailer 's' processes, especially for **IA-related** and **non-IA** escalations.

### 2. Repeat Callers

* Detected cases where customers made **excessive repeat calls** (e.g., 30+ times in 4 days).
* Many repeat calls involved simple issues that could be resolved by self-service or clearer IVR flows.

## 💡 Recommendations

### Suggestion 1: Add a Payment Section to IVR

* **Reason**: Many payment-related calls (PP and PT) are redirected inefficiently.
* **Impact**:

  * Reduced number of customer actions
  * Faster resolution
  * Improved cash flow and data collection

### Suggestion 2: Add Complaint Channels or Redirect in IVR

* **Reason**: "Change in terms" complaints always go to transfer, missing self-service potential.
* **Recommendation**: Offer choices like online or SMS complaint submission via IVR.
* **Impact**:

  * 24/7 availability
  * Lower agent load (\~3% cost reduction)
  * Streamlined and more accessible complaint process

## 📁 Files

* `Jiaqi_code.ipynb`: Retailer-level analysis, case resolution flow logic.
* `Jiaqi_code2.ipynb`: Repeat caller detection, IVR structure recommendation.
* `Datathon Solution Slides.pdf`: Presentation summarizing findings and recommendations.

## 🔧 Technologies

* Python (Pandas, NumPy, Matplotlib)
* Jupyter Notebooks
* Data visualization and EDA
* Business analytics

## 🚀 Future Work

* A/B test new IVR changes for measurable KPIs
* Use NLP to parse call transcripts for root-cause classification
* Expand IVR branching logic with customer segmentation
