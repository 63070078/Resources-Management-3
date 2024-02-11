# CPU Management


เพื่อที่จะดูรายการทั้งหมดที่กำลังทำงานอยู่ทั้งหมด เราสามารถใช้คำสั่ง top ได้(Table of process) โดยจะแสดงข้อมูล users, tasks, CPU load และ memory usage
```
top
```

ผลลัพธ์:

![alt text](https://github.com/63070078/Resources-Management-3/blob/main/img/top.png?raw=true)

ซึ่งสามารถเลื่อนขึ้นหรือลงด้วยปุ่ม Page up หรือ Page down ได้


สามารถเลือกใช้ option ต่างๆได้ ดังนี้
```
#help แสดง command syntax ที่สามารถใช้ได้
top -h

#ซ่อนรายการที่เป็นสถานะ idle
top -i

#แสดง process ที่มี ID หรือ username ตรงกับข้อมูลที่ input โดย
top -u | -U [ID or name]

#กำหนดจำนวนรอบการรีเฟรชข้อมูลของ top แล้วออกจากการทำงาน
top -n [X]
```

ในขณะที่ top กำลังทำงานสามารถใช้คำสั่งอื่นๆได้ ดังนี้:
k --> การส่งสัญญาณ เมื่อกดปุ่ม k แล้วจะสามารถใส่ค่า PID ของ process นั้นๆได้ หากไม่ใส่คำสั่งสัญญาณ จะเป็นการ kill process นั้นๆ
```
k 
M --> สำหรับ
```
<iframe src="https://giphy.com/embed/gOY0Z7zFZzgvADRXJY" width="480" height="360" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/gOY0Z7zFZzgvADRXJY">via GIPHY</a></p>
ใช้คำสั่ง q เพื่อออกจากการทำงาน
```
q
```
