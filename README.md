# SCHS_Reports

หน้ารายงานของ ส.เจริญโฮมสแควร์ สำหรับแชร์ลิงก์ให้คนอื่นดู เผยแพร่ผ่าน GitHub Pages

ข้อมูลต้นฉบับอยู่ใน repo SCHS_Web (private) repo นี้เก็บเฉพาะหน้าที่ตั้งใจแชร์

## โครงสร้าง

```
index.html                     หน้ารวมรายงาน (รายงานใหม่ใส่บนสุด)
reports/YYYY-MM-DD-shortname/  รายงานละโฟลเดอร์ ไฟล์หลักชื่อ index.html
robots.txt                     กันไม่ให้เครื่องมือค้นหาเก็บหน้า
```

ทุกหน้าใส่ `<meta name="robots" content="noindex, nofollow">` เพราะเป็นข้อมูลภายในร้าน ใครมีลิงก์เปิดได้ แต่ไม่ขึ้นใน Google
