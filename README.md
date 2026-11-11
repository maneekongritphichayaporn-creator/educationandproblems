# Future Education

เว็บไซต์ภาษาไทยเกี่ยวกับปัญหาการศึกษาไทย จัดทำขึ้นเพื่อรวบรวมข้อมูลและข่าวสาร แนะนำแหล่งเรียนรู้ และนำเสนอเรื่องราวผ่านสถานการณ์จำลอง

เว็บไซต์ออนไลน์: [educationandproblems.vercel.app](https://educationandproblems.vercel.app/)

## เนื้อหาภายในเว็บไซต์

- `index.html` — หน้าแรกและทางเข้าสู่เนื้อหาต่าง ๆ
- `about.html` — เกี่ยวกับโครงการ
- `service.html` — ปัญหาที่เกี่ยวข้องกับการศึกษาไทย
- `case.html` — ข่าวและกรณีศึกษา
- `blog1.html`, `blog2.html` — ข้อมูลหลักสูตรและค่าย
- `game.html` และ `ans*.html` — สถานการณ์จำลองและหน้าตัวเลือกคำตอบ
- `board.html` — พื้นที่แลกเปลี่ยนเรื่องราว
- `contact.html` — หน้าติดต่อ

## การเปิดเว็บไซต์ในเครื่อง

เว็บนี้เป็น HTML, CSS และ JavaScript แบบ static ไม่มีขั้นตอน build หรือติดตั้ง dependencies สำหรับตัวโปรเจกต์

1. ดาวน์โหลดหรือ clone repository นี้
2. เปิดโฟลเดอร์ด้วย editor หรือเว็บเซิร์ฟเวอร์สำหรับ static files เช่น Live Server ใน VS Code
3. เปิด `index.html` ผ่านเว็บเซิร์ฟเวอร์

หากติดตั้ง PHP แล้ว สามารถเริ่มเว็บเซิร์ฟเวอร์ทดสอบจากโฟลเดอร์โปรเจกต์ด้วยคำสั่ง:

```bash
php -S localhost:8000
```

จากนั้นเปิด [http://localhost:8000](http://localhost:8000)

> ฟอร์มติดต่อใช้ `mail/contact.php` ซึ่งต้องรันผ่าน PHP และตั้งค่า `mail()` บนเซิร์ฟเวอร์ให้พร้อม การเปิดไฟล์ HTML โดยตรงหรือใช้ static hosting อย่างเดียวจะไม่ส่งอีเมล

## โครงสร้างไฟล์

- `css/`, `scss/` — สไตล์ที่เว็บใช้และไฟล์ SCSS ต้นฉบับ
- `js/` — JavaScript ของเว็บไซต์
- `lib/` — ไลบรารีที่ใช้ในหน้าเว็บ เช่น Owl Carousel และ Easing
- `mail/` — สคริปต์ PHP สำหรับฟอร์มติดต่อ
- `*.html` — หน้าเว็บไซต์

## เครดิตและลิขสิทธิ์

เว็บไซต์นี้ใช้เทมเพลต **DotCom – Creative Agency Website Template** จาก [HTML Codex](https://htmlcodex.com/creative-agency-website-template) โดย HTML Codex ([เว็บไซต์ผู้จัดทำ](https://htmlcodex.com)) โปรดดูเงื่อนไขการใช้งานและการให้เครดิตใน [`LICENSE.txt`](LICENSE.txt)
