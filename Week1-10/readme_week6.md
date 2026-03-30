# WEEK 6 – MANET (Ad-Hoc Networking)

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. แก้ไข config.py (HOST, BASE_PORT, NEIGHBORS, FORWARD_PROBABILITY, TTL, BUFFER_SIZE)
2. เปิด node หลาย Terminal: python node.py (แต่ละ node ใช้ BASE_PORT ต่างกัน)
3. สังเกตการส่งต่อ message ระหว่าง node
<img width="1544" height="557" alt="image" src="https://github.com/user-attachments/assets/ed3f97b0-488a-406e-bdbe-85ee3a91c7fc" />

---

## อธิบาย
- ไม่มีโครงสร้างถาวร
- node ค้นหา neighbor เอง ส่งต่อแบบสุ่ม
