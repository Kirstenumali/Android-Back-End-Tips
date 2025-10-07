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
## XML
1. To access the onClick functionality on activities and fragment. You must set this in the XML which is onClick. The onClickStop is a function from Fragement. For example, this is the code for the onClickStop.
``` bash
android:onClick="onClickReset"
android:onClick="onClickStop"
android:onClick="onClickStart"
```
 - onClickStop
   ``` bash
   public void onClickStop(View view) {
   running = false;}
   ```
   
