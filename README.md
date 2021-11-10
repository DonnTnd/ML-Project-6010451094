# ML-Project-6010451094
# King County, Washington Housing Prediction
ชื่อ : นายธนดล  สระแก้ว

รหัสนิสิต : 6010451094

หมู่ : 200

รายละเอียดไฟล์
1. PDF File : ML-slide-project-6010451094.pdf
2. HTML File : index.html
3. Configuration File : jupyter_kernel_gateway_config.py
4. Dataset : kc_house_data.csv (ชุดข้อมูลราคาบ้าน), zipcode.csv (ชุดข้อมูลเลขไปรษณีย์เขต King County ในรัฐ Washington)
5. Model : price_regression.ipynb (ก่อนนำเสนอ), price_regression2.ipynb (แก้หลังนำเสนอ)

ไฟล์ที่ได้แก้ไรเพิ่มเติมอยู่ที่ไฟล์ price_regression2.ipynb โดยมีรายละเอียดการเพิ่มดังนี้
  1. เพิ่มตัวเลือกการใช้ข้อมูลในการทำนาย ที่เป็นบ้านที่ต้องการใกล้ริมน้ำ (Waterfront) หรือไม่
  2. Model ใหม่ (price_regression2.ipynb) เพิ่มการทำนายแบบใหม่คือ Polynomial Regression โดยค่า Accuary มีความแม่นยำเพิ่มขึ้น

คำแนะนำ
  เนื่องจากได้แก้ปัญหาใช้การทดสอบแบบ Polynomial Regression ทำให้ผลลัพธ์ในการ Predict มีความแม่นยำเพิ่มขึ้น และทำเป็นโมเดลใหม่ขึ้นมา แต่ปัญหาที่เกิดขึ้นคือไม่สามารถนำโมเดลนี้ไปแสดงบน HTML ได้ จึงจำเป็นต้องใช้การทำนายแบบ Linear Regression แบบเดิมก่อน
