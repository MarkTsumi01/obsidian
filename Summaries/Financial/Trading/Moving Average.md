	คือ เครื่องมือประเภทหาค่าเฉลี่ยเคลื่อนที่ ทำหน้าที่ smooth data
	
	ใช้ในการสร้างเส้นอนุมานแนวโน้ม ทิศทางราคาหุ้น จากการเฉลี่ยค่าข้อมูลราคาในอดีต ณ ช่วงเวลาต่างๆ

	มีหลากหลายโมเดล แตกต่างกันไปตามรูปแบบสมการ ความช้าเร็วในการตอบสนองการเคลื่อนตัวของราคา

	Moving average มีประโยชน์หลากหลายด้านในการวิเคราห์ทางเทคนิคอล

	เช่นสร้างแนวโน้ม , สร้างแนวรับ - แนวต้าน , หาจุดซื้อจุดขายเป็นต้น

	มีวิธีการนำไปใช้หลายรูปแบบ เช่นการใช้แบบเส้นเดี่ยว เส้นคู่ (Crossover) หรือแบบ หลายเส้น (Multi Moving average)

	เป็นเครื่องมือที่นิยมมากใช้นิยามแนวโน้ม

	ได้แก่ Simple moving average(sma) , Exponential Moving Average(EMA), Smoothed Moving Average(SMMA), Linear Weight Moving Average (LWMA), ,Modified Moving Average(MMA)


## Simple Moving Average

	SMA => 1980 => Classic

	Simple Moving Average (SMA)

	เครื่องมือค่าเฉลี่ยเคลื่อนที่แบบพื้นฐาน ไม่ซับซ้อน

	มองค่าข้อมูล ในทุกช่วงเวลามีความสำคัญเท่ากันหมด

	ข้อเสียกรณีเกิด bias หรือเกิดช่วงราคามีการกระโดด ในอดีต

	ไม่มีการใส่ค่าน้ำหนักพิเศษ

	SMA = Pm + Pm-1 + ... +Pm(n-1)/n


## Exponential Moving Average

	เครื่องมือค่าเฉลี่ยเคลื่อนที่ ที่มีการเกลี่ยค่าความสำคัญ ตามช่วงเวลา

	ถ่วงน้ำหนักให้ความสำคัญกับข้อมูล ปัจจุบัน มากกว่าข้อมูลอดีตที่ผ่านมา

	ลด Noise และการกระโดดของข้อมูล แต่ไม่ตัดทิ้งข้อมูลอดีต

	ได้ค่าผลลัพธ์ที่ใกล้เคียงกับปัจจุบัน



## Weighted Moving Average

	เน้นการถ่วงน้ำหนักมากกว่า

	ตอบสนองปัจจุบันได้เร็วกว่าโมเดลอื่น



## Modified Moving Average (MMA)

	เครื่องมือค่าเฉลี่ยเคลื่อนที่ ที่มีการเกลี่ยค่าคล้ายกับ simple moving averages

	สร้างเพื่อให้เกิดการคำนวณที่เร็วขึ้น และลดเวลาการคำนวณกับข้อมูลจำนวนมากๆ

	ลด resource การเก็บข้อมูล หรือคำนวณข้อมูลทุก node