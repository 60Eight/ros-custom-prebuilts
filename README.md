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
- AuroraStore from [F-Droid](https://f-droid.org/repo/com.aurora.store_3.apk)
- DroidGuard from 
- FakeStore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/FakeStore)
- GmsCore from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GmsCore)
- GsfProxy from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/GsfProxy)
- MozillaNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/MozillaNlpBackend)
- NominatimNlpBackend from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/NominatimNlpBackend)
- Recorder from
- YalpStore from
- com.google.android.maps from [lineageos4microg](https://github.com/lineageos4microg/android_prebuilts_prebuiltapks/tree/master/com.google.android.maps)

- https://github.com/dan-v/rattlesnakeos-stack#prebuilts
- https://github.com/Hammergrat7/microg
