# EP 06-03 Structure Project ASP.NET Core MVC

### โครงสร้างโปรเจค ASP.NET Core MVC

* เมื่อทำการ run server ของโปรเจค โดยไปที่ Debug -> Start Without Debugging (หรือกดคีย์ลัด Ctrl+F5)  

![](images/EP06/01.PNG)

* * *

* เมื่อ run Server สำเร็จ ก็จะทำการเปิด Website ขึ้นมา  

![](images/EP06/02.PNG)

* * *

### เราจะไปดูกันว่า สิ่งที่ทำให้ Server สามารถเปิดหน้า Website นี้ขึ้นมาให้เราได้ มีส่วนประกอบอะไรบ้าง


1) Server จะ run จากไฟล์ Startup.cs  

![](images/EP06/03.PNG)

* * *

2) เมื่อเข้าไปดูที่ไฟล์ Startup.cs เและเลื่อนลงไปด้านล่างสุด จะมี default routing  

![](images/EP06/04.PNG)

* * *

3) ซึ่ง default จะวิ่งไปที่ controller ที่ชื่อว่า Home กับ action ที่ชื่อว่า Index  

![](images/EP06/08.PNG)

* * *

4) จากนั้นลองกดไปที่ Controllers คลิกที่ไฟล์ HomeController.cs จะปรากฏ action ที่ชื่อว่า Index อยู่ ซึ่งจะเห็นว่าภายใน Index() จะมี View  

![](images/EP06/09.PNG)

* * *

5) ลองกดไปที่ View -> Home คลิกที่ไฟล์ Index.cshtml จะปรากฏไฟล์ HTML ที่ Server นำมาแสดงผลเป็น Website จากที่ได้ run ไปข้างต้น  

![](images/EP06/11.PNG)

* * *

6) ซึ่งทุกอย่างที่เห็นจากฝั่งซ้ายมือ คือสิ่งที่เกิดจากไฟล์ HTML ในฝั่งขวามือ 

![](images/EP06/12.PNG)

* * *

7) และหากเราลองแก้ไข Code จากไฟล์ Index.cshtml ตัว Website ก็จะเปลี่ยนตามไปด้วย  

![](images/EP06/14.PNG)

* * *

[VDO Link : ](http://www.youtube.com/watch?v=tpMTZClsE6Y)

[![](images/EP06/00.PNG)](http://www.youtube.com/watch?v=tpMTZClsE6Y)