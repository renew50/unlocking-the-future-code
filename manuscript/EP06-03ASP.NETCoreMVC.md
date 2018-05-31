# โครงสร้างโปรเจค ASP.NET Core MVC

* เมื่อทำการรัน server ของโปรเจค โดยไปที่ Debug->Start Without Debugging (หรือกดคีย์ลัด Ctrl+F5)  
![img](EP06-03ASP.NETCoreMVC/01.PNG)
---
* เมื่อรัน Server สำเร็จ ก็จะทำการเปิด Website ขึ้นมา  
![img](EP06-03ASP.NETCoreMVC/02.PNG)
---
>เราจะไปดูกันว่า สิ่งที่ทำให้ Server สามารถเปิดหน้า Website นี้ขึ้นมาให้เราได้ มีส่วนประกอบอะไรบ้าง

1.  Server จะทำการ run จากไฟล์ Startup.cs  
![img](EP06-03ASP.NETCoreMVC/03.PNG)
---
2. เมื่อเข้าไปดูที่ไฟล์ Startup.cs เและลื่อนลงไปด้านล่างสุด จะมี default routing  
![img](EP06-03ASP.NETCoreMVC/04.PNG)
---
3. ซึ่ง default จะวิ่งไปที่ controller ที่ชื่อว่า Home กับ action ที่ชื่อว่า Index  
![img](EP06-03ASP.NETCoreMVC/08.PNG)
---
4. จากนั้นลองกดไปที่ Controllers คลิกที่ไฟล์ HomeController.cs จะปรากฏ action ที่ชื่อว่า Index อยู่ ซึ่งจะเห็นว่าภายใน Index() จะมี View  
![img](EP06-03ASP.NETCoreMVC/09.PNG)
---
5. ลองกดไปที่ View->Home คลิกที่ไฟล์ Index.cshtml จะปรากฏไฟล์ HTML ที่ Server นำมาแสดงผลเป็น Website จากที่ได้รันไปข้างต้น  
![img](EP06-03ASP.NETCoreMVC/11.PNG)
---
6. ซึ่งทุกอย่างที่เห็นจากฝั่งซ้ายมือ คือซึ่งที่เกิดจากไฟล์ HTML ในฝั่งขวามือ  
![img](EP06-03ASP.NETCoreMVC/12.PNG)
---
7. และหากเราลองทำการแก้ไข Code จากไฟล์ Index.cshtml ตัว Website ก็จะเปลี่ยนตามไปด้วย  
![img](EP06-03ASP.NETCoreMVC/14.PNG)

---
### VDO Link :  

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/tpMTZClsE6Y/0.jpg)](http://www.youtube.com/watch?v=tpMTZClsE6Y)