# Basic git
[![uQeiRv.md.png](https://sv1.picz.in.th/images/2021/10/24/uQeiRv.md.png)](https://www.picz.in.th/image/uQeiRv)
## สรุปคำสั่ง Git
- git init ไว้สร้าง Git repository 
- git status ตรวจสอบสถานะของไฟล์ working directory และ staging area 
- git add เพิ่มไฟล์ the working directory เข้าสู่ staging area 
- git diff แสดงความแตกต่างของไฟล์ระหว่าง working directory กับ staging area 
- git commit เก็บประวัติการแก้ไขแบบถาวรจาก staging area ไว้ใน repository 
- git log แสดงรายการที่ commit มาทั้งหมด
- git branch ใช้แสดงรายชื่อ branch ทั้งหมด 
- git branch <branch_name> สร้าง branch ใหม่ 
- git checkout <branch_name> สลับไปใช้งาน branch ที่ระบุ 
- git merge <branch_name> ใช้รวมไฟล์จาก branch ที่ระบุ มายัง branch ปัจจุบัน 
- git branch -d <branch_name> ลบ branch ที่ระบุ
- git clone สร้าง local repository จาก remote repository 
- git remote -v แสดงรายการ remote address ทั้งหมด 
- git fetch ดึงข้อมูลทั้งหมดจากฝั่ง remote มายัง local 
- git merge origin/master สัง่รวมไฟล์จาก origin/master มายัง local branch 
- git pull สั่งรวมไฟล์จาก ฝั่ง remote มายัง local (git fetch + git merge) 
- git push origin <branch_name> ส่งข้อมูลจาก local branch ไปรวมกับ originremote.
