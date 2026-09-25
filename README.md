<div align="center">

# 🦖 Devgotchi DB Setup Power

### 🐘 PostgreSQL + 🌿 Drizzle ORM — พร้อมใช้งานในคำสั่งเดียว

[![Kiro Power](https://img.shields.io/badge/Kiro-Power-8A2BE2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,&logoColor=white)](https://kiro.dev)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Bun](https://img.shields.io/badge/Bun-Runtime-FBF0DF?style=for-the-badge&logo=bun&logoColor=black)](https://bun.sh)
[![Drizzle](https://img.shields.io/badge/Drizzle-ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)](https://orm.drizzle.team/)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen?style=for-the-badge)](#)

</div>

---

## ✨ ภาพรวม

**Devgotchi DB Setup** เป็น Kiro Power ที่ช่วยให้คุณ **spin up ฐานข้อมูล PostgreSQL ผ่าน Docker** และ **รัน Drizzle ORM migrations** ได้อัตโนมัติ ด้วยการรันเพียงคำสั่งเดียว 🚀

> 🎓 สร้างขึ้นเป็นส่วนหนึ่งของ **Kiro University Challenge (Bonus Lesson 2)**

---

## 🧩 ความสามารถ

| 🔧 ฟีเจอร์ | 📋 รายละเอียด |
|:---|:---|
| 🐳 **Docker Compose** | สั่ง `docker-compose up -d db` เพื่อรันคอนเทนเนอร์ฐานข้อมูลแบบ background |
| 🌿 **Drizzle Migration** | รัน `bun x drizzle-kit push` เพื่อซิงก์ schema เข้าฐานข้อมูลทันที |
| ⚡ **One-command Setup** | ไม่ต้องสลับไปมาระหว่าง terminal หลายอัน |

---

## 📦 ความต้องการของระบบ

- 🐳 **Docker** & **Docker Compose**
- 🥟 **Bun** runtime

---

## 🚀 วิธีใช้งาน

1. คัดลอก Power นี้ไปไว้ที่โฟลเดอร์ `.kiro/powers/` ของโปรเจกต์คุณ
2. หรืออ้างอิงตรงในไฟล์ config ของ Kiro workspace
3. รัน Power เพื่อให้ Kiro จัดการ setup ฐานข้อมูลให้อัตโนมัติ ✅

```yaml
name: devgotchi-db-setup
version: 1.0.0
execute: |
  docker-compose up -d db
  bun x drizzle-kit push
```

---

## ⚙️ Dependencies

<div align="center">

🐳 `docker` &nbsp;&nbsp;|&nbsp;&nbsp; 🥟 `bun`

</div>

---

<div align="center">

👤 สร้างโดย **KOngphob03**

🦖 *Happy coding with Devgotchi!*

</div>
