# WEEK 7 – Store-and-Forward Communication

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. แก้ไข config.py (HOST, BASE_PORT, PEER_PORTS, BUFFER_SIZE, RETRY_INTERVAL)
2. เปิด node หลาย Terminal: python node.py
3. ปิด node บางตัวเพื่อจำลองลิงก์ขาด แล้วเปิดใหม่

---

## อธิบาย
- เก็บ message ไว้ก่อน ส่งใหม่เมื่อ peer กลับมา
- ทนต่อความล่าช้าและการขาดการเชื่อมต่อ
