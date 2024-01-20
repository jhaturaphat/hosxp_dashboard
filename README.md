#Hosxp Dashboard with Grafana

<img src="/dashboard-1.png" width="900"> 
<br>
<label>ติดตั้ง Docker บน Server หรือ PC https://docs.docker.com/engine/install </label><br>
<label>git clone https://github.com/jhaturaphat/hosxp_dashboard.git หรือ Download ZIP File</label><br>
<label>เข้าไปในโฟล์เดอร์ hosxp_dashboard หรือใช้คำสั่ง cd hosxp_dashboard </label> <br>
<label>พิมพ์คำสั่ง docker-compose up -d </label><br>

<label>http://localhost:3000 หรือ http://<ip-server>:3000 </label><br>

<label>Username: admin <br> Password:123456</label>
<div>
#เปลี่ยน IP Address สำหรับเชื่อมต่อฐานข้อมูล HOSXP  <br>
<label>Home > Connections > Data sources > MySQL</label>
</div>
<div>
รีเซ็ตรหัสผ่าน <br>
docker ps จากนั้นดูชื่อ คอนเทนเนอร์ ที่เป็น gafana <br>
docker-compose exec -it [container name ชื่อคอนเทนเนอร์] grafana cli admin reset-admin-password [new password ระบุรหัสผ่านใหม่]
</div>
