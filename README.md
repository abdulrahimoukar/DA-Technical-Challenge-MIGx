# DA-Technical-Challenge-MIGx

# MIGx Technical Challenge

This repository contains the solution for the MIGx Technical Challenge. All analysis, SQL queries, visualizations, and documentation are integrated within the notebook.

## 📂 Project Structure
* COVID_19_Clinical_Trials.ipynb: Main notebook containing the Exploratory Data Analysis (EDA), SQL analysis, and statistical findings.
* COVID.csv: The clinical trial dataset used for this challenge.

## 🚀 How to Run
1. Open COVID_19_Clinical_Trials.ipynb in Google Colab (recommended) or Jupyter.
2. Upload the COVID.csv file to the workspace.
3. Run all cells to view the analysis and interactive visualizations.

## 📝 Bonus Questions

**1. Stakeholder Communication:** For executives, I would focus only on high-level charts and final KPIs to support quick strategic decisions. For operations managers, I would provide both the results and the "how-to".

**2. Data Quality at Scale:** I would implement automated checks to ensure ID uniqueness, flag missing critical values (nulls), and verify that dates are logically consistent (e.g., start date before completion). I would also add alerts for unusual changes in data volume during daily updates

**3. Self-Service Analytics:** I would build a user-friendly dashboard in a BI tool with clean, non-technical column names and easy drop-down filters so they can get their own answers without needing to write SQL or code.

**4. Compliance Considerations:** I would need to further review the specific regulatory implications, but I would focus on having everything perfectly documented, keeping a history of every change made to the code, and making sure there is a clear "trail" to prove the results are accurate and haven't been messed with.

**5. Advanced Analytics:** I would need to conduct a more in-depth review of the "outcomes" column to fully understand its specific information but probably I could implement a Random Forest model to predict success or failure.

---
Technical decisions, SQL query logic, and data storytelling narrative are detailed throughout the notebook cells to provide context for the results.
