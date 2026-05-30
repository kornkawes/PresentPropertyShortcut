# HOME Real Estate Interactive Pitch

เว็บพรีเซนต์แบบ Interactive สำหรับนำเสนอ HOME Real Estate Internal Tool / AI & Automation Initiative

## วิธีรันในเครื่อง

```bash
npm install
npm run dev
```

## วิธี Build

```bash
npm run build
```

ไฟล์เว็บที่ build แล้วจะอยู่ในโฟลเดอร์ `dist/`

## วิธี Deploy บน GitHub Pages

1. สร้าง GitHub repository ใหม่
2. Upload ไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น repo
3. ไปที่ Settings > Pages
4. Source เลือก GitHub Actions
5. Push แล้วระบบจะ build/deploy อัตโนมัติ

## จุดที่แก้บ่อย

- เปลี่ยนลิงก์แอปจริง: แก้ที่ `src/App.jsx` ใน `<iframe src="..." />`
- แก้ข้อความพรีเซนต์: แก้ใน array `features`, `roadmap`, `stats`
- แก้สีธีม: ค้นหา `#0F2922` และ `yellow-400`
