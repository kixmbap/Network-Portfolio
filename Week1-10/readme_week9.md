# WEEK 9 – Bio-Inspired Networking

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. เปิด 3 terminal แล้วรัน node.py พร้อมระบุ port และ peers เช่น
   python node.py 13000 13001 13002
   python node.py 13001 13000 13002
   python node.py 13002 13000 13001
2. พิมพ์ข้อความเพื่อส่ง message
<img width="1274" height="578" alt="image" src="https://github.com/user-attachments/assets/74b5ca98-42ab-4792-a4d6-6a8dcd8239e1" />

---

## อธิบาย
- ใช้ pheromone reinforcement/decay ในการเลือกเส้นทาง
- ระบบเรียนรู้เส้นทางที่ดีที่สุดเอง
