# ENGCE301
Software Design and Development

## ข้อมูลกลุ่ม
กลุ่มที่ 1 (CPE No.1)

## สมาชิกในกลุ่ม
1. นายเมธิวัฒน์ ชมชื่น 67543206069-6 [(GitHub)](https://github.com/maythiwat)
2. นายอชิตพล โอชารส 67543206027-4 [(GitHub)](https://github.com/achitphon09)
3. นายศราวุฒิ ข่ายแก้ว 67543206076-1 [(GitHub)](https://github.com/sarawut5555)
4. นายพีสิรวิชญ์ ชัยวัชรนนท์ 67543206068-8 [(GitHub)](https://github.com/Peesiravit)
5. นายชาคริตส์ แก้วมูลเมือง 67543206005-0 [(GitHub)](https://github.com/Zag5A6167)

## ไฟล์สำคัญ
- [ENVIRONMENT.md](./ENVIRONMENT.md)
- [SE_INTRO_NOTES.md](./SE_INTRO_NOTES.md)

## DevTools Reflection (Week 1)

1) Browser รู้ได้อย่างไรว่าต้องรัน JavaScript ใน `<script>` เมื่อโหลดหน้าเว็บ?
Browser รู้ว่าต้องรัน JavaScript เพราะเมื่อ HTML Parser ของ Browser พบแท็ก script ในโค้ด HTML
Browser จะหยุดการประมวลผล DOM ชั่วคราว และนำโค้ดภายในแท็ก script ส่งให้ JavaScript engine ของ Browser ประมวลผลทันที
จากนั้นจึงกลับไปประมวลผล DOM ต่อจนครบทั้งไฟล์ HTML และเรนเดอร์เป็นหน้าเว็บเพจในที่สุด

2) ถ้าไม่มี DevTools การแก้ไขปัญหา (debug) เวลาเว็บมีปัญหาจะยากขึ้นอย่างไร?
- ...
- ...
- ...

3) แต่ละคนคิดว่า Panel ไหนใน DevTools จะได้ใช้บ่อยที่สุดในเทอมนี้ (Elements / Console / Network / อื่น ๆ)? เพราะอะไร?
- (เมธิวัฒน์) "Network" เพราะจะต้องดูการรับ-ส่งข้อมูล ผ่าน API ว่า Request ที่ส่งไป และ Response ที่ได้รับนั้นถูกต้องหรือไม่
- (...) ...
