# Lenezong

เว็บไซต์ Lenezong

## สกิลออกแบบที่ติดตั้งไว้

repo นี้เปิดใช้ plugin ของ Claude Code 3 ตัวผ่าน `.claude/settings.json` เพื่อให้เว็บที่ Claude สร้างไม่ดูเป็นงาน AI ทั่วไป

| ขั้น | Plugin | ใช้ทำอะไร |
|---|---|---|
| 1 | `superpowers` (สกิล brainstorming) | ถามโจทย์ให้ชัดและเขียนสเปกก่อนลงมือ |
| 2 | `taste-skill` | กฎด้านดีไซน์ ไอคอนจริงจาก Lucide และ Simple Icons และตัวตรวจในเบราว์เซอร์จริงว่ามีอะไรทับกันหรือล้นจอ (1440, 1024, 768, 390px) |
| 3 | `impeccable` | ตรวจและขัดเกลางานดีไซน์ให้เนียนขึ้น |

ถ้าเปิด repo นี้ใน Claude Code บนเครื่องตัวเอง Claude Code จะถามให้ติดตั้ง plugin ตามการตั้งค่านี้เมื่อเชื่อถือโฟลเดอร์ (trust) แล้ว taste-skill ต้องใช้ Node 22 ขึ้นไปและ Chrome, Edge หรือ Chromium
