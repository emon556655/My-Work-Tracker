MY WORK TRACKER — APK PROJECT
================================

এই ZIP-টি একটি সম্পূর্ণ Android Studio/AndroidIDE project।
এতে My Work Tracker-এর HTML app Android WebView-এর ভিতরে চলছে।

যা আছে:
- Punch In
- Punch Out
- Working Hours (Hour + Minute)
- History
- Local Storage-এ data save
- App name: My Work Tracker
- App icon
- Offline কাজ করার জন্য HTML assets bundled

ফোন দিয়ে APK বানানোর সহজ পদ্ধতি:
1. ZIP extract করো।
2. AndroidIDE-এর মতো Android project builder-এ project folder ওপেন করো।
3. Gradle sync/build করতে দাও।
4. Build > Assemble Debug APK চালাও।
5. app/build/outputs/apk/debug/app-debug.apk পাওয়া যাবে।
6. APK ফোনে install করো।

গুরুত্বপূর্ণ:
- এই project-এর HTML data localStorage-এ থাকে, তাই একই app-এর ভিতরে History থাকে।
- App uninstall করলে Android-এর app data মুছে যেতে পারে।
- Release/Play Store APK বানাতে পরে signing করতে হবে।

যদি AndroidIDE-তে Gradle/SDK version চাই:
- compileSdk: 35
- minSdk: 23
- targetSdk: 35
- Android Gradle Plugin: 8.5.2
