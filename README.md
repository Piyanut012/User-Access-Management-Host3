# User Access Management

Linux เก็บข้อมูลของผู้ใช้และกลุ่มไว้ในไฟล์และไดเรกทอรีที่เฉพาะเจาะจงที่มีข้อมูลบัญชีผู้ใช้ รหัสผ่าน และการกำหนดค่ากลุ่ม เจ้าหน้าที่ระบบสามารถปฏิสัมพันธ์กับไฟล์เหล่านี้เพื่อควบคุมและปรับเปลี่ยนการตั้งค่าของผู้ใช้และกลุ่มใน Linux ได้

# Subcomponents
1. Add/Delete/Mod Users/Groups
   - การสร้างผู้ใช้ใหม่และกำหนดสิทธิ์ในการเข้าถึงไฟล์และรายการอื่น ๆ ในระบบ
   - การลบผู้ใช้ที่ไม่ใช้แล้วหรือไม่จำเป็นออกจากระบบ
   - การแก้ไขข้อมูลผู้ใช้และกลุ่มเช่น รหัสผ่าน หรือกำหนดสิทธิ์ใหม่
2. User Policy และ Password Policy
   - การกำหนดนโยบายสำหรับผู้ใช้ เช่น การกำหนดความแข็งแกร่งของรหัสผ่าน การกำหนดนโยบายเกี่ยวกับการใช้งาน
   - การกำหนดระยะเวลาการเปลี่ยนรหัสผ่าน การบังคับให้ใช้งานการยืนยันตัวตนสองขั้นตอน เป็นต้น
3. Authentication/IDM/SSO
   - การตรวจสอบและการรับรองตัวตนของผู้ใช้ก่อนที่จะเข้าสู่ระบบ
   - การบริหารจัดการข้อมูลตัวตนของผู้ใช้ รวมถึงการตรวจสอบการเข้าถึงและการอนุญาต
   - การใช้งานระบบ Single Sign-On (SSO) เพื่ออนุญาตผู้ใช้ให้เข้าสู่ระบบหลายระบบได้ด้วยการรับรองตัวตนเดียว
4. Authorization
   - การกำหนดสิทธิ์และการอนุญาตในการเข้าถึงข้อมูลและทรัพยากรต่างๆ ในระบบ
   - การกำหนดสิทธิ์ให้กับกลุ่มผู้ใช้หรือผู้ใช้แต่ละคน เช่น สิทธิ์ในการอ่าน การเขียน หรือการดำเนินการแบบอื่นๆ
5. Access Control, Firewall
   - การกำหนดนโยบายและกฏในการควบคุมการเข้าถึงข้อมูล โดยใช้เครื่องมือเช่น Access Control Lists (ACLs) เพื่อกำหนดสิทธิ์การเข้าถึงข้อมูลแยกตามผู้ใช้หรือกลุ่ม
   - การใช้งานระบบไฟร์วอลล์เพื่อควบคุมการเข้าถึงของเครือข่ายและข้อมูลที่เข้าถึงระบบ

ทั้งหมดเป็นองค์ประกอบที่สำคัญในการควบคุมและจัดการความปลอดภัยในระบบ Linux ซึ่งมีการทำงานร่วมกันเพื่อให้ระบบมีความปลอดภัยและการเข้าถึงทรัพยากรที่เชื่อถือได้ที่สูงขึ้นอย่างมีประสิทธิภาพในระบบ Linux.
# User-Access-Management-3
 คือ 

| รหัสนักศึกษา | ชื่อ - นามสกุล | ส่วนรับผิดชอบ 
| --- | --- | --- |
| `65070138` | นายปิยณัฐ โรจน์เจริญทรัพย์ | Access Control, Firewall
| `65070149` | นายพริษฐ์ ชมภูบุตร | Password Policy
| `65070181` | นายภูริพัทธ์ ชนะภัย | Add/Delete/Mod Users/Groups
| `65070190` | นายมานัส ถนอมรอด | Authentication/IDM/SSO
| `65070191` | นายเมธัส พุ่มพวง | Authentication/IDM/SSO
| `65070229` | นายสพณทร บุญกรไกรฤกษ์ | User Policy/Authorization
| `65070232` | นายสหชินเดช เกตุดี | Authorization


# เอกสารอ้างอิง
https://phoenixnap.com/kb/user-management-linux
