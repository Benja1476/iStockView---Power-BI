# 🚀 iStockView: Strategic Inventory Intelligence System (Power BI Project)

> A comprehensive Power BI project to drive **data-led inventory decisions** through smart segmentation, actionable insights, and DAX-powered analysis.  
>  
> ระบบวิเคราะห์สินค้าคงคลังเชิงกลยุทธ์ด้วย Power BI เพื่อช่วยให้ผู้ใช้งานสามารถ **วางแผนได้แม่นยำ ลดทุนจม ตัดสินใจได้เร็วขึ้น**

---

## 🧾 Project Purpose | จุดประสงค์ของโปรเจกต์

- ลดทุนจมจากสินค้าที่ไม่มีการเคลื่อนไหวหรือล้นสต็อก  
- เพิ่มความแม่นยำในการวางแผนจัดซื้อและการพยากรณ์ยอดใช้  
- ลดการทำงานซ้ำซ้อนและการวิเคราะห์แบบแมนนวลจาก Excel  
- ใช้ข้อมูลเพื่อสนับสนุนการตัดสินใจ (Data-Driven Decisions)  

> The purpose is to turn raw inventory data into **strategic actions**, helping teams proactively manage stock, detect risks early, and improve forecast quality.

---

## 🎯 Project Goals | เป้าหมายของโปรเจกต์

1. สร้างแดชบอร์ดที่ใช้งานง่าย และสามารถปรับให้เหมาะสมตามองค์กร  
2. สร้างระบบวิเคราะห์สินค้าคงคลังในมิติต่าง ๆ เช่น DOI, Forecast, Cost  
3. นำ DAX มาประยุกต์ใช้อย่างมีระบบแบบ Modular  
4. สร้างระบบแจ้งเตือนและคำแนะนำในเชิง Prescriptive Analytics  

> This project is designed to empower users to make **fast, reliable, and proactive inventory decisions** using a structured Power BI environment.

---

## 🧠 Design Concepts | แนวคิดหลักของระบบ

- **Modular DAX Engine**: เขียนสูตรแบบแยกโมดูลเพื่อความยืดหยุ่น  
- **Actionable Visuals**: ใช้ไอคอน สี และคอลัมน์คะแนนเพื่อสื่อสารความเสี่ยง  
- **Segmentation + Risk Modeling**: ผสาน ABC-FSN Matrix กับ DOI/Cost Scoring  
- **Forecast Feedback Loop**: นำผลต่างของยอดจริงกับยอดพยากรณ์กลับไปปรับปรุงแผน  

> iStockView is built not only to display metrics—but to **suggest actions** and guide users to what matters most.

---

## ⚙️ Key Functionalities | ฟังก์ชันเด่นในระบบ

| # | Module               | Functionality                              |
|---|----------------------|--------------------------------------------|
| 1 | Segmentation Matrix  | แบ่งกลุ่มสินค้า ABC × FSN เพื่อวางแผนตามความสำคัญ     |
| 2 | DOI Analysis         | วิเคราะห์วันคงคลังย้อนหลังตาม SKU                |
| 3 | Forecast Accuracy    | วัดความแม่นยำของยอดพยากรณ์ย้อนหลัง              |
| 4 | Risk Scoring Model   | คำนวณคะแนนความเสี่ยงจากหลายปัจจัยรวมกัน            |
| 5 | Opportunity Cost Flag| ตั้งธงเตือนสินค้าเสี่ยงทุนจม (Dead, Slow, Risk)       |
| 6 | Prescriptive Icon Flag| สร้างไอคอน 💀 🐢 ⚠️ ✅ เพื่อสะท้อนสถานะสินค้าแบบเรียลไทม์ |

---

## 🔬 Core DAX Functions | รายละเอียดสูตรหลัก DAX

| Function               | Description                        |
|------------------------|----------------------------------|
| `CalcDOITrend`         | คำนวณแนวโน้มของ Days of Inventory (DOI) |
| `AddForecastAccuracy`  | คำนวณความแม่นยำของการพยากรณ์ราย SKU     |
| `AddWeightedScore`     | รวมปัจจัยด้าน Cost, DOI, Accuracy เป็น Risk Score |
| `AddOpportunityCostFlag`| ตั้งธงเตือนสินค้าเสี่ยงทุนจม (Dead, Slow, Risk) |

> These DAX functions feed into the `InsightSummaryTable`, the brain of the system.

---

## 📊 Visualization Design | การออกแบบการแสดงผล

- **KPI Cards**: สถานะทุนจม, % Forecast Miss, สินค้าเสี่ยงสูง  
- **Matrix Table**: รายการสินค้าพร้อม Flag และคะแนน  
- **Interactive Graphs**: DOI Report, Forecast vs Actual, Trend Analysis  

---

## 🧰 Tools & Tech Stack | เครื่องมือที่ใช้

| Tool         | Purpose                               |
|--------------|-------------------------------------|
| Power BI     | สร้าง Dashboard และ Interactive Visual |
| Power Query  | เตรียมและแปลงข้อมูลเบื้องต้น              |
| DAX          | สร้างสูตรวิเคราะห์และระบบแจ้งเตือน           |
| GitHub       | จัดเก็บและควบคุมเวอร์ชันของโค้ด             |
| DAX Studio   | ปรับจูนประสิทธิภาพสูตร DAX                  |

---

## 🗂 Folder Structure | โครงสร้างโปรเจกต์

