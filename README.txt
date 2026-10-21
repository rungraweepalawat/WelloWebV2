WELLO BY TUATON — SEO + BLOG + BUSINESS TOOLS (v55)

แพ็กเกจนี้รวม:
- index.html: หน้าเว็บหลักและแอปสร้างเอกสารในหน้าเดียว
- images/: ภาพหน้าเว็บ แบรนด์ลูกค้า บริการ ไอคอน และ QR LINE
- blog/index.html: หน้ารวมบทความ
- blog/*.html: บทความ SEO 4 เรื่องที่เชื่อมไปยังบริการและ LINE
- robots.txt และ sitemap.xml: สำหรับ Search Engine
- CNAME: wellodocs.com (เก็บไว้เมื่ออัปโหลดขึ้น GitHub Pages)

เครื่องมือฟรี 3 ประเภท:
1. ใบเสนอราคา (quotation)
2. ใบแจ้งหนี้ (invoice)
3. ใบเสร็จรับเงิน (receipt)

วิธีนำขึ้น GitHub Pages:
1. แตก ZIP
2. อัปโหลด index.html และทับไฟล์ index.html เดิมใน root ของ Repository
3. อัปโหลดโฟลเดอร์ images/, โฟลเดอร์ blog/, robots.txt และ sitemap.xml
4. เก็บไฟล์ CNAME เดิมไว้ (ไม่ต้องลบ)
5. Commit changes แล้วตรวจ URL หน้าแรก, /blog/, และแต่ละ URL ใน sitemap

การเปลี่ยนภาพ:
- ภาพ Hero: images/hero/
- ภาพบริการ: images/services/
- โลโก้ลูกค้า: images/clients/
- QR LINE: images/contact/line-qr.jpg
- Icon: images/ui/
เมื่อเปลี่ยนภาพให้ใช้ชื่อไฟล์เดิม เพื่อไม่ต้องแก้ path ใน HTML

SEO Checklist หลังเผยแพร่:
- ตรวจว่า canonical URL ตรงกับโดเมนจริง
- เพิ่ม/ยืนยันโดเมนใน Google Search Console
- ส่ง https://wellodocs.com/sitemap.xml
- ใช้ URL Inspection ขอจัดทำดัชนีหน้าแรก หน้ารวมบทความ และบทความใหม่
- เชื่อม GA4 หรือ Google Tag Manager ก่อนเริ่มนับ conversion ของ LINE/โทรศัพท์

ข้อควรรู้:
- Sitemap และ structured data ช่วยให้ search engines เข้าใจเว็บไซต์ แต่ไม่รับประกันการ index หรืออันดับ
- เครื่องมือสร้างเอกสารประมวลผลในเบราว์เซอร์และใช้ localStorage บนเครื่องผู้ใช้สำหรับอีเมลผู้สร้าง; ไม่มีการส่งข้อมูลเอกสารไปยังฐานข้อมูลกลาง
- ปุ่มในเครื่องมือฟรีใช้ DOCS object เดิมใน index.html โดยเลือก quotation, invoice หรือ receipt


UPDATE v56 — หน้าแรกและเครื่องมือแยกกัน
- หน้าแรก: index.html (ซ่อนส่วนพรีวิวบทความและเครื่องมือฟรีออกจากหน้าแรก)
- บทความ: blog/index.html และบทความย่อยในโฟลเดอร์ blog/
- เครื่องมือฟรี: tools/index.html (ใบเสนอราคา ใบแจ้งหนี้ ใบเสร็จรับเงิน)
- เมนูส่วนหัวของหน้าแรกเชื่อมไปหน้า blog/ และ tools/ โดยตรง
- อัปโหลดโฟลเดอร์ tools/ เพิ่มไปกับ index.html, blog/, images/, robots.txt, sitemap.xml และ CNAME
SEO update 2026-10-20: refreshed blog page titles/descriptions and buyer-focused content; added graphic-design-pricing.html and social-media-graphic-design.html; corrected /tools/ search metadata; updated sitemap and internal links. Search volume should be verified in Google Keyword Planner and Search Console after publishing.
