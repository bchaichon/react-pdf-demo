สร้างไฟล์ pdf ด้วย React + pdfmake ภาษาไทย

ถ้ากำลังมองหาวิธีการสร้างไฟล์ pdf ฝั่ง client อยู่ ขอนำเสนอตัวนี้เลยครับ pdfmake ไปลองเล่นดูได้ พอลองดูก็จะพบว่าตัว example ที่เค้าให้มา font ไม่ support ภาษาไทย ถ้าอยากให้มันใช้ font ไทยได้มีมีขั้นตอนดังนี้ครับ

  => https://goo.gl/EeqZZx


สองตัวนี้ อยู่ใน  (prject folder)/node_modules/pdfmake/
examples => เก็บไฟล์ font 
pdfmake-build => ไฟล์ vfs_fonts.js ที่ build ใหม่