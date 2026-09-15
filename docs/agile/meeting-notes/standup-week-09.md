# Weekly Stand-up Meeting — Week 09

**วันที่ประชุม:** 2026-09-08 | **Sprint:** Sprint 1

---
## 🗣️ รายงานความคืบหน้าประจำสัปดาห์ (3 คำถามหลัก)

| สมาชิก (Domain) | อาทิตย์ที่ผ่านมาทำอะไรมาบ้าง (Done) | อาทิตย์นี้จะทำอะไร (Plan) | ปัญหา/อุปสรรคที่พบ (Blockers) |
| --- | --- | --- | --- |
| โตเกียว (Sound Designer) | ได้ใส่เสียง placeholder เข้าเพื่อทดสอบระบบ | แยกเสียง feedback ให้สื่อได้ชัดเจน | การหาเสียงเพื่อมาประกอบในเกม |

| โตเกียว (Programmer) | เขียนโค้ด Core Game ของ RaveYard บน MonoGame | Import Assets | เสียงไม่ sync |

| กาน (Artist) | ทำ art และ spritesheet สำหรับเกม | ทำต่อไป |

| เซบาส (Additional Programmer) | ทำ Distractions ให้เกม |
Import Assets ให้กับแต่ละตัว | อาจไม่เหมาะสมในบางช่วง |

| กาน (Artist) | วาด Asset สำหรับ prototype เสร็จแล้ว มี character spritesheet / background / UI symbol ทำแบบลวกๆ  |
ต่อยอดทำ Asset สำหรับใช้งานจริง  character spritesheet / background / UI symbol | ยังไม่มีปัญหา |

| Sebastien Tanapon Chapelin (Programmer) | เขียนโค้ดระบบจับจังหวะเสร็จ และทดสอบ Import Sprite เข้า
MonoGame | ทำระบบเสียง (sound) | ระบบเสียงยังไม่สมูท์
ตัวโน๊ตกับเสียงยังไม่ตรงกันเป็นบางจังหวะ |
| Kodchakorn Laikham (Designer) | ร่าง Layout Tilemap ด่าน 1 ใน Tiled ขนาด 32x32 |
จัดวาง Collision Layer ให้ตรงกับ Tilemap | รอขนาด Tile Size ที่โปรแกรมเมอร์ต้องการยืนยัน
|
| Pichaicharn Promma (Gamedesigner) | วางโครงสร้าง ScreenManager และหน้า Title Screen |
เชื่อมต่อระบบเปลี่ยน State ระหว่าง Title Screen และ Gameplay | โค้ด MonoGame บน
macOS มีปัญหาเรื่อง Font Rendering |
---
## ✅ Action Items & Blockers Resolution
- [ ] [หาเสียงใน freesound.org/Pixabay เพื่อตัดต่อและนำมาประกอบในเกม] [status:: doing]
[owner:: โตเกียว] [due:: 2026-09-12]
- [ ] [ทดสอบและปรับปรุงเสียง feedback ตามความต้องการ] [status:: todo]
[owner:: โตเกียว] [due:: 2026-09-14]

- [ ] [ช่วยโตเกียวทำโค้ด] [status:: doing]
[owner:: เซบาส] [due:: 2026-09-10]
- [ ] [Import Assets] [status:: done] [owner:: โตเกียว]
[due:: 2026-09-08]
- [ ] [ทดสอบเกม] [status:: todo]
[owner:: All] [due:: 2026-09-12]

- [ ] [ ทำ และให้เพื่อนเช็ค asset prototype ] [status:: done ] [owner:: กาน]
  [due:: done 8/8/2026 ]

- [ ] [ เช็ค animation ตัวละคร สำหรับใช้จริงคร่าวๆ ] [status:: in progress] [owner:: กาน]
  [due:: 20/8/2026]

- [ ] [ UI ] [status:: in progress] [owner:: กาน]
  [due:: 20/8/2026]

- [ ] [ cover game ] [status:: in progress] [owner:: กาน]
  [due:: 20/8/2026]

- [ ] [ช่วย Sebastien Tanapon Chapelin แก้ระบบจับจังหวะและระบบเสียง] [status:: doing]
[owner:: Supakorn Pairat] [due:: 2026-09-10]
- [ ] [ยืนยันขนาด Tile Size Natpasin Witee] [status:: done] [owner:: Supakorn Pairat]
[due:: 2026-09-08]
- [ ] [ทดสอบ Cross-platform Font บน Windows/macOS] [status:: todo]
[owner:: Supakorn Pairat] [due:: 2026-09-12]
---
## Related Documents
- [[docs/agile/sprint-plan-01|Sprint 1 Plan]]
- [[docs/agile/02-sprint-backlog|Sprint Backlog]]