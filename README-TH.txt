COCONUT MASSAGE · KOH SAMUI — เว็บไซต์ที่แก้ไขเองได้

ไฟล์สำคัญ
- index.html = หน้าเว็บไซต์
- data/site.json = ข้อความ เมนูนวด ราคา และข้อมูลรถ
- images/ = รูปภาพที่ใช้บนเว็บไซต์
- .pages.yml = ตั้งค่า Pages CMS
- js/content-manager.js = ตัวเชื่อมข้อมูลกับหน้าเว็บ

วิธีใช้งานแบบง่าย
1. สร้าง GitHub repository ใหม่สำหรับเว็บไซต์
2. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดในชุดนี้
3. เชื่อม repository เข้ากับ Cloudflare Pages แบบ Git integration
4. เข้า app.pagescms.org แล้ว Sign in with GitHub
5. เลือก repository นี้
6. ใน Pages CMS จะมีเมนู “ตั้งค่าเว็บไซต์”, “เมนูนวด” และ “Taxi / รถรับส่ง”
7. เปลี่ยนรูป ราคา หรือข้อความ แล้วกด Save
8. Cloudflare จะ deploy เวอร์ชันใหม่ให้อัตโนมัติ

หมายเหตุ:
- รูปเมนูให้เลือกจากโทรศัพท์ได้ผ่าน Media Manager ของ Pages CMS
- ราคาแก้เป็นตัวเลขบาทได้โดยตรง
- Toyota Ventury ตั้งไว้ 10 คน และ Mitsubishi Xpander ตั้งไว้ 4 คน
