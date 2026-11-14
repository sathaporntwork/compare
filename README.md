# DiffCraft Studio v2.3.0 (Portable Standalone Edition) ⚖️

> **Enterprise-Grade Web Text & File Diff Comparison Platform**  
> *100% Client-Side Private • Zero-Install Portable • 100% Offline & Corporate Policy Safe*

---

## 🚀 Quick Start / วิธีใช้งานเบื้องต้น

1. **ดับเบิลคลิกที่ไฟล์ `index.html`** เพื่อเปิดใช้งานบนเว็บเบราว์เซอร์ได้ทันที  
   *(รองรับ Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, Safari ฯลฯ)*
2. **ไม่ต้องติดตั้งโปรแกรม (Zero Installation)** ไม่ต้องมี Node.js และไม่ต้องใช้อินเทอร์เน็ต
3. **ความเป็นส่วนตัว 100% (Air-Gapped & Private)** ข้อมูลการเปรียบเทียบไฟล์ทั้งหมดจะถูกประมวลผลบนหน่วยความจำของเบราว์เซอร์เครื่องคุณเท่านั้น ไม่มีการส่งข้อมูลออกนอกเครื่องเด็ดขาด

---

## ✨ คุณสมบัติเด่น (Key Features)

* **Virtual Windowed Rendering**: รองรับการวางและเปรียบเทียบข้อความขนาดใหญ่ (1,000 ถึง 100,000+ บรรทัด) ได้อย่างลื่นไหล 60 FPS หน้าจอไม่ค้าง
* **High-Performance Myers Diff**: คำนวณจุดต่างรวดเร็วระดับมิลลิวินาที (35ms บน 10,000 บรรทัด) พร้อมการตัด Common Prefix/Suffix
* **Beyond Compare Style Red Diff Scheme**: ไฮไลต์จุดต่างด้วยโทนสีแดง Beyond Compare แท้ทั้งสองฝั่ง และไม่มีเส้นขีดฆ่าตรงกลางบดบังสายตา
* **Line Details Pane**: แถบขยายเปรียบเทียบข้อความระดับตัวอักษรของบรรทัดที่เลือกด้านล่างสุด
* **Sticky Line Numbers**: คอลัมน์เลขบรรทัดตรึงติดขอบซ้ายตลอดเวลา ไม่เลื่อนหลุดหายเมื่อมีข้อความยาว
* **Interactive Block Merge**: ปุ่มคัดลอกส่วนต่างระหว่าง ฝั่งซ้าย ➔ ฝั่งขวา หรือ ฝั่งขวา ➔ ฝั่งซ้าย ได้ทันที
* **Undo / Redo (<kbd>Ctrl</kbd> + <kbd>Z</kbd> / <kbd>Ctrl</kbd> + <kbd>Y</kbd>)**: บันทึกประวัติการแก้ไขและย้อนกลับได้สมบูรณ์
* **File Encoding Support**: รองรับการอ่านและบันทึกไฟล์ UTF-8, TIS-620 / Windows-874 (ภาษาไทย), และ UTF-16 LE
* **Save to File (<kbd>Ctrl</kbd> + <kbd>S</kbd>)**: บันทึกกลับไฟล์เดิมพร้อมคงค่า Line Ending (CRLF/LF) และ BOM
* **Bilingual UI (TH/EN)**: สลับภาษาไทย 🇹🇭 และภาษาอังกฤษ 🇬🇧 ได้ทันทีเพียงคลิกเดียว

---

## ⌨️ คีย์ลัดหลัก (Keyboard Shortcuts)

| คีย์ลัด (Shortcut) | การทำงาน (Action) |
| :--- | :--- |
| <kbd>Ctrl</kbd> + <kbd>V</kbd> | วางข้อความจากคลิปบอร์ดลงในฝั่งที่เลือกหรือฝั่งที่ว่าง |
| <kbd>Ctrl</kbd> + <kbd>A</kbd> | เลือกข้อความทั้งหมดใน Pane ที่กำลังโฟกัส |
| <kbd>Ctrl</kbd> + <kbd>C</kbd> | คัดลอกข้อความทั้งหมดใน Pane ที่กำลังเลือก |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> | บันทึกการแก้ไขกลับไฟล์เดิม (Chromium) |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd> | บันทึกเป็นไฟล์ใหม่ (Save As) |
| <kbd>Ctrl</kbd> + <kbd>Z</kbd> / <kbd>Ctrl</kbd> + <kbd>Y</kbd> | เลิกทำ (Undo) / ทำซ้ำ (Redo) |
| <kbd>Ctrl</kbd> + <kbd>F</kbd> | ค้นหาข้อความในเอกสาร |
| <kbd>Alt</kbd> + <kbd>↓</kbd> หรือ <kbd>F7</kbd> | ไปยังจุดต่างถัดไป (Next Difference) |
| <kbd>Alt</kbd> + <kbd>↑</kbd> หรือ <kbd>Shift</kbd> + <kbd>F7</kbd> | ไปยังจุดต่างก่อนหน้า (Previous Difference) |
| <kbd>Alt</kbd> + <kbd>→</kbd> | รวมบล็อกปัจจุบันจากซ้ายไปขวา (Merge Left to Right) |
| <kbd>Alt</kbd> + <kbd>←</kbd> | รวมบล็อกปัจจุบันจากขวาไปซ้าย (Merge Right to Left) |
| <kbd>Alt</kbd> + <kbd>S</kbd> | สลับตำแหน่งเนื้อหา ซ้าย ⇄ ขวา (Swap Panes) |
| <kbd>?</kbd> | เปิดหน้าต่างคีย์ลัดทั้งหมด |

---

## 📁 โครงสร้างไฟล์ในแพ็กเกจ (Package Contents)

```text
DiffCraft-Studio-v2.3.0/
├── index.html       # ไฟล์หลักสำหรับเปิดใช้งาน (ดับเบิลคลิกเพื่อเปิด)
├── css/
│   └── style.css    # สไตล์และธีมทั้งหมด
├── js/
│   └── bundle.js    # ไฟล์ระบบ Client Bundle (IIFE Standalone)
├── CHANGELOG.md     # ประวัติการพัฒนาและอัปเดตแต่ละเวอร์ชัน
└── README.md        # เอกสารแนะนำการใช้งานฉบับนี้
```

---
*ดูประวัติการเปลี่ยนแปลงเพิ่มเติมได้ที่ [CHANGELOG.md](CHANGELOG.md)*
