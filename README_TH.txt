RAN BoT v1 Lite — ต้นแบบ Dashboard 8 จอ

รายละเอียด
- แสดงรายการ UG Phone 8 เครื่องและหน้าที่ตามที่ผู้ใช้ระบุ
- ภาษาไทย ธีมดำ-เขียว-ขาว
- ไม่มีระบบบันทึกของดรอป
- มีปุ่มหยุดสำหรับต้นแบบหน้าจอ
- ไม่เชื่อมต่อ UG Phone จริง และไม่ควบคุมเกม
- ไม่มีการแก้ไขหน่วยความจำเกมหรือระบบแก้ CAPTCHA

สร้าง APK
1. ติดตั้ง Android Studio บนคอมพิวเตอร์ หรือใช้บริการ build Android ที่เชื่อถือได้
2. افتحโฟลเดอร์นี้เป็นโปรเจกต์ Gradle ใน Android Studio
3. รอ Gradle Sync และติดตั้ง Android SDK 34
4. เลือก Build > Build Bundle(s) / APK(s) > Build APK(s)
5. APK อยู่ที่ app/build/outputs/apk/debug/

เป้าหมายความเข้ากันได้
- minSdk 23
- targetSdk 29 (Android 10)
- compileSdk 34

หมายเหตุ
ไฟล์ ZIP นี้เป็นซอร์สโค้ด ไม่ใช่ APK ที่คอมไพล์แล้ว
