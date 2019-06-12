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
- https://github.com/dan-v/rattlesnakeos-stack#prebuilts
- https://github.com/Hammergrat7/microg
