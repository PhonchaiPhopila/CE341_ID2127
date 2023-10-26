![Screenshot 2023-10-26 150233](https://github.com/PhonchaiPhopila/CE341_ID2127/assets/143696679/36e0a3ed-e2ae-4155-9e96-9acba64285e8)run ระบบปฏิบัติการ Ubuntu 20 แล้วทำการติดตั้ง Application apache2 และ Git แล้วทำการ pull หรือ clone ตัว repository จาก GitHub ของตนเองมา run เริ่มต้นจากกร Github และ สร้าง repository นำไฟล์ index.html เป็นไฟล์หน้าเว็บ Sync ไฟล์ บน VS Code กับ Github 
![Screenshot 2023-10-26 154049](https://github.com/PhonchaiPhopila/CE341_ID2127/assets/143696679/f3f8d635-4814-408f-b6cc-58970ed3d6a1)
เปิด Ubuntu หา ip ของเรา ด้วยคำสั่ง ip a และนำเลข ip ไปใส่ใน Web browser จะเป็น apache ทำงานแทน
![Screenshot 2023-10-26 150233](https://github.com/PhonchaiPhopila/CE341_ID2127/assets/143696679/e419ee5f-44c0-4367-8a75-5ebe92a9fa0a)
เมื่อไม่ขึ้นหน้าเว็บของ apache ให้ทำการ start หรือ resteat apache 
เมื่อ apache ทำงานให้ทำงาน ย้ายไฟล์ index.html ของเรา แทนที่ ใน ver/www/html โดยใช้คำสั่ง sudo mv index.html /ver/www/html/
ทำการรีหน้าเว็บ หน้าเว็บ apache จะเป็นเว็บของเรา
![Screenshot 2023-10-26 153806](https://github.com/PhonchaiPhopila/CE341_ID2127/assets/143696679/8ba612ae-5884-4c9e-b15d-04420d3208b0)
