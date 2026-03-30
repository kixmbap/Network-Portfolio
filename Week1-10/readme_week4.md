# WEEK 4 – UDP Multicast Communication

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. แก้ไข config.py (MULTICAST_GROUP, PORT, BUFFER_SIZE, TTL)
2. เปิด Receiver หลาย Terminal: python receiver.py
3. เปิด Sender: python sender.py
<img width="1643" height="583" alt="image" src="https://github.com/user-attachments/assets/51db1b08-4b3e-477d-adb9-362d0181d311" />

---

## อธิบาย
- Multicast ส่งถึงเฉพาะกลุ่มที่ join เท่านั้น
- จำกัดขอบเขตด้วย TTL
