# HackerNews Monitoring & Automation System

An automated backend pipeline built to monitor top tech stories from HackerNews, evaluate performance thresholds, and route notifications cleanly to third-party endpoints.

## 📁 Repository Structure
* `Task1_QA_Report_Meenakshi.pdf` - Complete bug-tracking log and infrastructure root-cause analysis (RCA).
* `Task2_Workflow_Meenakshi.json` - Serialized blueprint file for the n8n automation pipeline.

## ⚙️ Workflow Architecture
* **Trigger:** Hourly automated polling cycle.
* **Data Layer:** Interacts dynamically with the HackerNews Firebase REST API.
* **Processing:** Features custom validation script to restrict arrays to 5 targeted records.
* **Error Handler:** Dedicated operational fallback routing to intercept exceptions and prevent silent runtime failures.
