CricketWorld Live — Android test project

IMPORTANT: This ZIP is Android Studio source code, NOT an installable APK.
A compiled APK cannot be produced in this workspace because Android SDK/Gradle build tools are not installed.

Build the APK on a Windows PC:
1. Install Android Studio and JDK 17.
2. Install Android SDK Platform 35 from Android Studio > SDK Manager.
3. Extract this ZIP.
4. Android Studio > Open > select the CricketWorld_Live_Android_Project folder.
5. Wait for Gradle Sync to finish.
6. Build > Build Bundle(s) / APK(s) > Build APK(s).
7. Copy app/build/outputs/apk/debug/app-debug.apk to your Android phone and install it.
   If Android asks, allow installation from this source.

Included:
- Home, Cricket, Live TV, Highlights, Islamic TV and local Admin tabs.
- PTV network website links and Madani Channel link in both Live TV and Islamic TV.
- Search in channel list.
- Add/delete custom channel links; stored locally on the same device.
- External links open in the phone browser.

Important limitations:
- Live score websites open in browser; automatic in-app ball-by-ball scores, fixtures feed and push alerts need a licensed cricket API key and backend.
- TV links open official pages/platforms; not every channel has a verified public direct stream. Rights, country and subscription restrictions apply.
- Madani Channel official page is linked; uninterrupted direct live playback has not been tested.
- Admin is a local link manager, not a password-protected cloud admin dashboard.


APK ONLINE BANANE KA TAREEQA (2GB RAM PC PAR BHI):
Is project mein GitHub Actions workflow shamil hai. APK GitHub ke cloud computer par build hogi; aapke PC par Android Studio/SDK ki zaroorat nahi.

1. GitHub.com par free account banayein ya login karein.
2. New repository banayein, naam: CricketWorld-Live (Private ya Public).
3. ZIP ko PC par Extract karein.
4. Extracted project ke tamam files/folders (including .github folder) GitHub repository mein upload karein. .github folder bhi zaroor upload karein.
5. Upload ke baad repository ke Actions tab par jayein. "Build CricketWorld Live APK" workflow select karein.
6. Agar workflow khud start na ho to "Run workflow" dabayein.
7. Build complete hone par workflow run ke neeche Artifacts mein "CricketWorld-Live-debug-APK" download karein.
8. Downloaded artifact ZIP ko extract karein. Us mein app-debug.apk hogi. APK phone mein bhej kar install karein.

Agar GitHub par build red/fail ho, Actions ke error ka screenshot bhejein. Build success ki guarantee pehle se nahi di ja sakti; error aaye to usay theek karna hoga.
