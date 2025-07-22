# 📊 Telco Customer Churn Insight

*Why do customers leave, and what can we learn before they do?*

>This project explores customer churn behavior in a telecom company using Python and visualized insights via Looker Studio. Instead of building a machine learning model, I focused on finding **meaningful business insights** through clean EDA and a concise dashboard.

🔗Dashboard: https://lookerstudio.google.com/reporting/40eb37e0-6739-4507-8496-f2facf91e6c1

---

## 🛠️ Tools Used

- `Python` (Pandas, Seaborn, Matplotlib)
- `Jupyter Notebook`
- `Looker Studio` for dashboard

---

## 📄 Dataset Overview

- Rows: `7,043`
- Clean: ✅ No missing values
- Target column: `Churn` (Yes / No)

Key features include:
- Customer demographics (`gender`, `SeniorCitizen`, etc.)
- Subscription details (`Contract`, `InternetService`, `tenure`)
- Billing (`MonthlyCharges`, `TotalCharges`)

---

## 🔎 Key EDA Findings

```text
1. Month-to-month contract customers have the highest churn rate (~42.7%)
2. Most churn happens within the first 0–2 months of joining
3. Fiber optic users tend to churn more than DSL users
4. Senior citizens show higher churn rates
5. Customers with monthly charges > $90 are more likely to churn

