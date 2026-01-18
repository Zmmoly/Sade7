# Android Permissions App

تطبيق Android بسيط يطلب جميع الأذونات الممكنة على Android 15 (API Level 35).

## الميزات

- ✅ طلب جميع الأذونات الخطرة (Dangerous Permissions)
- ✅ طلب الأذونات الخاصة (Special Permissions)
- ✅ خدمة إمكانية الوصول (Accessibility Service) مع جميع الميزات
- ✅ متوافق تمامًا مع Android 15
- ✅ جاهز للبناء على GitHub Actions

## الأذونات المدعومة

### أذونات خطرة (Dangerous Permissions)
- التقويم (Calendar)
- الكاميرا (Camera)
- جهات الاتصال (Contacts)
- الموقع (Location - بما في ذلك الموقع في الخلفية)
- الميكروفون (Microphone)
- الهاتف (Phone)
- المستشعرات (Sensors)
- الرسائل القصيرة (SMS)
- التخزين والوسائط (Storage & Media)
- التعرف على النشاط (Activity Recognition)
- البلوتوث (Bluetooth)
- الإشعارات (Notifications)
- الأجهزة القريبة (Nearby Devices)

### أذونات خاصة (Special Permissions)
- الرسم فوق التطبيقات الأخرى
- تعديل إعدادات النظام
- إدارة جميع الملفات
- تثبيت الحزم
- تجاهل تحسين البطارية

### خدمة إمكانية الوصول
- الوصول إلى جميع الأحداث
- إمكانية تنفيذ الإيماءات
- الوصول إلى محتوى النوافذ
- جميع ميزات إمكانية الوصول المتاحة

## البناء

### محليًا
```bash
./gradlew assembleRelease
```

### على GitHub Actions
قم برفع الكود إلى GitHub وسيتم بناء التطبيق تلقائيًا.

## المتطلبات

- Android Studio Arctic Fox أو أحدث
- JDK 17
- Android SDK API Level 35
- Gradle 8.2.0 أو أحدث

## الحزمة
```
com.awab.ai
```

## ملاحظات هامة

1. التطبيق يستخدم `targetSdk = 35` (Android 15)
2. جميع الأذونات متوافقة مع متطلبات Android 15
3. خدمة إمكانية الوصول مُهيأة بجميع الميزات الممكنة
4. APK المُنتج غير موقّع - يحتاج للتوقيع قبل النشر

## الترخيص
MIT License
