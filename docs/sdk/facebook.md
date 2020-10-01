# Facebook

In this section we will explain how to install, enable and use Facebook Audience Network Ads with AdKit plugin. We will explain in detail on how to create new project in the Facebook Audience Network dashboard and how to synchronize with the plugin.

!> **Prerequisites:**  
•	Registered Facebook account  
•	Active Facebook business manager account

## Installation

1. Select preferred SDK version:
  1. Recommended – this version is tested by our developers. Version is fully compatible with our plugin and other networks. Recommended version provides more functionality, including separate SDK folder where all recommended SDK will be installed. Also, we’re going to keep up to date the network with each plugin update.
  2. Latest – this version might be the newer version comparing to recommended version. However, this version might not be compatible with the current AdKit version. Only use this version if there is a need for it.

![SDK Versions](../images/unity-ads/1.png ":size=200 :class=center")

2. When SDK version has been selected press “Download SDK” button to download the plugin. In the top right corner ad formats, which are available in this plugin, are displayed:
  1. Yellow – banner ad.
  2. Green – interstitial ad.
  3. Blue – rewarded ad.

![Facebook Missing](../images/facebook/1.png ":size=400 :class=center")

3. After importing the plugin, message with installed plugin will appear. Also, if you choose to download recommended version, next to the header will be displayed SDK version and “Uninstall SDK” button at the bottom which will allow you to quickly delete installed SDK.
  1. Version – which version is currently installed (Recommended version only).
  2. Available Ad Formats – which ad formats are available. After enabling specific ad format, specific icon will become colored.
  3. Active SDK – enable or disable SDK from AdKit plugin.
  4. Uninstall SDK – uninstall network from plugin. (Recommended version only).
  5. Dashboard – opens Unity Ads online dashboard.

![Facebook Imported](../images/facebook/2.png ":size=400 :class=center")


4. Enable plugin and wait couple seconds for Unity Editor to finish loading files.

![Loading Icon](../images/unity-ads/3.png ":size=30 :class=center")

5. After plugin loading finished message with installed and enabled plugin will be displayed.
  1. Test Mode – Facebook Audience Network provides test mode for each ad format. Enable it if you want to display test ads while developing.
  2. Banner Ads Active – if enabled,Facebook Audience Network will be active to select for mediation in banner profiles.
  3. Interstitial Ads Active – if enabled, Facebook Audience Network  will be active to select for mediation in interstitial profiles.
  4. Rewarded Ads Active – if enabled, Facebook Audience Network will be active to select for mediation in rewarded profiles.

![Facebook Enabled](../images/facebook/3.png ":size=400 :class=center")

6. ~(Android)~ Navigate to “Assets” and now select “External Dependency Manager”, expand “Android Resolver” and select “Force Resolve” button.

![Android Resolver](../images/admob/5.png ":size=400 :class=center")

## New Project

In this section we will explain how to create project using Facebook Audience Network dashboard and how to synchronize all IDs with the plugin.

