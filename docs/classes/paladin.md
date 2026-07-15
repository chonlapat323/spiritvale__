# 🛡️ Paladin — อัศวินผู้ทอแสงศักดิ์สิทธิ์

![Level Gate](https://img.shields.io/badge/เปลี่ยนอาชีพ-Lv%2076--80-7c5cd6?style=flat-square)
![Class Change](https://img.shields.io/badge/สถานที่-Sanctum%20of%20Light-0e9c8f?style=flat-square)
![Tier](https://img.shields.io/badge/Tier%20(v2)-A-1c9a5b?style=flat-square)

> จาก Knight → Paladin "Fuses shield and sanctity, protecting allies while smiting the wicked with blessed force."

> [!IMPORTANT]
> **แหล่งข้อมูลหลัก = แพตช์โน้ตจาก dev เท่านั้น** วิกิยังมีข้อมูลบางส่วนล้าหลังกว่าแพตช์จริง (ยืนยันแล้วกรณี Sacrifice) — ดู [README.md](../../README.md) เรื่อง source priority

---

## 📜 สกิลทั้งหมด

**Paladin:** High Guard, Holy Shield, Aegis of Light, Judgement Blade, Divine Punishment, Grand Cross, Life Bond, Sanctify, Defiance Aura, Vitality Aura, Conviction Aura, Shield Bash, Shield Throw, Faith, Sacrifice, Consecration, Gryphon Riding

**Knight (base class):** Taunt, Spear Mastery, Shield Mastery, Endure, Piercing Flurry, Fortify, Twohand Parry, Impale, Reflect Shield, Increased Regeneration, Air Cutter, Spear Quicken, Weapon Throw, Counter Stance

## 🔧 สรุปแพตช์ล่าสุด

| สกิล | ผล | 
|---|---|
| 🟢 Sacrifice | รีเวิร์กเป็นดาเมจ single-target ทะลุเดฟ (ดูรายละเอียดด้านล่าง) |
| 🟢 Shield Bash / Shield Throw | **ดาเมจ +30%** |
| 🔴 Consecration | เสีย regen buff |
| 🔴 Holy Shield | เสีย all-resistance buff (เหลือแค่ Block) |
| 🔴 Judgement Blade | ดาเมจ -25%, ไม่ trigger hit effect |
| 🔴 Grand Cross | ไม่ trigger hit effect |
| 🔴 Oathbreaker | เสีย +1 matk/str → ได้ +10% block แทน |

> [!NOTE]
> ผลรวม: ดันไปทาง **pure shield-tank** มากขึ้น แต่ยังมีดาเมจจริงจาก Sacrifice — ดู [../patch-notes.md](../patch-notes.md) สำหรับรายละเอียดแพตช์เต็ม

---

## ⚔️ สายสกิลที่ยืนยันแล้ว (Shield Chain)

`Faith → Holy Shield → Shield Bash → Shield Throw` (Sacrifice แยกออกจาก Faith โดยตรง)

| สกิล | Max Lv | คูลดาวน์ | มานา | ต้องเรียนก่อน | หมายเหตุ |
|---|---|---|---|---|---|
| Holy Shield | 5 | - | `20` | Faith Lv1+ | Block เท่านั้น (all-resist ถูกตัดแล้ว) |
| ⚡ Shield Bash 🏆 | 5 | `3s` | `7 (+3/lv)` | Holy Shield Lv1+ | "crumble defenses" — โดนบัฟ +30% |
| ⚡ Shield Throw 🏆 | 10 | - | `5 (+2/lv)` | Shield Bash Lv1+ | AOE หลายเป้าหมาย — โดนบัฟ +30% |
| 💥 Sacrifice | 5 | - | `20` | Faith Lv1+ | ดาเมจทะลุเดฟ ดูด้านล่าง |

> [!WARNING]
> วิกิยังไม่มีตัวเลข damage scaling จริงของสกิลเหล่านี้ (ขึ้น 0 ทั้งหมด) — ยังเป็นข้อมูลไม่สมบูรณ์จากตัววิกิเอง ไม่ใช่แค่การเดาของเรา

### 🔍 ปริศนา "Oathbreaker"
แพตช์โน้ตพูดถึงสกิล Oathbreaker แต่ **ไม่มีอยู่ในรายชื่อสกิลของ Paladin หรือ Knight บนวิกิเลย** อาจเป็นสกิลที่วิกิยังไม่อัพเดต หรือสกิลลับ/ปลดล็อกด้วยเควส ต้องเช็คซ้ำภายหลัง

---

## 💥 Sacrifice — วิเคราะห์ลึก

| | วิกิ (เก่า, ยังไม่อัพเดต) | แพตช์จริง |
|---|---|---|
| กลไก | Passive on-hit — เผา HP ตัวเองแลกดาเมจ Holy เพิ่มทุกการตี | **โจมตี single-target ครั้งเดียว** |
| ดาเมจ | (ไม่มีดาเมจตรงๆ) | 5-10% HP เป้าหมาย |
| Defense | - | **ทะลุเดฟ (ignore defense)** |

> [!CAUTION]
> นี่คือการเปลี่ยนกลไกทั้งหมด ไม่ใช่แค่ปรับตัวเลข — วิกิล้าหลังกว่าแพตช์จริงยืนยันแล้วในจุดนี้

**คำนวณ (ยืนยันจากผู้ใช้):** ดาเมจน่าจะอิง **Max HP ไม่ใช่ current HP** — เพราะ 10 ครั้ง × 10% = 100% พอดี (ถ้าอิง current HP จะไม่มีวันตีจนตายพอดีแบบ Zeno's paradox)

→ **ไม่ต้องรีบยิงตอนบอสเลือดเต็ม** ดาเมจเท่ากันทุกจังหวะ ใช้เมื่อไหร่ก็ได้ผลเท่ากัน
→ เฉลี่ย 10-20 ครั้งฆ่าได้ (5-10% roll), ยังไม่รวมดาเมจจากสกิลอื่น

> [!WARNING]
> ยังไม่ยืนยันว่า Sacrifice เผา HP ตัวเองเป็นต้นทุนหรือไม่ (ตามคำอธิบายเก่าบนวิกิ) ถ้าใช่ ต้องพก Life Bond คู่กันเสมอ ต้องทดสอบในเกม

---

## 🏆 Reassessment

Sacrifice ที่ทะลุเดฟ + Shield Bash/Throw ที่โดนบัฟ ทำให้ Paladin หลังแพตช์มีดาเมจจริงมากกว่าที่ประเมินไว้ตอนแรก **Tier: A** — แทงค์แข็งแรง + มีดาเมจทะลุเดฟจริงสำหรับบอส/มอนเดฟสูง ดู [../tier-list.md](../tier-list.md)

---

## 🎒 ชุดอุปกรณ์ช่วงต้น (พอเปลี่ยนอาชีพ Lv 76-90)

| ไอเทม | ประเภท | Stat | Bonus |
|---|---|---|---|
| 🛡️ **Sanctum Guard** | โล่ (1 slot) | Def+15(+1/lv), Mdef+15(+1/lv), **Block+30%** | Healing Received+5%(+2%/lv), Consecration CD-2 / Skill Lv+2 |

**คราฟต์:** Antique Teacup ×100 ที่ **Sanctum of Light** (โซนเดียวกับที่เปลี่ยนอาชีพ Paladin พอดี)
**ดรอป:** Angel Mage (บอส Lv90, 10%), Phantom (Lv83, 2%)

> [!WARNING]
> โล่ตัวนี้บัฟ **Consecration** โดยตรง (ลด CD, เพิ่มเลเวลสกิล) แต่ Consecration เพิ่งโดนเนิร์ฟ (เสีย regen buff) ในแพตช์นี้ — โบนัสของโล่ยังใช้ได้ แต่ตัวสกิลที่มันบัฟอยู่อ่อนลงกว่าก่อนแพตช์

> [!NOTE]
> **ยังไม่เจอชุดเกราะ (chest/legs/boots) ที่ตรงช่วงเลเวล 76-90 พอดี** ชุดที่ใกล้เคียงอย่าง Sanctified Set (Chest/Legs/Shoes) และ Endurance Set ล้วนดรอปจากมอนสเตอร์ Lv110-130 ซึ่งเกินช่วงเพิ่งเปลี่ยนอาชีพไปมาก — ใส่เกราะทั่วไปตามเลเวลไปก่อน แล้วอัพเกรดเป็น Sanctified Set ช่วง Lv110+ ได้ ต้องหาข้อมูลชุดเกราะช่วง 76-90 เพิ่มเติม

### Sanctified Set (เป้าหมายอัพเกรดช่วง Lv110-130)
| ชิ้น | Stat | Bonus |
|---|---|---|
| Sanctified Chest | Def+15(+1/lv), Mdef+15(+1/lv), Hp+20% | Hp+10%, **Healing Received+10%** |

คราฟต์: Marble ×200 ที่ Abyss Castle Crypt · ดรอป: Wraith (Lv125, 5%), Death Mage (Lv130, 5%), Mimic Treasure Chest (Lv110, 2%)

---

## 🌟 Build แนะนำ: "Shield Breaker Tank"

**ลำดับเรียนสกิล:**
1. Faith (root)
2. Holy Shield — ปลดล็อก Shield Bash
3. **Shield Bash** (max Lv5) — เปิดคอมโบ, CD 3 วิ, +30% dmg
4. **Shield Throw** (max Lv10) — AOE เคลียร์กลุ่ม, +30% dmg
5. **Sacrifice** (max Lv5) — ดาเมจหลักทะลุเดฟ ใช้ได้ทุกจังหวะ
6. Life Bond — sustain ชดเชยที่หายไป
7. เลือก 1 Aura (Vitality/Defiance/Conviction — อย่ากระจาย point)
8. High Guard / Aegis of Light — เสริมพื้นฐาน

**ข้ามได้เลย:** Judgement Blade, Grand Cross, Divine Punishment, Sanctify, Consecration, Gryphon Riding (มีทีหลังสุดได้)

**สเตต:** STR/VIT ตรงๆ มากกว่า %dmg-stacking (การ์ดดาเมจถูกตัดออกจากระบบไปเยอะ)

**Rotation:**
```
เดี่ยว/บอส   : Shield Bash (เปิด) → Sacrifice (ดาเมจหลัก) → สลับตามคูลดาวน์
กลุ่ม/ฟาร์ม  : Shield Throw หลัก, Shield Bash เก็บตัวที่เหลือ
ตลอดเวลา    : เปิด Aura ค้างไว้
```

> [!IMPORTANT]
> **ยังไม่ยืนยัน:** ต้นทุน HP จริงของ Sacrifice, ตาราง SP cost แบบเต็มของแต่ละสกิล (มีแค่ลำดับความสำคัญ ไม่ใช่งบ point แบบละเอียด)

---
*อ้างอิงจาก spiritvalewiki.com + แพตช์โน้ตจาก dev · เนื้อหายังเป็น theorycraft รอข้อมูลจากการเล่นจริง*
