# WEEK 7 – Store-and-Forward Communication

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. แก้ไข config.py (HOST, BASE_PORT, PEER_PORTS, BUFFER_SIZE, RETRY_INTERVAL)
2. เปิด node หลาย Terminal: python node.py
3. ปิด node บางตัวเพื่อจำลองลิงก์ขาด แล้วเปิดใหม่
<img width="1309" height="287" alt="image" src="https://github.com/user-attachments/assets/de21620e-7097-4f6c-80c7-4e16f204642f" />

---

## อธิบาย
- เก็บ message ไว้ก่อน ส่งใหม่เมื่อ peer กลับมา
- ทนต่อความล่าช้าและการขาดการเชื่อมต่อ
