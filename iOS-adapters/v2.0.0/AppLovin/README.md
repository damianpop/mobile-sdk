# AppLovin - adapter info

## Compatibililty

| Network | Adapter version | Third party SDK version | Fyber SDK version |
|:----------:|:-------------:|:-----------------------:|:------------:|
| AppLovin | 2.2.0 | 2.5.3 | 7.0.2 |

**Important:** *The AppLovin Mobile SDK supports iOS 6 or higher.*

## Example parameters

* **name**: `AppLovin`
* **settings**:
	* **SPAppLovinSdkKey**
	* **SPAppLovinEnableVerboseLogging**: `YES` | `NO`
	
## Required frameworks

* `AdSupport.framework`
* `AVFoundation.framework`
* `CoreTelephony.framework`
* `CoreGraphics.framework`
* `CoreMedia.framework`
* `MediaPlayer.framework`
* `SystemConfiguration.framework`
* `UIKit.framework`

## Required linker flags

* `-ObjC`
* `-all_load`