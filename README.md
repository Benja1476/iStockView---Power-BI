# iStockView - Power BI Inventory Template

**iStockView** คือ Template สำหรับวิเคราะห์ทุนจมสินค้าในคลัง (Inventory) ด้วย Power BI  
ครอบคลุมการวิเคราะห์ ABC/FSN, Dead Stock, Turnover, DOI และคำแนะนำการเคลียร์ทุนจมอัตโนมัติผ่าน DAX

## ✅ คุณสมบัติเด่น
- **Dashboard Overview:** สรุปทุนจม, turnover, และสินค้าควรเคลียร์
- **ABC + FSN Matrix:** จัดกลุ่มสินค้าตามมูลค่าและความเคลื่อนไหว
- **Turnover / DOI Analysis:** วิเคราะห์ความถี่การหมุนเวียนและวันที่ถือครอง
- **Dead/Slow Stock:** รายการสินค้าที่ควรเคลียร์ ลดทุนจม
- **Action Summary:** แสดงแผนเคลียร์ทุนจมแบบอัตโนมัติ

## 📊 DAX Logic ที่ใช้
- `DeadStockFlag`: ระบุสินค้าที่ DOI เกิน 365 วัน
- `TurnoverCategory`: แบ่งระดับหมุนเวียนของสินค้า
- `StockRecommendation`: ให้คำแนะนำ เช่น "เคลียร์ด่วน", "ระบาย"
- `StuckCapital`: มูลค่าทุนจมต่อสินค้า

## 🧩 เหมาะสำหรับใคร?
- ฝ่ายวางแผนคลังสินค้า (Inventory)
- ฝ่ายจัดซื้อ / จัดการวัสดุ (Procurement)
- ธุรกิจที่ต้องการลดทุนจมและ optimize stock

## 🚀 วิธีใช้งาน
1. เปิด `index.html` เพื่อนำไปแสดง Landing Page
2. เปิดเทมเพลต `.pbix` (ไม่รวมใน repo นี้) ด้วย Power BI Desktop
3. นำ Template ไปปรับใช้กับข้อมูลขององค์กรคุณ

## 📬 ติดต่อ
📧 benjaja60@gmail.com  
🌐 [iStockView Landing Page](./index.html)

---

© 2025 iStockView. All rights reserved.
