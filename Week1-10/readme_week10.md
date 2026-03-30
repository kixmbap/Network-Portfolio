# WEEK 10 – Quantum-Inspired Networking

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. เปิด 3 terminal แล้วรัน node.py พร้อมระบุ port และ peers เช่น
   python node.py 11000 11001 11002
   python node.py 11001 11000 11002
   python node.py 11002 11000 11001
2. พิมพ์ข้อความเพื่อส่ง token
<img width="1274" height="574" alt="image" src="https://github.com/user-attachments/assets/1e6cf088-2bc2-4909-b7f6-7cdf5d7e118b" />

---

## อธิบาย
- ข้อความเป็น token อ่านได้ครั้งเดียว
- มีหมดอายุ (expire) และ state collapse
