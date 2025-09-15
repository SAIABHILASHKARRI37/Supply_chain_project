# 📊 Supply Chain Performance Dashboard

## 🎯 Objective
To analyze and improve **supply chain performance** by tracking critical KPIs such as:
- On-Time %
- In-Full %
- OTIF %
- Volume Fill Rate (VFR)
- Line Fill Rate (LFR)

The goal is to provide insights that help management identify at-risk customers, reduce churn, and improve operational efficiency.

---

## 🛠️ What I Have Done
- Collected and structured delivery performance data (customer-level, city-level, overall).
- Built an **interactive Power BI dashboard** with:
  - High-level KPIs (On-Time, In-Full, OTIF, VFR, LFR, Total Orders).
  - **City-wise comparison** (Surat, Ahmedabad, Vadodara).
  - **Customer-level performance table** with On-Time %, In-Full %, OTIF %, LIFR %, VOFR %.
  - **Trend analysis over time** for performance monitoring.
- Applied **conditional formatting** to highlight gaps vs targets.
- Added **drill-down capability** to identify top at-risk customers.

---

## ✅ What I Achieved
- Identified that **OTIF % is critically low (29.4% vs 65.9% target)** → major risk for customer satisfaction and contract renewals.
- Found that while **Volume Fill Rate (96.6%) is strong**, **Line Fill Rate (65.9%) is weak** → customers receive bulk volumes but incomplete assortments.
- Discovered **systemic issues across all cities** (Surat, Ahmedabad, Vadodara) with no city meeting the target.
- Highlighted **at-risk customers** with OTIF <30% who are most likely to churn.

---

## 💡 Recommendations
1. **Customer Rescue Plan**
   - Focus on top 10 high-revenue customers with OTIF <40%.
   - Assign account managers and prioritize their orders.

2. **Process Improvements**
   - Improve **On-Time %** → optimize dispatch scheduling, strengthen logistics partnerships.
   - Improve **In-Full %** → enhance demand forecasting, maintain safety stock for high-demand SKUs.

3. **Pilot & Scale**
   - Start with Surat (slightly higher OTIF) as a pilot location.
   - Replicate improvements in Ahmedabad and Vadodara.

4. **Build Customer Trust**
   - Communicate proactively with customers (alerts for partial shipments, ETAs).
   - Share improvement roadmap with strategic clients.

---

## 🚀 Impact
If implemented, these actions can:
- Improve OTIF by **+15–20% in the next quarter**.
- Reduce customer churn.
- Increase contract renewals and overall business profitability.

---

## 📌 Tools & Technologies
- **Power BI** (dashboard, data modeling, visualization)
- **Excel / CSV** (data input and preprocessing)
- **DAX** (calculated measures and KPIs)

---

## 🔗 Next Steps
I plan to extend this project by:
- Integrating AI/ML for **demand forecasting**.
- Adding **predictive churn models** to identify customers most likely not to renew.
