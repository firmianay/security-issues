# com.sf.calculatornew

com.sf.calculatornew has an Android manifest file that contains an entry with the android:allowBackup attribute set to true. This could be leveraged by an attacker with physical access to the device.

- package: com.sf.calculatornew
- version: 4.01
- url: https://os-android.liqucn.com/rj/9069969605635.shtml

```xml
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.sf.calculatornew"
    platformBuildVersionCode="30" platformBuildVersionName="11" android:versionCode="50" android:versionName="4.01" android:compileSdkVersion="30" android:compileSdkVersionCodename="11">
<application
    android:theme="@style/AppTheme" android:label="@string/app_name" android:icon="@drawable/icon_cal_new" android:name="com.stub.StubApp"
    android:allowBackup="true"
    android:supportsRtl="true" android:networkSecurityConfig="@xml/network_security_config" android:roundIcon="@drawable/icon_cal_new" android:appComponentFactory="androidx.core.app.CoreComponentFactory" android:requestLegacyExternalStorage="true">
```
