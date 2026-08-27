# RTR Lead — Landing Page

## ไฟล์
- index.html        หน้าแรก (ใช้ไฟล์ใน assets/)
- 404.html          หน้าเดียวกัน แต่รวม CSS/JS ไว้ในตัว
                    GitHub Pages เสิร์ฟไฟล์นี้เมื่อหา path ไม่เจอ
                    ทำให้ /r/T3EV ใช้งานได้โดยไม่ต้องมีโฟลเดอร์รายร้าน
- assets/styles.css
- assets/app.js     ตั้งค่า API ที่ไฟล์นี้
- .nojekyll         ห้ามลบ

## ตั้งค่า
เปิด assets/app.js บรรทัดบนสุด วาง URL ของ Apps Script Web App
จากนั้นเปิด 404.html หา var API แล้ววาง URL เดียวกัน (404.html รวมโค้ดไว้ในตัว)

## เพิ่มร้านใหม่
ไม่ต้องแก้ไฟล์เว็บเลย แค่เพิ่มแถวในแท็บ Shops แล้วสร้าง QR ใหม่
