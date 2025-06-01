# <span style="color:#007ACC">iStockView - Power BI Inventory Template</span>

**iStockView** คือ Template สำหรับวิเคราะห์ทุนจมสินค้าในคลัง (Inventory) ด้วย Power BI  
ครอบคลุมการวิเคราะห์ ABC/FSN, Dead Stock, Turnover, DOI และคำแนะนำการเคลียร์ทุนจมอัตโนมัติผ่าน DAX

---

## <span style="color:#28a745">✅ คุณสมบัติเด่น</span>
- **Dashboard Overview:** สรุปทุนจม, turnover, และสินค้าควรเคลียร์  
- **ABC + FSN Matrix:** จัดกลุ่มสินค้าตามมูลค่าและความเคลื่อนไหว  
- **Turnover / DOI Analysis:** วิเคราะห์ความถี่การหมุนเวียนและวันที่ถือครอง  
- **Dead/Slow Stock:** รายการสินค้าที่ควรเคลียร์ ลดทุนจม  
- **Action Summary:** แสดงแผนเคลียร์ทุนจมแบบอัตโนมัติ  

---

## <span style="color:#17a2b8">📊 DAX Logic ที่ใช้</span>
- `DeadStockFlag`: ระบุสินค้าที่ DOI เกิน 365 วัน  
- `TurnoverCategory`: แบ่งระดับหมุนเวียนของสินค้า  
- `StockRecommendation`: ให้คำแนะนำ เช่น "เคลียร์ด่วน", "ระบาย"  
- `StuckCapital`: มูลค่าทุนจมต่อสินค้า  

---

## <span style="color:#6f42c1">🧩 เหมาะสำหรับใคร?</span>
- ฝ่ายวางแผนคลังสินค้า (Inventory)  
- ฝ่ายจัดซื้อ / จัดการวัสดุ (Procurement)  
- ธุรกิจที่ต้องการลดทุนจมและ optimize stock  

---

## <span style="color:#17a2b8">🚀 วิธีใช้งาน (สำหรับผู้ใช้ทั่วไป)</span>
1. เปิดไฟล์ `iStockView.pbix` ด้วยโปรแกรม Power BI Desktop  
2. นำเข้าข้อมูลสินค้าคงคลังจาก Excel หรือฐานข้อมูลของคุณ  
3. Dashboard จะประมวลผลและแสดงผลการวิเคราะห์ให้อัตโนมัติ  
4. พร้อมใช้งานเพื่อวางแผนลดทุนจมได้ทันที  

---

## <span style="color:#ffc107">📬 ติดต่อ</span>
📧 benjaja60@gmail.com  

---

© 2025 iStockView. All rights reserved.
