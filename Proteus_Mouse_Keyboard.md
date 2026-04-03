# Proteus 8 — สรุปการใช้ Mouse & Keyboard

> **Version:** Proteus 8.6 SP2  
> **หมวด:** Schematic Capture & VSM Simulation

---

## 🖱️ การใช้ Mouse

### คลิกพื้นฐาน

| การกระทำ | ผลลัพธ์ |
|---|---|
| คลิกซ้าย | เลือก Object |
| คลิกซ้ายค้าง + ลาก | ย้าย Object (Move) |
| คลิกซ้าย 2 ครั้ง | แก้ไข Properties ของ Object |
| คลิกขวา | เปิด Context Menu |
| คลิกขวา → Drag Object | ย้าย Object อีกวิธี |
| คลิกขวา → Delete | ลบ Object |
| คลิกขวา → Rotate | หมุน Object |
| คลิกขวา → Mirror | กลับด้าน Object |

### Scroll & Zoom

| การกระทำ | ผลลัพธ์ |
|---|---|
| Scroll ขึ้น | Zoom เข้า |
| Scroll ลง | Zoom ออก |
| Ctrl + Scroll | Zoom เข้า/ออก (ละเอียด) |
| คลิกกลาง + ลาก | Pan (เลื่อนมุมมอง) |

### การเลือกหลาย Object

| การกระทำ | ผลลัพธ์ |
|---|---|
| คลิกซ้าย + ลาก (พื้นที่ว่าง) | Select หลาย Object พร้อมกัน |
| Ctrl + คลิกซ้าย | เพิ่ม/ลด Object ออกจาก Selection |

---

## ⌨️ Keyboard Shortcuts

### Mode การวาด Schematic

| Key | คำสั่ง |
|---|---|
| `Esc` | กลับ Arrow / Select Mode ✅ ใช้บ่อยที่สุด |
| `P` | เพิ่มอุปกรณ์ (Pick Device) |
| `W` | ต่อสาย (Wire Mode) |
| `G` | วาง Ground |
| `T` | เพิ่มข้อความ (Text) |
| `L` | วาง Label / Net Name |
| `A` | วาดส่วนโค้ง (Arc) |
| `B` | วาดกล่อง (Box) |

### การหมุน / กลับด้าน

| Key | คำสั่ง |
|---|---|
| `R` | หมุน Object 90° (Rotate) |
| `X` | กลับซ้าย-ขวา (Mirror Horizontally) |
| `Y` | กลับบน-ล่าง (Mirror Vertically) |

### การแก้ไข

| Key | คำสั่ง |
|---|---|
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + C` | Copy |
| `Ctrl + V` | Paste |
| `Ctrl + D` | Duplicate (Copy ชิ้นส่วนที่เลือก) |
| `Ctrl + A` | Select All |
| `Del` | ลบที่เลือก |

### Zoom & มุมมอง

| Key | คำสั่ง |
|---|---|
| `F5` | Redraw / Refresh หน้าจอ |
| `F6` | Zoom เข้า |
| `F7` | Zoom ออก |
| `F8` | Fit ทั้งหมดในหน้าจอ |

### Simulation

| Key | คำสั่ง |
|---|---|
| `F12` | เริ่ม Simulate (Play ▶) |
| `Shift + F12` | หยุด Simulate (Stop ■) |
| `Pause` | หยุดชั่วคราว / เล่นต่อ |

### Source Code (VSM Studio)

| Key | คำสั่ง |
|---|---|
| `F7` | Build / Compile โค้ด |
| `Ctrl + S` | Save ไฟล์ |

### จัดการไฟล์

| Key | คำสั่ง |
|---|---|
| `Ctrl + N` | New Project |
| `Ctrl + O` | Open Project |
| `Ctrl + S` | Save |
| `Ctrl + P` | Print |

---

## 💡 Tips ที่ควรจำ

| สถานการณ์ | วิธีแก้ |
|---|---|
| ติดอยู่ใน Wire Mode ออกไม่ได้ | กด `Esc` |
| ต้องการย้าย Object | `Esc` → คลิกซ้ายค้าง + ลาก |
| ต้องการแก้ไข Properties | ดับเบิลคลิกที่ Object |
| มองไม่เห็น Schematic | กด `F8` (Fit to screen) |
| หน้าจอค้าง / แสดงผลผิด | กด `F5` (Redraw) |
| ลบ Object ผิด | กด `Ctrl + Z` ทันที |

---

*อ้างอิง: Proteus 8.6 SP2 — Labcenter Electronics*
