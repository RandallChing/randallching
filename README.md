# Hi, I'm Randall Ching 👋

I operate at the intersection of computer science, public health, and K-12 education. I build simple, secure, and low-maintenance digital tools to solve operational bottlenecks in under-resourced public settings.

*I transitioned from biology to computer science because my time in public health non-profit spaces showed me that high-maintenance software is the single biggest bottleneck for non-profit operations. I use my technical background to bridge this gap, focusing on tools that staff on the ground can own long-term.*

---

## Core Projects

These projects serve as the direct evidence for the technical solutions documented in my fellowship application:

### 1. [teen-health-screener](https://github.com/randallching/teen-health-screener) (HTML/JS, Google Apps Script)
*   **The Focus:** A client-side screening app (handling PHQ-9, GAD-7, and C-SSRS protocols) served standalone via Google Apps Script. 
*   **The Constraint:** Explicitly engineered to run on shared clinic iPads with zero server maintenance overhead, zero hosting budgets, and no backend database. It outputs structured, standardized screening results optimized to match Epic EHR documentation schemas, allowing nurses to rapidly verify and log data with zero formatting friction.
*   👉 *[Click here for the Live Demo](https://randallching.github.io/teen-health-screener/)*

### 2. [csv-validation-pipeline](https://github.com/randallching/csv-validation-pipeline) (Python, Google Apps Script)
*   **The Focus:** A data integrity verification script standardized for clinical chart audits.
*   **The Constraint:** Clinical charts must adhere to strict, standardized regulatory rules. This script bridges data auditing with human workflow optimization through a two-part automated pipeline:
    *   **The Audit Engine (Python):** Automatically scans clinical chart csv exports, identifies validation anomalies, and isolates flagged records.
    *   **The Notification System (Google Apps Script):** Packages the flagged errors into clean, chronologically sorted, and highly scannable email tables sent directly to staff. Every notification uses standardized, jargon-free messaging so nurses instantly understand exactly why a record was flagged.
    *   **Workflow Alignment:** Built around the actual data-entry habits of school nurses. Shifting the automated validation triggers to Tuesday mornings allowed nurses to fix previous week's entries on Monday afternoon. This simple operational adjustment eliminated false alarms and drove down weekly charting errors by 60% YoY.

---

## My Operational Philosophy

*   **Constraint-First Engineering:** Prioritizing lightweight, durable solutions that fit within the host organization's existing licensing and hardware constraints.
*   **Operational Humility:** Shadowing operators in their physical work environments to map their daily workflow before writing any code.
*   **Designed for Departure:** Building code, runbooks, and file structures specifically so that non-technical staff can confidently maintain the tools after my deployment ends.