1. Visit [https://developers.facebook.com](https://developers.facebook.com)
2. Expand “My Apps” and select “Create App” button.

![Create App](../images/facebook/4.png ":size=200 :class=center")

3.	Fill in “Display Name” and “Contact Email” fields.

![Create New App ID](../images/facebook/5.png ":size=400 :class=center")

4.	In the new page find “Audience Network” section and press “Set Up” button.

![Audience Network Section](../images/facebook/6.png ":size=250 :class=center")

5.	Select your Business Manager account and click “Next”.

![Log In With Business Manager](../images/facebook/7.png ":size=400 :class=center")

6.	Fill in “Property name” field and select “Next”.

![Property Name](../images/facebook/8.png ":size=400 :class=center")

7.	Navigate to right toolbar. Expand “Integration” and select “Properties” button.

![Properties](../images/facebook/9.png ":size=250 :class=center")

8.	In the following page select project property.

![Game](../images/facebook/10.png ":size=100 :class=center")

9.	Select one of the following platforms.

![Select Platform](../images/facebook/11.png ":size=400 :class=center")

10.	If the project is already published on Google Play Store or Apple App Store, then select “App is live” and enter store link. If the project is not published, then select “App is not live”. If you are planning to use more than one network in your project, then check “This app is using mediation” property and click “Submit” button.

![Submit App](../images/facebook/12.png ":size=400 :class=center")

11.	Navigate to right toolbar. Expand “Integration” and select “Properties” button.

![Properties](../images/facebook/9.png ":size=250 :class=center")

12.	In the following page select project property.

![Game](../images/facebook/10.png ":size=100 :class=center")

13.	Press “+ Create Ad Space” button.

![Android App](../images/facebook/13.png ":size=400 :class=center")

14.	Fill in “Name” field and provide brief explanation about your project and where ads will be shown. After providing description, select “Create Ad Space” button.

![Create Ad Space](../images/facebook/14.png ":size=400 :class=center")

## Banner Ads‎‎‏‏‎‏‏‎ ‎

In this section we will explain how to create banner ad in Facebook Audience Network dashboard and then synchronize it with AdKit Plugin. 

1.	Navigate to right toolbar. Expand “Integration” and select “Properties” button.

![Properties](../images/facebook/9.png ":size=250 :class=center")

2.	In the following page select project property.

![Game](../images/facebook/10.png ":size=100 :class=center")

3.	Select Ad Space.

![Android App](../images/facebook/15.png ":size=400 :class=center")

4.	Press “+ Create Placement”.

![Placements](../images/facebook/16.png ":size=250 :class=center")

5.	Fill in “Placement name” field.

![Placement Name](../images/facebook/17.png ":size=400 :class=center")

6.	Select Banner placement.

![Banner Placement](../images/facebook/18.png ":size=400 :class=center")

7.	Press “Create Placement” button.

![Create Placement](../images/facebook/19.png ":size=400 :class=center")

8.	Banner ads has been created. Do not forget to copy ID.

![Banner Ads](../images/facebook/20.png ":size=200 :class=center")

9.	Navigate back to Unity Editor and enable “Banner Ads Active”. Fill in “Banner ID” field with ID that has been created in Facebook Audience Network dashboard.

![Fill in Banner ID](../images/facebook/21.png ":size=400 :class=center")

## Interstitial Ads

In this section we will explain how to create interstitial ad in Facebook Audience Network dashboard and then synchronize it with AdKit Plugin. 

1.	Navigate to right toolbar. Expand “Integration” and select “Properties” button.

![Properties](../images/facebook/9.png ":size=250 :class=center")

2.	In the following page select project property.

![Game](../images/facebook/10.png ":size=100 :class=center")

3.	Select Ad Space.

![Android App](../images/facebook/15.png ":size=400 :class=center")

4.	Press “+ Create Placement”.

![Placements](../images/facebook/16.png ":size=250 :class=center")

5.	Fill in “Placement name” field.

![Placement Name](../images/facebook/22.png ":size=400 :class=center")

6.	Select Interstitial placement.

![Interstitial Section](../images/facebook/23.png ":size=400 :class=center")

7.	Press “Create Placement” button.

![Create Placement](../images/facebook/24.png ":size=400 :class=center")

8.	Interstitial ads have been created. Do not forget to copy ID.

![Interstitial Ads](../images/facebook/25.png ":size=200 :class=center")

9.	Navigate back to Unity Editor and enable “Interstitial Ads Active”. Fill in “Interstitial ID” field with ID that has been created in Facebook Audience Network dashboard.

![Fill In Interstitial ID](../images/facebook/26.png ":size=400 :class=center")

## Rewarded Ads

In this section we will explain how to create rewarded ad in Facebook Audience Network dashboard and then synchronize it with AdKit Plugin. 

1.	Navigate to right toolbar. Expand “Integration” and select “Properties” button.

![Properties](../images/facebook/9.png ":size=250 :class=center")

2.	In the following page select project property.

![Game](../images/facebook/10.png ":size=100 :class=center")

3.	Select Ad Space.

![Android App](../images/facebook/15.png ":size=400 :class=center")

4.	Press “+ Create Placement”.

![Placements](../images/facebook/16.png ":size=250 :class=center")

5.	Fill in “Placement name” field.

![Placement Name](../images/facebook/27.png ":size=400 :class=center")

6.	Select Rewarded placement.

![Rewarded Section](../images/facebook/28.png ":size=400 :class=center")

7.	Press “Create Placement” button.

![Create Placement](../images/facebook/24.png ":size=400 :class=center")

8.	Rewarded ads have been created. Do not forget to copy ID.

![Rewarded Ads](../images/facebook/29.png ":size=200 :class=center")

9.	Navigate back to Unity Editor and enable “Rewarded Ads Active”. Fill in “Rewarded ID” field with ID that has been created in Facebook Audience Network dashboard.

![Fill In Rewarded ID](../images/facebook/30.png ":size=400 :class=center")