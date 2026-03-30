# WEEK 8 – Opportunistic Routing

## ผลลัพธ์ทดลอง (Result)

---

## วิธีทดลอง
1. เปิดหลาย terminal แล้วรัน node.py พร้อมระบุ port และ peers เช่น
   python node.py 12000 12001 12002
   python node.py 12001 12000 12002
   python node.py 12002 12000 12001
2. พิมพ์ข้อความเพื่อส่ง message

---

## อธิบาย
- ส่ง message เมื่อพบ peer ที่มีโอกาสส่งถึงสูง
- ใช้ delivery probability ในการตัดสินใจ
