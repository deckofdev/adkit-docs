# Troubleshooting

In this section we will provide help for the most common errors that can appear in the project. If you encounter the problem that is not defined in this section, please contact us using “Report a Bug” link which is provided in “Overview” section.

## Both Platforms

#### _(AdMob)_ App crashes right after starting it on device

1.	Navigate to “Assets” expand “Google Mobile Ads” and select “Settings” field. 

![Navigate To AdMob Settings](/images/troubleshooting/1.png ":size=300 :class=center")

2.	In the opened window make sure that “Google AdMob” is enabled and device app ID, on which you are launching the app, is filled.

![AdMob Settings](/images/troubleshooting/2.png ":size=400 :class=center")

## Android

#### _(AdMob, Facebook, IronSource, AdColony)_ Ads does not appear on device

1.	Navigate to “Assets” and now select “External Dependency Manager”, expand “Android Resolver” and select “Force Resolve” button.

![Force Resolve](/images/troubleshooting/3.png ":size=400 :class=center")

## iOS

#### _(AdMob, IronSource, AdColony)_ Error “Library not found for -lPods-Unity-iPhone” when building xCode

![Library not found](/images/troubleshooting/4.png ":size=400 :class=center")

It means you probably do not have installed CocoaPods on your Mac. To install it you need to follow instructions below:
1.	Open terminal.
2.	Run following command: “sudo gem install -n /usr/local/bin cocoapods”.
3.	You need to provide user password when requested.
4.	After installation is finished run following command: “pod install”.
5.	When installation is completed come back to Unity Editor and re-build your project.
6.	Open xCode project using .xcworkspace file.
7.	Now project should build without the error. Make sure that the ads are displayed on your device.
