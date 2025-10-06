# Android-Back-End-Tips

1. The launcher for android that you can change the activity name and launch the activity firstly instead of the MainActivity. As the xml file below shows that the activity is inside the code for intent functionality.
``` bash
</activity>
<activity android:name=".DetailActivity" />
<activity android:name=".TempActivity">
<intent-filter>
<action android:name="android.intent.action.MAIN" />
<category android:name="android.intent.category.LAUNCHER" />
</intent-filter>
</activity>
</application>
```
