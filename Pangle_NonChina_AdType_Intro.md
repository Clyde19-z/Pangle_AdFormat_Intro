



# Ad Formats Supported by Pangle

Currently (2021 February), Pangle is supporting different Ad Formats for China Mainland Traffic and Non China Mainland Traffic and a certian Ad format may have different rendering method. 
For example, Splash Ads is only supported for China Mainland Traffic rather than Non China Mainland Traffic, but Rewarded Video Ads is supported for both of them. 
However, even though Rewarded Video Ads is supported for all the traffic, you have to use 'Template Rendering' (also known as 'Traditional Rendering') for China Mainland Traffic and use 'Non Template Rendering' (also known as 'Origin Rendering')for Non China Mainland Traffic.

If you created a wrong placement, you cannot receive any ads from Pangle.
Thus, in this article, we're trying to indroduce Ad formats supported by Pangle.

## 1. For China Mainland's Traffic

Ad formats that supported for China Mainland's Traffic are:
- Native Ads
- Banner Ads
- Interstitial Video Ads
- Rewarded Video Ads
- Splash Ads
- Vertical Draw Video Ads
- Interstitial Static Image Ads
- In-Stream Ads (Whitelist needed)


## 2. For Non China Mainland's Traffic
Ad formats that supported for Non China Mainland's Traffic are:

- Native Ads
- Banner Ads (Whitelist needed)
- Interstitial Video Ads
- Rewarded Video Ads


Supported size and rendering method are:


|                  | Native Ads | Banner Ads | Interstitial Video Ads| Rewarded Video Ads |
|-------------------|--------------------|--------------------|---------------------|---------------------|
| Supported Size  | 1280x720 Video, 640x640 Video, 1200x628px Image, 640x640px Image |  320x50, 300x250 | Fullscreen |  Fullscreen |
| Supported Rendering Method| Non Template   |  Template   | Non Template | Non Template |
| Remarks          |    | 320x50 and 300x250 are also known as 640x100 and 600x500 | Interstitial Video Ads is also known as Fullscreen Video Ads |   |



## 3. Pangle's supported Countries/Regions 

Currently (2021 February), Pangle is supporting the following countries or regions:
CN/JP/KR/TW/TH/VN/MY/SA/AE/TR/EG/GB/FR/DE/IT/ES/ID/RU

**NOTE:**
If you have both China Mainland Traffic and Non China Mainland Traffic, please note that:

**For Android App, you should use the Pangle SDK（The Chinese Mainland) for your China Mainland Traffic and the Pangle SDK (Outside the Chinese Mainland) for your Non China Mainland Traffic.**

**For iOS App, you have two options:**

**1. Use the Pangle SDK（The Chinese Mainland) for your China Mainland Traffic and the Pangle SDK (Outside the Chinese Mainland) for your Non China Mainland Traffic.**

**2. Integrate both the Pangle SDK（The Chinese Mainland) and the Pangle SDK (Outside the Chinese Mainland) into one project. You can find more in the 'Integration Doc' on Pangle's platform.**















