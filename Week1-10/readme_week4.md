# WEEK 4 – UDP Multicast Communication

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. แก้ไข config.py (MULTICAST_GROUP, PORT, BUFFER_SIZE, TTL)
2. เปิด Receiver หลาย Terminal: python receiver.py
3. เปิด Sender: python sender.py

---

## อธิบาย
- Multicast ส่งถึงเฉพาะกลุ่มที่ join เท่านั้น
- จำกัดขอบเขตด้วย TTL
