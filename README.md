# Micro-Project-60070037
This project is solely an academic work for subject Microprocessing KMITL
วิธีการใช้งาน
1. ติดตั้ง Object detection ตามลิงก์นี้ https://www.instructables.com/Raspberry-Pi-Object-Detection/?fbclid=IwAR287R5bJLdkEHGo5fGpq7ce6X4BiT2IR2K9rIto1xQJgZBucKHdrsOHzQA
2. ทำการเช็คว่าใช้งานได้หรือไม่โดยการรัน python3 Object_detection_picamera.py ที่ในลิงก์มีการให้มา (หากรันไม่ได้ลองทำตาม EX:)
3. โหลดโค้ดของโปรเจคนี้
4. ใส่ไว้ในโฟลเดอร์  /home/pi/tensorflow1/models/research/object_detection
5. รันโค้ดแล้วใช้งานได้เลย

EX สำหรับผู้ที่รันไม่ได้ลองทำตามนี้
1. หาก error จากการหา libary ไม่เจอให้ import ตามที่ cmd บอกว่าหาไม่เจอ
2. รันโค้ดตามนี้
   sudo apt update
   sudo apt install realvnc-vnc-server realvnc-vnc-viewer
3. เข้า sudo raspi-config > interfacing option > VNC > Enable
4. รันคำสั่ง vncserver แล้วจำ ip และ port ที่บอกมาหลังรัน
5. โหลด vnc viewer ลงคอมพิวเตอร์
6. ใส่ ip และ port ที่ได้
7. จะมีหน้าต่าง cmd raspberry pi ขึ้นมาเหมือน connect ด้วย puTTy
8. ลองทำตามขั้นตอนที่ 2 ในวิธีการด้านบนอีกครั้ง
