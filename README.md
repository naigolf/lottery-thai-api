# lottery-thai-api


RESTful API Lottery thailand

>>  https://lottery-th.herokuapp.com/loto

เป็น API ผลสลากกินแบ่งรัฐบาล(หวย)ไทย 
เมื่อ request จะได้รับผลสลากงวดล่าสุด ในรูปแบบของ JSON

ปล. 
- ผลหวย จะ update(เปลี่ยนแปลง) ทุกวันที่มีการประกาศผลสลากกินแบ่งรัฐบาล เช่น 1 , 16
- เวลาในการ update(เปลี่ยนแปลง) หลังจากรางวัลที่ 1 ออกเรียบร้อยแล้ว
- สำหรับใครที่นำไปต่อยอด request แนะนำให้เรียกวันที่หวยออกนะครับ (วันอื่นๆจะได้ค่าเดิมของงวดล่าสุด)
- ความถี่ในการ request แนะนำไม่ควรต่ำกว่า 10-20วินาที/ครั้ง

***ด้วยข้อจำกัดของ server ที่ผมใช้มัน "ฟรี" 
อาจจะทำให้ช้าบ้าง มีปัญหาบ้าง ต้องขออภัย ณ ที่นี่ด้วยครับ
