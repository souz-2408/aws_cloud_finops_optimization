# ☁️ AWS Enterprise Cloud Cost Optimization & FinOps Governance Strategy

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![AWS](https://img.shields.io/badge/AWS_Cost_Management-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Draw.io](https://img.shields.io/badge/Draw.io-F08705?style=for-the-badge&logo=diagramsdotnet&logoColor=white)

## 📌 Executive Summary
An enterprise Cloud Financial Operations (FinOps) project analyzing **$36.90K** in baseline AWS expenditure across **5,000 allocation records**. The analysis identified key cost drivers across departments and mapped out a **TO-BE Resource Governance Workflow** in Draw.io to prevent non-production budget leakage.

---

## 💡 Key Business Findings

* **Baseline Spend:** Monthly enterprise expenditure totaled **$36.90K**.
* **Top Cost Driver:** The **Data Science** department represents the highest cloud spend, primarily driven by persistent **Amazon RDS** database deployments.
* **Non-Production Cost Leakage:** **$9,054.76** is spent on non-production environments (Staging & Development) that run 24/7 without automated off-hour shutdowns.

---

## 🚀 Strategic Recommendations & Financial Impact

1. **Automated Weekend Shutdowns:** Enforce off-hour auto-shutdown policies for Staging/Dev instances, projecting a **15–20% reduction** in non-production expenditure.
2. **Mandatory Tagging Policy:** Enforce cost-allocation tags (`Department`, `Environment`, `Owner`) at instance launch to maintain 100% visibility in Power BI.
3. **Database Reserved Instances:** Transition baseline production RDS instances in Data Science to 1-Year Reserved Instances for up to **30% cost savings**.

---

## 📂 Repository Deliverables
* `aws_enterprise_billing_5k.csv`: Synthetic multi-department billing dataset.
* `AWS_FinOps_Dashboard.pbix`: Interactive Power BI dashboard file.
* `aws_finops_governance_workflow.png`: 3-lane Draw.io process flowchart.
* `FinOps_Strategy_Memo.docx`: Executive brief outlining governance findings.
