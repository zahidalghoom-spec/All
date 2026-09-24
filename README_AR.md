# مشروع Android — مصمم القحوم AI

هذا مشروع Android كامل بصيغة Gradle/Android Studio، ويحوّل نسخة الويب إلى تطبيق Android عبر WebView.

## قبل البناء
افتح:
`app/src/main/java/com/qahoum/ai/MainActivity.java`

واستبدل:
`https://YOUR-DOMAIN-HERE.example`

برابط نسخة الويب المنشورة للتطبيق.

## البناء
من Android Studio:
1. Open واختر مجلد المشروع.
2. انتظر Gradle Sync.
3. Build > Build APK(s).
4. ستجد APK داخل:
`app/build/outputs/apk/debug/app-debug.apk`

## مهم
مفتاح OpenAI API لا يوضع داخل التطبيق. يجب أن يكون في خادم الـNode الذي يشغل `/api/design`.
المحرك الخلفي في نسخة الويب يستخدم GPT Image 2 لتوليد/تحرير الصور. 
