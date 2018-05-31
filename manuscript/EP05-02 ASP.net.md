# EP 05-02 ASP.NET CORE + ANGULAR

* ใช้ดูคำสั่งต่างๆของ ASP.NET CORE ใช้คำสั่ง 

A>dotnet -h

* สำหรับการสร้างโปรเจคใช้คำสั่ง 

A>dotnet new 

จะมี Template มาให้เลือก

![](images/EP05-01Dotnet/EP05-02ASP-NET-Core.PNG)

* * *

* คำสั่งเพื่อสร้าง angular

A>dotnet new angular -n demoweb

รอซักครู่เพื่อทำการสร้างโปรเจค (demoweb สามารถตั้งชื่อเองตามที่ต้องการ)

* * *

* เราจะต้องลง npm install เพื่อเพิ่ม packet ใช้คำสั่ง

A>npm install 

ใช้เวลาซักครู่ในการลง npm

* * *

* วิธีเช็คโปรเจ็คติดตั้งเรียบร้อยหรือไม่พิมพ์

A>dotnet build

ใช้เวลาซักครู่เพื่อให้โปรเจค build สามารถเช็คว่ามี error ไหมดูได้ที่นี้  

* * *

* วิธีการเปิดเว็บไซต์  

A>dotnet run  

รอซักครู่เพื่อเตรียม server ในการรันเว็บไซต์ ให้ copy เพื่อทำการเปิดเว็บไซต์  

* * *

* วิธีการปิดserver  

ให้กดปุ่ม CTRL + C  เพื่อทำการปิด server  

* * *

A>หมายเหตุ  
A>ห้ามปิดcmd ในขณะที่เปิด server อยู่   เพราะถ้าปิดจะทำให้ไม่สามารถ run serverได้  
