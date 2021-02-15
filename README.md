# TODO List App

### 1. ทำการสร้างหน้าเวบ My ToDo List โดขใช้ HTML และ Bulma CSS และ Vue JS ดังรูป Wireframe
- รายการ Task เป็น checkbox และเมื่อติ้ก checkbox จะเปลี่ยนสถานะของ Task เป็น "Completed"
- สามารถเพิ่มรายการใหม่เข้าไปได้โดยการพิมพ์ชื่อ Task ใน Textbox "Task" ด้านล่าง แล้วกดปุ่ม "Save"
- โดย Default เมื่อสร้าง Task ขึ้นใหม่จะมีสถานะ "Incomplete" เสมอ

[IMG TODO1]

### 2. เพิ่มปุ่ม icon รูปดินสอ เมื่อกดแล้วให้มี [Modal](https://bulma.io/documentation/components/modal/) เปิดขึ้นมาสำหรับแก้ไขดังรูป
- หน้า Modal มีส่วนประกอบดังนี้
  1. ช่อง Textbox สำหรับแก้ไขชื่อ Task
  2. ปุ่ม "Save" เมื่อกดจะทำการบันทึกการแก้ไข

[IMG TODO2]

### 3. เพิ่มปุ่ม icon รูปถังขยะ สำหรับลบรายการ Task นั้น ๆ เมื่อกดแล้วให้มี [Modal](https://bulma.io/documentation/components/modal/) เปิดขึ้นมาสำหรับยืนยันการลบดังรูป

[IMG TODO3]

### 4. ด้านบนของรายการ ToDo ให้แสดงผลการนับจำนวน Task ที่มีสถานะ Completed และ Incomplete ดังรูป
***จะต้องใช้ Computed Properties เท่านั้น***

[IMG TODO4]

### 5. เพิ่ม Filters สำหรับการกรองรายการ Task โดยสามารถกรองได้ดังนี้
- "Hide completed tasks" เป็น Checkbox คือเมื่อติ้กจะทำการ**ซ่อน** Task ที่มีสถานะ "Complete"
- "Sort incomplete tasks" เป็น Checkbox คือเมื่อติ้กจะทำเรียงลำดับ (sort) รายการ Task โดยเอารายการที่มีสถานะ "Incomplete" ขึ้นไว้ด้านบน
- "Filter by task name" เป็น Textbox สำหรับค้นหา Task ด้วยชื่อ

[IMG TODO5]
