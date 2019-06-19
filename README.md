Custom prebuilts for use with [rattlesnakeos-stack](https://github.com/dan-v/rattlesnakeos-stack) to build [RattleSnakeOS](https://github.com/RattlesnakeOS).

## How to
Add the following to end of your `rattlesnakeos-stack` config file.
```
...

[[custom-prebuilts]]
  repo = "https://github.com/60Eight/ros-custom-prebuilts"
  modules = [
      "com.google.android.maps.jar",
      "FakeStore",
      "GmsCore",
      "GsfProxy",
      "MozillaNlpBackend",
      "NominatimNlpBackend",
      "Recorder"
  ]

...
  
```

## References:
### APKs:
1. AuroraStore from [f-droid](https://f-droid.org/en/packages/com.aurora.store/)
2. DroidGuard from 
3. FakeStore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/FakeStore)
4. GmsCore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GmsCore)
5. GsfProxy from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GsfProxy)
6. MozillaNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/MozillaNlpBackend)
7. NominatimNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/NominatimNlpBackend)
8. Recorder from [apkmirror](https://www.apkmirror.com/wp-content/themes/APKMirror/download.php?id=663426)
9. com.google.android.maps from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/com.google.android.maps)
### Repos:
* https://github.com/dan-v/rattlesnakeos-stack#prebuilts
* https://github.com/Hammergrat7/microg
