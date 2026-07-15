# 💀 Necromancer — เจ้าแห่งความตาย

![Level Gate](https://img.shields.io/badge/เปลี่ยนอาชีพ-Lv%2026--30-7c5cd6?style=flat-square)
![Class Change](https://img.shields.io/badge/สถานที่-Festering%20Woods%202-0e9c8f?style=flat-square)
![Tier](https://img.shields.io/badge/Tier%20(v2)-C%20(wildcard)-a3720a?style=flat-square)

> จาก Summoner → Necromancer "A dark summoner who commands the dead and drains the living, winning through attrition and decay."

---

## 📜 Summoner (base class)

"A binder of spirits" — ต่อสู้ผ่านพันธมิตรที่เรียกมา ("fights through conjured allies, overwhelming foes with numbers")

| กลุ่ม | สกิล |
|---|---|
| 🐾 Summon | Summon Angel, Summon Cactus, Summon Cat, Summon Wolf |
| 🎗️ Support | Summon Mastery, Resonance Well, Suppression Field, Dissonance Well |
| ⚔️ Combat | Soul Strike, Banishment Field, Conjurer, Guardian Bond, Fury Bond, Invoker, True Sight |
| 🎮 Control | Summon Command, Summon Recall, Summon Swap, Summon Mount |

**Grimoires:** Alpha Surge, Hexwell Current, Banishment Well, Resonant Wind, Blessed Resonance, Soul Chains

## 📜 Necromancer (advanced)

Summon: Abomination, Skeleton, Skeleton Mage, Wraith, Reanimation
Offense: Bone Spear, Bone Spikes, Death Coil, Corpse Explosion
Defense: Corpse Barrier
Utility: Life Drain, Soul Drain, Harvest, Reap, Death Nova, Death Spiral, Necrotic Presence

---

## 👻 แพตช์ Ghost Element — กระทบตรงจุด

> [!IMPORTANT]
> แพตช์ล่าสุดเพิ่มธาตุ Ghost ใหม่ และ **แปลงสกิล Summoner ทั้งหมดเป็นธาตุ Ghost** — สำคัญ: นี่หมายถึงสกิลซัมมอนของ **Summoner (base class)** เช่น Summon Angel/Cactus/Cat/Wolf ที่ Necromancer ยังใช้ได้อยู่ ส่วนสกิลเฉพาะของ Necromancer เอง (Bone Spear = Undead, ที่เหลือ = Neutral) ไม่ได้รับผลกระทบโดยตรง
>
> ผลลัพธ์ยังทายไม่ได้ — ถ้ามอนส่วนใหญ่ resist Ghost ต่ำ จะเป็นบัฟใหญ่ให้มินเนี่ยนสายเก่า ถ้า resist สูง จะเป็นเนิร์ฟ ต้องรอตาราง element resist มายืนยัน

---

## ⚔️ ตารางสกิลที่ยืนยันแล้ว

| สกิล | ธาตุ | Max Lv | คูลดาวน์ | มานา | ดาเมจ/lv | ต้องเรียนก่อน |
|---|---|---|---|---|---|---|
| 🦴 Bone Spear | Undead | 5 | ไม่ระบุ | `10 (+5/lv)` | `+0.67/lv` | ไม่ระบุ |
| ☠️ Death Coil | Neutral | 5 | `3s` | `20 (+10/lv)` | ไม่ระบุ | - |
| 🩸 Life Drain | Neutral | 5 | `3s` | `20 (+10/lv)` | ไม่ระบุ | Death Coil Lv1 |
| 💥 Corpse Explosion 🏆 | Neutral | 10 | `1s` | `20 (+10/lv)` | ไม่ระบุ | Corpse Barrier Lv1 |

> [!TIP]
> **Corpse Explosion** คูลดาวน์แค่ 1 วิ (เหมือนแพทเทิร์น Thunder Storm ของ Weaver) และเป็น AOE — "Detonate a skeleton summon in a burst of necrotic force" คือต้องมี **Skeleton summon อยู่ใกล้ๆ** ถึงจะจุดระเบิดได้ ต่างจาก nuke ปกติที่ยิงตรงได้เลย

> [!WARNING]
> วิกิไม่มีตัวเลขดาเมจที่ชัดเจนของสกิลกลุ่มนี้เลย (Death Coil, Life Drain, Corpse Explosion ไม่มี dmg scaling ระบุ) — ข้อมูลไม่สมบูรณ์กว่าฝั่ง Weaver/Paladin มาก ต้องพึ่งการทดสอบในเกมเป็นหลัก

---

## 🌟 แนวทางเล่น (ทฤษฎี — ข้อมูลยังไม่ครบเท่าคลาสอื่น)

**คอนเซปต์หลัก:** ปล่อย **Skeleton** ยืนระยะ, ใช้ **Life Drain/Death Coil** เพื่อดูดเลือดและฮีลมินเนี่ยนไปพร้อมกัน, จุด **Corpse Explosion** เวลามอนตายเยอะๆ ใกล้กัน

**ลำดับที่น่าจะสมเหตุสมผล:**
1. Summon Skeleton — ตัวตั้งของสายมินเนี่ยน
2. Corpse Barrier → Corpse Explosion — AOE คูลดาวน์สั้น
3. Death Coil → Life Drain — sustain คู่ดาเมจ
4. Bone Spear — ดาเมจเสริมทะลุระยะ (Undead type)

> [!CAUTION]
> ความเสี่ยงหลักของคลาสนี้ตามที่วิเคราะห์ไว้คือ **AI/pathing ของมินเนี่ยน** — ถ้ามินเนี่ยนเดินโง่หรือตามไม่ทัน ประสิทธิภาพทั้งคลาสจะตกทันที เป็นความเสี่ยงที่ตัวเลขสกิลอย่างเดียวบอกไม่ได้ ต้องลองเล่นจริง

---

## 🎒 ชุดอุปกรณ์

> [!NOTE]
> **ยังไม่เจอชุดที่ตรงช่วง Lv26-30 พอดี** (ช่วงเพิ่งเปลี่ยนอาชีพ) ใกล้สุดที่เจอคือ Gravemarrow Set ซึ่งดรอปช่วง Lv36-40 — ห่างจากช่วงเปลี่ยนอาชีพราว 10 เลเวล ถือว่าใกล้กว่ากรณี Paladin แต่ก็ยังไม่ตรงเป๊ะ

### Gravemarrow Set (ใกล้เคียงช่วงต้นสุดที่เจอ, Lv36-40)
| ไอเทม | Stat | Bonus |
|---|---|---|
| Gravemarrow Chest | Def+15(+1/lv), Mdef+15(+1/lv), Hp+20% | Damage Status+15%, Resistance to Bleeding+50% |

คราฟต์: Larva ×50 ที่ Swamp · ดรอป: Dragonfly Arrow (Lv36), Plant Shooter (Lv38), Dragonfly Darner (Lv39), Mosquito Pester (Lv40) — ทั้งหมด 4%
ชุดเต็ม: Gravemarrow Chest + Legs + Shoes

### Necronomicon — เป้าหมายอัพเกรดระยะยาว (Lv107-130)
| Stat | Bonus |
|---|---|
| Atk+10(+1/lv), Matk+25(+2.5/lv) | Buff Duration+25%, **Summon Skeleton Lv+1**, **Summon Skeleton Mage Lv+1**, Summon Resist+1%/lv, **Undead Damage+2%/lv** |

หนังสือ Undead 2 slots ที่บัฟมินเนี่ยนโดยตรง — ตัวเทพของสายนี้ แต่ดรอปช้ามาก (Death Mage บอส Lv130 เท่านั้นที่ให้โอกาสดีสุด 5%) เก็บไว้เป็นเป้าหมายระยะยาว ไม่ใช่ของช่วงต้น

---
*อ้างอิงจาก spiritvalewiki.com + แพตช์โน้ตจาก dev · เนื้อหายังเป็น theorycraft รอข้อมูลจากการเล่นจริง — ข้อมูลตัวเลขของคลาสนี้ไม่ครบเท่า Weaver/Paladin*
