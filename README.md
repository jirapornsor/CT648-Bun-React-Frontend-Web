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
2. เปลี่ยนตำแหน่งไปที่โฟลเดอร์ my-react-app ที่เพิ่งสร้างขึ้น
   ```bash   
   cd my-react-app
   ```
3. ติดตั้งไลบรารี Axios ในโปรเจกต์ที่ใช้ Bun เป็นตัวจัดการแพ็กเกจที่ช่วยให้คุณทำคำขอ HTTP ได้ง่ายขึ้น (เช่น GET, POST) เพื่อเชื่อมต่อกับ API หรือเว็บเซอร์วิสอื่นๆ
   ```bash   
   bun add axios
   ```
4. สร้างโฟลเดอร์ชื่อ components ภายในโฟลเดอร์ src และสร้างไฟล์ชื่อ DataDisplay.tsx  , PokemonTable.tsx  , DataDisplay_pok.tsx  ภายในโฟลเดอร์ src/components
   - คำสั่งสร้างโฟลเดอร์
   ```bash   
   mkdir src/components
   ```
   - คำสั่งสร้างไฟล์สำหรับ Unix/Linux หรือ MacOS
   ```bash   
   touch src/components/DataDisplay.tsx
   ```
   - คำสั่งสร้างไฟล์สำหรับ Windows
   ```bash   
   New-Item -Path "src/components/DataDisplay.tsx" -ItemType File
   ```
5. สร้างโค้ดไว้ในไฟล์ src/components/DataDisplay.tsx เป็นคอมโพเนนต์ React ที่ใช้ TypeScript สำหรับแสดงข้อมูล Joke จาก API แบบสุ่ม โดยใช้ Axios สำหรับทำคำขอ HTTP เพื่อดึงข้อมูลจาก API ภายนอก และยังมีการใช้รูปภาพและไฟล์ CSS เพื่อทำการตกแต่งคอมโพเนนต์
-	ดึงข้อมูลจาก API และแสดงข้อมูล Joke แบบสุ่มพร้อมกับรูปภาพโปเกมอน
   ```bash   
   
   ```
-	ใช้ useEffect เพื่อทำให้คอมโพเนนต์อัปเดต joke ทุกๆ 15 วินาที


   
