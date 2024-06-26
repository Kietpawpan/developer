# การพัฒนา Web Application ภาครัฐ โดยเจ้าหน้าที่ของรัฐ

เว็บแอปภาครัฐที่เจ้าหน้าที่ของรัฐพัฒนาเอง เน้นที่ความคุ้มค่าและเกิดประโยชน์ต่อประชาชน ตามหน้าที่รับผิดชอบ ซึ่งมีขั้นตอนการพัฒนา ดังนี้ 
> [!NOTE]
> __ปัจจัย 4__
> 1. ความรู้ด้านภาษาคอมพิวเตอร์: HTML/CSS/JavaScript/PHP 
> 2. Server ขออนุมัติใช้ Cloud ภายใต้โครงการ GDDC ของกระทรวง DE เพื่อทำเป็น Web Server
> 3. ระบบปฏิบัติการ Window/Antivirus/Web Server
> 4. Antivirus/SSL Certificate 


## 1. วิเคราะห์ปัญหา
> [!TIP]
> - _A problem well stated is half solved_.--__Charles Kettering__
> - _Direction is more important than speed_.
> - _Give me six hours to chop down a tree and I will spend the first four sharpening the axe_.--__Abraham Lincoln__

### 1.1 ยุบกระบวนงาน
ถ่ายโอนภารกิจ
- ระบบรับเรื่องร้องเรียน (e-Petition) ให้ กตร.
- ระบบห้องสมุด (e-Library) ให้ สพท.

เลือกกระบวนงานนำร่อง คือ งานบริการข้อมูลข่าวสารของราชการ
  
### 1.2 จำแนกขั้นตอน
```mermaid
flowchart LR
    A[Start] --> B[ยื่นคำขอ]
    B --> C[พิจารณาคำขอ]
C-->D[แจ้งผล]
D-->E[ชำระค่าธรรมเนียม]
E-->F[นัดรับข้อมูล]
F-->G[End]
```

### 1.3 คิดหาแนวทางการประยุกต์ใช้เทคโนโลยีในแต่ะขั้นตอน
- Web Application
  - e-Request
  - AI (Expert System)
  - e-Tracking
  - e-Payment
> [!TIP]
> ประชาชนสะดวก เจ้าหน้าที่สบาย

## 2. ออกแบบ
### 2.1 ออกแบบหน้าที่ (UX)
- e-Form
- e-Mail
- Search box
- Database
    
>[!TIP]
> หน้าที่ สำคัญกว่า หน้าตา

### 2.2. ออกแบบหน้าตา (UI)
- ดูมาตรฐานภาครัฐ
- สร้างสรรค์สิ่งที่ดีกว่า
>[!TIP]
> _สะดวก รวดเร็ว เข้าถึง่าย คุ้มค่า มั่นคงปลอดภัย_
 
## 3. เขียนโปรแกรม
### 3.1 เลือกโปรแกรมหลังบ้าน
ใช้ระบบที่มีอยู่
- Web Server ของ DE
- E-mails ของทุกหน่วยงาน ทส.
- จนท.สารบรรณ ของทุกหน่วยงาน ทส.
- Apache/PHP/
   
- จั่นเจา ไม่ตีกระบี่เอง
- เห้งเจีย ไม่สร้างกระบองเอง
>[!TIP]
> _If I have seen further it is by standing on the shoulders of Giants_.--__Isaac Newton__

### 3.2 สร้างโปรแกรมหน้าบ้าน
เน้นภาษาสากล HTML/JavaScript/CSS/PHP 
- เรียนรู้ง่าย
- สร้างง่าย
- ใช้ง่าย
ตกแต่งภายในก่อนภายนอก
>[!TIP]
> _f you can't make it good, at least make it look good_.--__Bill Gate__

## 4. ตกแต่งภายนอก
ทำตามกฎหมายและระเบียบที่เกี่ยวข้อง
- PDPA
- Cybersecuirty
- App Standard
- etc.
  
## 5. ทดสอบระบบ
- มีอะไรเพี้ยนไหม
- ใช้ง่ายไหม
- ปลอดภัยไหม
- ลองใช้กันเองสักช่วงหนึ่ง

## 6. เผยแพร่
- ติดตั้งบน Web Server
- ติดตั้ง SSL Cert
  
## 5. ติดตามประเมินผลและบำรุงรักษา
- Sentiment Analysis
- MA เช่น ต่ออายุ SSL Certificate/เปลี่ยนเวอร์ชัน Window/Backup ฯลฯ 
