# E-Book Application

## About

แอปพลิเคชันสำหรับคนรักหนังสือ พัฒนาขึ้นเพื่อเปลี่ยนหนังสือในรูปแบบ **Physical Book** ให้อยู่ในรูปแบบ **E-Book** เพื่อช่วยถนอมหนังสือ ลดการเสื่อมสภาพจากการใช้งาน และเพิ่มความสะดวกในการพกพาและเข้าถึงหนังสือได้ทุกที่

## My Responsibilities

### Frontend Development

* พัฒนา Mobile Application ด้วย **React Native**
* ออกแบบและพัฒนาหน้าจอสำหรับการใช้งานแอปพลิเคชัน
* เชื่อมต่อ Frontend กับ Backend ผ่าน **REST API**
* จัดการการแสดงผลข้อมูลหนังสือและรูปภาพปกหนังสือ
* พัฒนาฟังก์ชันสำหรับการจัดการและอ่านหนังสือในรูปแบบ E-Book

### Backend Development

* พัฒนา Backend ด้วย **Node.js และ Express**
* พัฒนา REST API สำหรับรับส่งข้อมูลระหว่าง Mobile Application และ Database
* เชื่อมต่อ Backend กับ **MongoDB**
* จัดการข้อมูลหนังสือและข้อมูลที่เกี่ยวข้องกับผู้ใช้งาน

### File & Image Storage

* เชื่อมต่อ **Cloudinary** สำหรับจัดเก็บไฟล์หนังสือในรูปแบบ E-Book
* ใช้ Cloudinary สำหรับจัดเก็บรูปภาพปกหนังสือ
* จัดการ URL สำหรับเข้าถึงไฟล์และรูปภาพจาก Cloudinary

## Technologies

### Frontend

* React Native
* JavaScript
* REST API

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Storage

* Cloudinary

## System Architecture

```text
React Native
     │
     │ REST API
     ↓
Node.js + Express
     │
     ├──────────────→ MongoDB
     │
     └──────────────→ Cloudinary
                       ├── E-Book Files
                       └── Book Cover Images
```

## Project Objective

พัฒนาแอปพลิเคชันที่ช่วยให้ผู้ใช้งานสามารถจัดเก็บหนังสือจากรูปแบบ Physical ให้อยู่ในรูปแบบดิจิทัล เพื่อช่วยลดการเสื่อมสภาพของหนังสือ เพิ่มความสะดวกในการจัดเก็บ และสามารถพกพาหนังสือจำนวนมากไว้ในอุปกรณ์เดียวได้
