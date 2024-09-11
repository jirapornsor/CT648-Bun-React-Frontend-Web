## CT648-Bun-React-Frontend-Web
## โปรเจคนี้เป็นการเรียนรู้การใช้ React + TypeScript + Bun และการใช้งาน Public Rest API
### หลักการออกแบบ
#### ออกแบบให้หน้าเว็บแสดง 3 ส่วน คือ
1. DataDisplay จะจัดการการแสดงผลข้อมูลมุขตลก โดยการดึงข้อมูลจาก API และแสดงข้อมูล Joke แบบสุ่มพร้อมกับรูปภาพโปเกมอน ใช้ useEffect เพื่อทำให้คอมโพเนนต์อัปเดต joke ทุกๆ 15 วินาที
2. PokemonTable จะจัดการการแสดงผลข้อมูลตัวอย่างชื่อ Pokémon ในรูปแบบตาราง
3. DataDisplay_pok จะจัดการการดึงและแสดงข้อมูลเกี่ยวกับ Pokémon จาก PokéAPI โดยมีช่องให้กรอกชื่อ Pokémon แล้วกด Search ก็จะโชว์รูปและข้อมูลของ Pokémon

#### ขั้นตอนการสร้าง
1. สร้างโปรเจกต์ React ด้วย Vite โดยใช้ bun ด้วยคำสั่ง
   ```bash
   bun create vite my-react-app --template react-ts
   ```
   
   
