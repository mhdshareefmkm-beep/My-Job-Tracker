MY JOB TRACKER - ANDROID PROJECT

This is an Android Studio project source package. It is not a prebuilt APK.

BUILD APK:
1. Install Android Studio on a computer.
2. Open this extracted folder (MyJobTracker_Android) in Android Studio.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the APK at app/build/outputs/apk/debug/app-debug.apk.

FEATURES:
- Attendance calendar; tap a date to select it.
- Mark Present or Absent. Sundays are automatically shown as weekly off.
- Fixed weekly salary amount and Saturday payment day.
- Track paid/unpaid weekly salary.
- Attendance and salary history stored locally in the app.
- Export/import backup JSON; export CSV attendance.

DATA:
Records are stored on the device using browser local storage inside the app. Clearing app data or uninstalling may remove records. Use Export Backup regularly to keep a copy.

No internet permission is requested.
