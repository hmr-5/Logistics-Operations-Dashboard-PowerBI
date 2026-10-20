 🚚 Logistics Operations & Fleet Management Dashboard
لوحة قيادة العمليات اللوجستية وإدارة الأسطول

An interactive, data-driven Power BI dashboard designed to monitor and optimize logistics operations, track financial performance, and evaluate driver and fleet efficiency.

لوحة قيادة تفاعلية مدعومة بالبيانات ومصممة في Power BI لمراقبة وتحسين العمليات اللوجستية، تتبع الأداء المالي، وتقييم كفاءة السائقين وأسطول المركبات.

---

 📌 Project Overview | نظرة عامة على المشروع
This project simulates a complete end-to-end data analysis workflow for a logistics company. It covers data cleaning, relational modeling, advanced DAX measures, and UI/UX report design to support data-driven decision-making in operations management.

يحاكي هذا المشروع دورة عمل كاملة لتحليل البيانات لشركة لوجستية؛ بدءاً من تنظيف البيانات وهيكلتها، مروراً بنمذجة العلاقات، وكتابة مقاييس الـ DAX المتقدمة، وصولاً إلى تصميم واجهة مستخدم احترافية تدعم اتخاذ القرار الإداري.

---

 🏗️ Data Architecture & Modeling | هندسة ونمذجة البيانات
- **Star Schema Design:** Built a robust star schema connecting 6 core tables:
  * **Shipments (الشحنات):** Transactional data of deliveries, weights, and distances.
  * **Branches (الفرع):** Branch locations and regional mapping.
  * **Drivers (السائقين):** Driver profiles and operational mapping.
  * **Vehicles (المركبات):** Fleet inventory and types.
  * **Maintenance (الصيانة):** Tracking repair logs and operational costs.
  * **Customers (العملاء):** Client database and tracking.
- **Data Transformation:** Cleaned, formatted, and transformed raw data using **Power Query**.

---

 📊 Key Performance Indicators (KPIs) & DAX Measures | المؤشرات الرئيسية ومقاييس DAX
The dashboard tracks the following core business metrics using custom DAX formulas:
تتتبع اللوحة المؤشرات الأساسية التالية باستخدام معادلات DAX مخصصة:

1. **Total Revenue (إجمالي الإيرادات):** Calculated from shipment service fees.
2. **Total Operational Cost (إجمالي تكاليف التشغيل):** Sum of fuel and maintenance expenses.
3. **Net Profit (صافي الأرباح التشغيلية):** `Net Profit = [إجمالي الإيرادات] - [إجمالي تكاليف التشغيل]`
4. **Delayed Shipments Count (عدد الشحنات المتأخرة):** `CALCULATE([إجمالي الشحنات], 'الشحنات'[حالة الشحنة] = "متأخرة")`
5. **Delayed Rate (نسبة الشحنات المتأخرة):** `DIVIDE([Delayed Shipments], [إجمالي الشحنات], 0)`

---

 🖥️ Dashboard Features & Visuals | مميزات وعناصر لوحة القيادة
- **KPI Strip (شريط المؤشرات العلوي):** High-level summary of Revenue, Costs, Profit, Volume, and Delay %.
- **Branch Performance:** Clustered bar chart comparing revenue generation across branches.
- **Regional Distribution:** Donut chart breaking down shipment volume by region.
- **Fleet Readiness:** Column chart tracking vehicle types and operational statuses.
- **Driver Performance Table:** Detailed breakdown of individual driver delivery volumes and delay rates.
- **Interactive Slicers:** Dynamic filters for Branch, Date Range, and Shipment Status.

---

 🛠️ Tools & Technologies | الأدوات والتقنيات المستخدمة
- **Power BI Desktop:** Data modeling, DAX calculations, and visual design.
- **Power Query:** Data cleaning, transformation, and ETL processes.
- **Git & GitHub:** Version control and bilingual project documentation.

---

## 👤 Author | إعداد وتطوير
- **Haneen Al-rddadi (حنين الردادي)**
- Administrative Support & Operations Coordination Specialist | Data Analyst
