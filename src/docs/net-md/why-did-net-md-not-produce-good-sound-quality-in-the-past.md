---
title: ทำไมในอดีต Net MD จึงเสียงไม่ดี
---

![](images/why-did-net-md-not-produce-good-sound-quality-in-the-past/net-md-sound-quality-cover.png)

เรามักได้ยินเสมอว่า "Net MD เสียงไม่ดี" เรื่องนี้เป็นไปได้จริง แต่ปัจจุบันไม่ได้เป็นแบบนั้นแล้ว

ด้วยข้อมูลเหล่านี้ เป็นไปได้อย่างยิ่งที่ในอดีต Net MD เสียงไม่ดี:

👉 1) ข้อมูลจาก Wikipedia https://en.wikipedia.org/wiki/MiniDisc#NetMD บอกว่า
When transferring music in SP mode using NetMD with SonicStage, what is transferred is in-fact padded LP2. That is to say that the quality of the music is that of LP2 but recorded as SP.

สรุปได้ประมาณว่า:

การอัด SP mode ด้วย SonicStage ให้คุณภาพเสียงเพียง LP2 เท่านั้น ไม่ได้เป็นการได้คุณภาพเสียง SP จริง
มองเป็นการอัดเพลงที่คุณภาพเสียง LP2 แต่ปรับแต่งให้เล่นได้ในเครื่องเล่นที่รองรับ SP ได้เท่านั้น
(คหสต แม้ว่าการเขียน SP จะใช้เวลานานกว่า LP2 มาก อาจจะเป็นเวลาในตอนเขียนเพลงมากกว่า แต่ขั้นตอนการแปลงเพลงไม่ได้ใช้เวลาเยอะเลย คุณภาพเสียงน่าจะเป็นตอนแปลงเพลงมากกว่า)

**ปัจจุบันปัญหานี้ได้ถูกแก้ไปแล้ว** เพราะ Web MiniDisc/Platinum MD ได้ใช้  libnetmd ทำให้เราเขียนเพลงได้คุณภาพเสียง SP จริงๆ นี่จึงตอบคำถามได้ว่าทำไมเขียนด้วย Web MiniDisc/Platinum MD ได้เสียงที่ดีกว่า SonicStage จริง

👉 2) ในอดีตไฟล์เพลงส่วนใหญ่ที่หาได้มักจะอยู่ในรูปแบบ MP3 128kbps ซึ่งมีคุณภาพเสียงด้อยกว่า CD อย่างชัดเจน
ดังนั้นการเขียนเพลงด้วย MP3 128kbps จึงได้เพลงออกมาคุณภาพเสียงไม่ดี
ไม่ได้เป็นปัญหาที่ Net MD แต่ปัญหาที่ต้นฉบับเพลงเป็นหลัก

**ปัจจุบันปัญหานี้ได้ถูกแก้ไปแล้ว** เรามีไฟล์ให้เลือกเพิ่มมากขึ้นและหาได้ง่าย มี lossless หลายแบบ ที่ใช้งานได้กับ Net MD เช่น flac, m4a, aiff เพิ่มเติม https://onlyminidisc.com/net-md/web-mini-disc-manual#supported-music-files

---
👉จากประสบการณ์ส่วนตัว ตอนนี้ตัวแปรสำคัญต่อคุณภาพเสียงที่ได้คือ:
- คุณภาพของไฟล์ต้นฉบับ
- เครื่องอัดที่ดี เช่น ถ้าใช้ deck อัด ก็ให้คุณภาพเสียงที่ดีกว่ากว่าอัดด้วยเครื่องเล่นพกพา
- เครื่องอัดที่รองรับ ATRAC version ที่ดีกว่า

👉ดังนั้นในปัจจุบัน จึงบอกได้ว่าการอัดด้วย Net MD ควรได้คุณภาพเสียงไม่แตกต่างกับ 1:1 ถ้าอัดด้วยไฟล์เดียวกัน แต่ถ้าจะพิสูจน์ให้ลึกลงไป เราอาจจะต้องใช้เครื่องมือเช่น Oscilloscope เพื่อให้เห็นภาพกราฟเสียง แล้วมาเปรียบเทียบกันครับ

หากมีข้อผิดพลาดประการใด ผมขออภัยไว้ ณ ที่นี้ และจะปรับปรุงเนื้อหาให้ถูกต้องครับ