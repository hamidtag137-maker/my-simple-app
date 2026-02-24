[app]
# نام برنامه
title = برنامه ساده

# نام بسته (package name)
package.name = mysimpleapp

# دامنه بسته (معکوس دامنه شما)
package.domain = org.example

# نسخه برنامه
version = 0.1

# فایل اصلی برنامه
source.dir = .
source.include_exts = py,png,jpg,kv,atlas,txt,html,css,js

# نسخه‌های پایتون (2 یا 3)
requirements = python3,kivy

# معماری‌های هدف
android.archs = arm64-v8a, armeabi-v7a

# مجوزهای برنامه
android.permissions = INTERNET

# Minimum SDK
android.minapi = 21

# Target SDK
android.api = 33

# SDK و NDK
android.sdk_path = /home/your_username/Android/Sdk
android.ndk_path = /home/your_username/Android/android-ndk-r25c

# آیکون برنامه
# icon.filename = %(source.dir)s/icon.png

# نام نمایشی برنامه
presplash.filename = %(source.dir)s/presplash.png

# ویژگی‌های fullscreen
fullscreen = 0

# جهت‌گیری برنامه
orientation = portrait

# پشتیبانی از WebView
android.add_src = 
android.add_src = java/org/example/mysimpleapp/WebView.java

# اضافه کردن فایل‌های assets
android.extra_src = src
android.add_src = src/org/example/mysimpleapp/WebView.java

# اضافه کردن فایل HTML به assets
android.extra_src = assets
android.add_assets = index.html:assets

[buildozer]
# سطح لاگ
log_level = 2

# هشدارها
warn_on_root = 1

# معماری برای شبیه‌ساز
android.arch = armeabi-v7a