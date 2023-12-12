image-detection with esp32-s3 (tg2023 ubu)
not finist yet

โดยโค้ดนี้เป็นโค้ดที่ ใช้ upload ลง esp32s3 เพื่อถ่ายภาพจากกล้องและนำมาประมวลผลด้วย AI ของ edge impules เพื่อทำการจับวัตถุจากรูปภาพที่ถ่ายได้
โดย folder lib เป็น folder ที่เก็บ file deploy ที่ได้จากการ train model edge impulse
<img width="250" alt="Screenshot 2566-12-12 at 15 33 00" src="https://github.com/aelde/tgr2023_esp32s3_imagedetection/assets/79216582/205f6373-e7a6-4ed5-85e4-9950fa2e15e2">

เมื่อนำไปใช้งานให้เปลี่ยนตัวแปรดังนี้
  1. Wifi SSID / Password
  2. mqtt broker
  3. mqtt topic
