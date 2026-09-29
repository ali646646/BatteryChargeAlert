# BatteryChargeAlert

پروژه Android برای هشدار رسیدن باتری به درصد تعیین‌شده.

## ساده‌ترین Build آنلاین
این پروژه فایل GitHub Actions دارد. پس از قرار دادن پروژه در یک Repository عمومی GitHub:
1. تب Actions را باز کنید.
2. Workflow با نام Build BatteryChargeAlert APK را انتخاب کنید.
3. Run workflow را بزنید.
4. بعد از پایان Build، در بخش Artifacts فایل BatteryChargeAlert-debug-apk را دانلود کنید.

این روش از Gradle/Java روی سرور GitHub استفاده می‌کند و نیاز به نصب Android Studio روی کامپیوتر ندارد.

## Build محلی
در محیط دارای Gradle 8.11.1 و JDK 17:
gradle assembleDebug

خروجی:
app/build/outputs/apk/debug/app-debug.apk
