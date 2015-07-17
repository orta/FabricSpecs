# FabricSpecs

*Note - These are the old, unofficial specs, you should use this only if you have very strong reasons to ~not~ update to the official Podspecs.*

A simple Specs repo containing the Twitter specs that were removed in [CocoaPods/Specs#12199](https://github.com/CocoaPods/Specs/pull/12199). If you were relying on these Specs, you can use this at the top of your Podfile:

```
source 'https://github.com/orta/FabricSpecs.git'
source 'https://github.com/CocoaPods/Specs.git'
```

This will prioritise looking for the removed Specs over the current master repo. 
