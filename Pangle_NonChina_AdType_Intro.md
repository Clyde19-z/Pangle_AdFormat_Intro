



# How to create an Ad placement on Pangle' platform?

Currently, Pangle is supporting different Ad Formats for China Mainland Traffic and Non China Mainland Traffic and a certian Ad format may have different rendering method. 
For example, Splash Ads is only supported for China Mainland Traffic rather than Non China Mainland Traffic, but Rewarded Video Ads is supported for both of them. 
However, even though Rewarded Video Ads is supported for all the traffic, you have to use 'Template Rendering' for China Mainland Traffic and use 'Non Template Rendering' (also known as 'Traditional Rendering') for Non China Mainland Traffic.

If you created a wrong placement, you cannot receive any ads from Pangle.
Thus, in this article, we're trying to indroduce how to create an Ad placement for Non China Mainland Traffic on Pangle's platform.


## China Mainland's Traffic

Ad formats that supported for China Mainland's Traffic are:
- Native Ads
- Banner Ads
- Interstitial Video Ads
- Rewarded Video Ads
- Splash Ads
- Vertical Draw Video Ads
- Interstitial Static Image Ads
- In-Stream Ads


## Non China Mainland's Traffic
Ad formats that supported for Non China Mainland's Traffic are:

- Native Ads
- Banner Ads
- Interstitial Video Ads
- Rewarded Video Ads

### Create a Native Ads Placement

### Create a Banner Ads Placement

### Create an Interstitial Video Ads Placement

### Create a Rewarded Video Ads Placement

## Pangle's supported Countries/Regions (2021 Feb)
- CN
- JP
- KR
- TW
- TH
- VN
- MY
- SA
- AE
- TR
- EG
- GB
- FR
- DE
- IT
- ES
- ID
- RU

## Import Pangle SDK through CocoaPods (Recommened):
The simplest way to import the SDK into an iOS project is to use CocoaPods. Open your project's Podfile and add this line to your app's target:

- Note: Import Pangle SDK that the version is higher than v3.4.0.0
```XML
pod 'Ads-Global', '~>3.4.1.1' 
```


- Note: If you wanna import old version of Pangle SDK that the version is lower than v3.4.0.0, as shown below:
```XML
pod 'Bytedance-UnionAD', '~>3.3.6.2'
```



## Download Pangle SDK Manually:
Download and unzip the SDK framework from Pangle Platform directly, and import the following frameworks and bundles into your Xcode project manually:

- `BUAdSDK.framework`
- `BUFoundation.framework`
- `BUAdSDK.bundle`
- `BUVAAuxiliary.framework`

<img src="https://github.com/JohnnyWangMiura/Pangle-iOS-SDK-Integration-Guideline/blob/main/destination.png" />



**Note: When you upgrade the SDK, you need to update all frameworks and bundle files.**


Please make sure that `Copy Bundle Resource` contains `BUAdSDK.bundle`.

<img src="https://github.com/JohnnyWangMiura/Pangle-iOS-SDK-Integration-Guideline/blob/main/bundle.png" />





### Xcode Compiler Option Settings

#### Add Permissions

Add the parameter `-objc` to `Other Linker Flags` in build settings, and the SDK supports `- all_ load`

##### Detailed Steps:

<img src="https://github.com/JohnnyWangMiura/Pangle-iOS-SDK-Integration-Guideline/blob/main/permission.png" />




#### Add Dependency Libraries

- StoreKit.framework
- MobileCoreServices.framework
- WebKit.framework
- MediaPlayer.framework
- CoreMedia.framework
- AVFoundation.framework
- CoreTelephony.framework
- SystemConfiguration.framework
- AdSupport.framework
- CoreMotion.framework
- Accelerate.framework
- libresolv.9.tbd
- libc++.tbd
- libz.tbd
- libsqlite3.tbd
- libbz2.tbd
- libxml2.tbd
- libiconv.tbd
- Security.framework


**Note: Add the `ImageIO.framework` if the above dependency library is still reporting errors.**

##### Detailed Steps:

<img src="https://github.com/JohnnyWangMiura/Pangle-iOS-SDK-Integration-Guideline/blob/main/library.png"/>


#### Add language configuration

<img src="https://github.com/JohnnyWangMiura/Pangle-iOS-SDK-Integration-Guideline/blob/main/language.png"/>






