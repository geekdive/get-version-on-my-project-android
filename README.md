# get-version-on-my-project-android
Mengambil nilai dari versi android yang sedang dibuat

## Import Settings
String versionName = BuildConfig.VERSION_NAME;

## Check the Version
<img src="https://github.com/moeslimdecoded/get-version-on-my-project-android/blob/master/get-version.png" />

## Result Checker
<img src="https://github.com/moeslimdecoded/get-version-on-my-project-android/blob/master/result.png" />

## Sourcecode
import com.yourpackage.BuildConfig;
....
....
String version = BuildConfig.VERSION_NAME;
System.out.println("Versi Android: " + version);

## Sumber
https://stackoverflow.com/questions/4616095/how-to-get-the-build-version-number-of-your-android-application
