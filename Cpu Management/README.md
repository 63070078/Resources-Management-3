# CPU Management


เพื่อที่จะดูรายการทั้งหมดที่กำลังทำงานอยู่ทั้งหมด เราสามารถใช้คำสั่ง top ได้(Table of process) โดยจะแสดงข้อมูล users, tasks, CPU load และ memory usage
```
top
```

ผลลัพธ์:

![alt text](https://github.com/63070078/Resources-Management-3/blob/main/img/top.png?raw=true)

สามารถเลือกใช้ option ต่างๆได้ ดังนี้
```
#ซ่อนรายการที่เป็นสถานะ idle
top -i

#กำหนดจำนวนรอบการรีเฟรชข้อมูลของ top แล้วออกจากการทำงาน
top -n [X]
```

ในขณะที่ top กำลังทำงานสามารถใช้คำสั่งอื่นๆได้ ดังนี้:
```
M --> สำหรับ
```
ใช้คำสั่ง q เพื่อออกจากการทำงาน
```
q
```
