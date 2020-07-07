# Federated Learning

ตัวอย่างของการทำ Federated Learning อย่างง่ายโดยใช้ PySyft 

## Step 1:
รัน start_xor_data_node.py ด้วยคำสั่ง 


`python start_xor_data_node.py --port 8777 --verbose`


เป็นการเริ่มใช้งาน Data_Node เตรียมพร้อมให้สามารถรับโมเดล ที่จะส่งมาและรันบนนี้ได้ สิ่งที่อาจจะต้องปรับเปลี่ยนในโค้ดคือ IP Address ต้องใช้ IP Address ที่ใช้งานจริง

## Step 2
รันแต่ละขั้นตอนใน Notebook เพื่อเชื่อมต่อ, ส่งโมเดล, รัน ANN และรับโมเดลกลับมาอัพเดท

วิดีโอสาธิตการใช้งาน https://youtu.be/Ch0OoZQ-6WI
