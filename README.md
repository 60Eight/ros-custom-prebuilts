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
- AuroraStore from [f-droid](https://f-droid.org/en/packages/com.aurora.store/)
- DroidGuard from 
- FakeStore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/FakeStore)
- GmsCore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GmsCore)
- GsfProxy from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GsfProxy)
- MozillaNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/MozillaNlpBackend)
- NominatimNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/NominatimNlpBackend)
- Recorder from [apkmirror](https://www.apkmirror.com/wp-content/themes/APKMirror/download.php?id=663426)
- YalpStore from
- com.google.android.maps from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/com.google.android.maps)

- https://github.com/dan-v/rattlesnakeos-stack#prebuilts
- https://github.com/Hammergrat7/microg
