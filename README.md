ชื่อโครงงาน : เข้าออกปลอดภัยด้วยระบบสแกน

โครงงานนี้เป็นส่วนหนึ่งของรายวิชา Practicum for Computer Engineering การปฏิบัติการทางวิศวกรรมคอมพิวเตอร์ รหัสวิชา 01204223 ภาควิชาวิศวกรรมคอมพิวเตอร์ คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ ภาคปลาย ปีการศึกษา 2564 หมู่ 11,12

โครงงานนี้จัดทำโดยกลุ่ม วินจะมาแบก มีสมาชิกกลุ่มดังนี้

1. 6310500040 นายปรมี สกุลตั้งมณีรัตน์ 
2. 6310500481 นายปรัญชัย สมเกษม 
3. 6310503201 นายกัณฑ์เพชร เตชะวิจิตรา 
4. 6310503324 นายทัตเทพ รัตนจันทร์

รายการอุปกรณ์ Hardware

- Board NodeMCU - ATmega328p (Practicum Board v3.2 CPE. KU 2020-11)  x 1
- RaspberryPI x 1 
- Servo  x 1
- BreadBoard x 1 
- LCD x 1
- RFID Card Reader/Detecto x 1
- สายไฟ
- Jumper

ไฟล์โครงงานประกอบไปด้วย 

frontend
├── web.html  เป็นไฟล์ที่เก็บ html ไว้ทั้งหมด
└── web.css เป็นไฟล์ที่เก็บ css ไว้ทั้งหมด

Backend
├── main.py    ใช้ในการรับค่าบัตร ควบคุมการเปิดประตู
└── practicum.py    ใช้ในการส่งและรับค่าจาก hardware

Library ที่ใช้สำหรับ Python

- ‘json’ 
- ‘time’ 
- ‘datetime’ 

Hardware
├── particum.ino เป็นโปรทุกอย่างของ Hardware
└── usbconfug.h เป็น config สำหรับ usb

Library ที่ใช้สหรับ Arduino

- ‘MFRC522’ 
- ‘Wire’
- ‘SPI’
- ‘usbdrv’
- ‘LiquidCrystal_I2C’ 
- ‘Servo’ 

Data
├── count.txt ใช้เก็บค่าของจำนวนคนที่อยู่ข้างในตอนปัจจุบัน
├── remaining.txt ใช้เก็บค่าของจำนวนคนที่สามารถเข้าได้
└── enter.txt ใช้เก็บค่าของประวัติการเข้าออก

hardware-driver-main


license.txt ไฟล์แสดงข้อมูลลิขสิทธิ์ 

