# 🧵 Weaver — จอมเวทผู้ทอสาย

![Level Gate](https://img.shields.io/badge/ปลดล็อก-Lv%20131--135-7c5cd6?style=flat-square)
![Skills](https://img.shields.io/badge/สกิลทั้งหมด-43-0e9c8f?style=flat-square)
![Grimoire](https://img.shields.io/badge/กริมัวร์-ใส่คลาสไหนก็ได้-a3720a?style=flat-square)

> คลาสระดับปลายเกม รวมดาเมจ ซัพพอร์ต และการคุมสนามไว้ในตัวเดียว "A versatile spellweaver who threads support and control, bending the flow of battle to favor their allies."

> [!NOTE]
> Base class origin ยังไม่ชัดเจน (ดู [../overview.md](../overview.md)) — ปลดล็อกช้ากว่าคลาสขั้นสูงอื่นมาก (26-90 → 131-135) และใส่กริมัวร์คลาสไหนก็ได้ น่าจะเป็น **prestige/endgame class** มากกว่า advanced class ปกติ

---

## 📜 สกิลทั้งหมด (43 ตัว ยืนยันแล้ว)

Icebolt, Firebolt, Weaver Mastery, Piercing Flurry, Strafing Volley, Venom Strike, Haste, Ice Shard, Fireball, Bash, Impale, Arrow Shower, Venom Coating, Cure, Earthbolt, Thunderbolt, Endure, Air Cutter, Blade Dance, Shadow Step, Holy Light, Earth Spikes, Thunder Storm, Fortify, Stomp, Mark Target, Cloaking, Soul Strike, Suppression Field, Banishment Field, Natural Resistance, Vortex Slash, Steady Hands, Lightning Reflexes, Benediction, Resonance Well, Dissonance Well, Divine Grace, Whirlwind, Inner Focus, Dual Wield Mastery, Heal

หลายสกิลแชร์กับคลาสอื่น (Whirlwind ↔ Warrior, Arrow Shower ↔ Scout, Fireball/Thunder Storm ↔ Mage) → ยืนยันว่า Weaver เป็น "จอมยุทธ์รวมทุกสาย" ไม่ใช่คิทเฉพาะตัว

## 🧭 สี่สายทักษะ — เลือกทางที่จะเดิน

| สาย | สกิลเด่น | เหมาะกับ |
|---|---|---|
| 🔥 **ฟาร์ม/ดาเมจ** | Thunder Storm, Fireball, Ice Shard, Earth Spikes | เล่นคนเดียว, ฟาร์ม/เลเวลลิ่ง — **แนะนำเป็นสายหลัก** |
| 🗡️ **ประชิด/Bash** | Bash, Impale, Piercing Flurry, Whirlwind | ไม่อยากบริหารมานา, ชอบระยะประชิด |
| 💚 **ซัพพอร์ต** | Heal, Cure, Benediction, Divine Grace | เล่นปาร์ตี้บ่อย |
| 🛡️ **คุมสนาม** | Suppression Field, Banishment Field, Cloaking | PvP / บอสที่ต้องคุมพื้นที่ |

---

## ⚔️ ตารางสกิลฟาร์ม (ยืนยันจากหน้าสกิลจริง)

| สกิล | ธาตุ | ต้องเรียนก่อน | คูลดาวน์ | มานา | ดาเมจ/lv | แชร์กับ |
|---|---|---|---|---|---|---|
| ⚡ **Thunder Storm** 🏆 | ลม/น้ำ | Thunderbolt Lv1 | `1s` | `30 (+15/lv)` | `+2.5/lv` | Mage |
| 🔥 Fireball | ไฟ | Firebolt Lv1 | `1s` | `30 (+15/lv)` | `+1/lv` | Mage |
| 🌀 Whirlwind | กายภาพ (ประชิด) | Vortex Slash Lv1 | `6s` | `10 (+5/lv)` | `+0.75/lv` | Warrior |
| 🏹 Arrow Shower | กายภาพ (ระยะไกล) | Steady Hands Lv1 | `4s` | `7 (+3/lv)` | `+0.3/lv` | Scout |

> [!TIP]
> **Thunder Storm** คุ้มมานาต่อดาเมจสุด (2.5/15 มานา เทียบ Fireball 1/15) — ตัวหลักฟาร์มที่ควรเรียนก่อน ทั้งคู่มี CD แค่ 1 วิ ทำให้ **มานาคือคอขวดจริง ไม่ใช่คูลดาวน์**

---

## 🎒 ชุดอุปกรณ์แนะนำ (ช่วง Lv 130-145)

### Arcane Set — เกราะหลัก (4 ชิ้น, คราฟต์ที่ Starfall Tundra ด้วย Candy Cane x200/ชิ้น)

| ชิ้น | Stat | Bonus พิเศษ |
|---|---|---|
| Arcane Chest | Def+5(+1/lv), Mdef+20(+1/lv) | **Mp+20%, Mp Regen+100%** |
| Arcane Legs | Def+2(+1/lv), Mdef+10(+1/lv) | Mp Regen+20%, Matk+3%, Atk+3% |
| Arcane Boots | Def+2(+1/lv), Mdef+10(+1/lv) | Move Spd+10%, ร่ายไม่โดนขัดจังหวะ, Free Cast Lv.3 |
| Arcane Gloves | Def+1(+1/lv) | Grants Lv.5 Heal ฟรี, Grants Lv.5 Haste ฟรี |

> [!TIP]
> เข้ากับ build นี้มาก — Mp Regen รวมกัน 120%+ ตรงจุดคอขวดของ Thunder Storm (มานา 30+15/lv) แถม Free Cast/uninterruptible cast ทำให้สแปมสกิลได้ลื่นไม่โดนขัดจังหวะ

**ดรอปจาก:** Mega Ice Golem (บอส Lv140), Vanilla Ice (133), Twinkle (135), Festive Baby (132), Shadow Ice (134) — ทั้งหมดอยู่โซน Starfall Tundra ตรงกับช่วงเลเวลที่เพิ่งเปลี่ยนเป็น Weaver พอดี

### อาวุธ: Skybreaker Staff (Wind Staff, 3 slots) — ตัวเทพสำหรับ build นี้โดยเฉพาะ

- Atk+5(+0.5/lv), **Matk+25(+2.5/lv)**
- Cast Speed+15%
- **Thunder Storm Damage+15% (+2%/Lv)**
- Thunder Storm Cast Time -1
- Thunder Storm ไม่มี autocast delay

ทำที่ Windy Desert ใช้ Foxtail 50 ชิ้น — ไม้เท้านี้แทบทำมาเพื่อ Thunder Storm build ตรงๆ ควรหามาใส่เป็นอันดับแรก

> [!NOTE]
> ชุด Arcane ไม่มี headgear ในเซ็ต — เช็ค Mystic Hood แล้วแต่เป็นไอเทมที่ "เพิ่มดาเมจที่รับจากธาตุ Holy/Shadow/Undead/Poison" (ข้อเสีย ไม่ใช่ข้อดี) ไม่แนะนำ ยังไม่เจอหมวกที่เข้าทางสายนี้ชัดเจน ต้องหาข้อมูลเพิ่ม

---

## 🌟 Build ฟาร์ม (สายเวท) — แนะนำเป็นหลัก

```
Thunderbolt Lv1 → Thunder Storm (max)        ← ดาเมจหลัก
Firebolt Lv1    → Fireball (max)             ← สลับธาตุเวลามอน resist ฟ้า
Earthbolt/Icebolt → Earth Spikes/Ice Shard   ← ถ้า point เหลือ ครบ 4 ธาตุ
```

- **สเตต:** INT + Max SP (ไม่ใช่ STR/VIT) — มานาคอสต์ขึ้นไว (+15/lv)
- **เกียร์:** ลด Cooldown / เพิ่ม SP Regen + กริมัวร์ Wizard/Mage (ลดมานาธาตุ)
- **วิธีเล่น:** เล่นเหมือน Wizard ย่อ — สลับธาตุตามจุดอ่อนมอน สแปมได้เพราะ CD 1 วิ

## 🗡️ สาย Bash (ประชิด) — ทางเลือกรอง

| หัวข้อ | รายละเอียด |
|---|---|
| สกิลหลัก | Bash, Impale, Piercing Flurry → **Whirlwind** (AOE) |
| ข้อดี | มานาคอสต์ต่ำกว่าสายเวทมาก (`10+5/lv` เทียบ `30+15/lv`), ไม่ต้องบริหารมานาหนัก |
| ข้อเสีย | Whirlwind คูลดาวน์ `6s` — ช้ากว่า Thunder Storm ถึง 6 เท่า, ดาเมจ/มานา ด้อยกว่าสายเวทชัดเจนจากตัวเลขที่มี |

> [!WARNING]
> ยังไม่มีข้อมูลตัวเลขของ **Bash, Impale, Piercing Flurry, Blade Dance** (ยังไม่ได้ดึงหน้าสกิลพวกนี้) ต่างจากสายเวทที่เช็คครบแล้ว — จากข้อมูลเท่าที่มี **สายเวทคุ้มกว่าสาย Bash ชัดเจน** แต่ยังสรุปเต็มไม่ได้จนกว่าจะมีตัวเลขของสกิลกลุ่มนี้

---

> [!IMPORTANT]
> **สิ่งที่ยังไม่ยืนยัน ต้องทดสอบในเกม:**
> - ตาราง SP cost แบบเต็มของทุกสกิล
> - Thunder Storm ที่แปะป้าย "water-touch" นับเป็น 2 ธาตุ (ลม+น้ำ) ตอนคิด resist หรือไม่
> - ตัวเลขดาเมจ/คูลดาวน์ของสาย Bash (Bash, Impale, Piercing Flurry, Blade Dance)

---
*อ้างอิงจาก spiritvalewiki.com · เนื้อหายังเป็น theorycraft รอข้อมูลจากการเล่นจริง*
