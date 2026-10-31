BISWAART STUDIO — ANDROID STUDIO PROJECT (PREVIEW WRAPPER)

গুরুত্বপূর্ণ:
এটি Android Studio-তে APK বানানোর জন্য একটি source project।
এই পরিবেশে Android SDK/Gradle build tool নেই, তাই এখানে compiled APK তৈরি করা সম্ভব হয়নি।
এটি এখনকার HTML interactive prototype-কে Android WebView-এর ভিতরে চালায়; পূর্ণ native Picsart-level editor নয়।

Windows PC-তে APK তৈরি:
1. Android Studio ইনস্টল করুন (developer.android.com/studio)।
2. ZIP Extract করুন।
3. Android Studio > Open > এই Biswaart_Studio_Android_Project ফোল্ডার নির্বাচন করুন।
4. Gradle Sync শেষ হওয়া পর্যন্ত অপেক্ষা করুন। প্রথমবার internet লাগবে dependencies নামাতে।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
6. Build সফল হলে app/build/outputs/apk/debug/app-debug.apk পাবেন।
7. APK ফোনে পাঠিয়ে ইনস্টল করুন। ফোনে প্রয়োজন হলে "Install unknown apps" অনুমতি দিন।

যা এই preview wrapper-এ কাজ করার কথা:
- Home/Create/Projects/Settings navigation
- Text, shape, image layer add
- Layer select, visibility, lock, duplicate, reorder, delete
- Basic layer properties
- Undo/redo
- Local project save (WebView storage)
- PNG export to Pictures/Biswaart Studio
- Android image picker integration

সীমাবদ্ধতা:
- Unlimited layer-এর কোনো কৃত্রিম app-level সংখ্যা নির্ধারণ করা হয়নি; বাস্তব সীমা ফোনের RAM/storage/performance।
- AI generation, professional background removal, full Lightroom/Snapseed-grade processing, video editing, Bengali font library, PDF export এখনও সম্পূর্ণ implement করা হয়নি।
- APK debug build হবে; Play Store release-এর জন্য signing, testing, privacy policy এবং আরও development লাগবে.
