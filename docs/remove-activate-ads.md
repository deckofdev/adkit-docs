# Remove and Activate Ads

In this section we will explain how to completely remove ads from the project. Later you can activate them again. This function is useful when having IAP ability to remove ads from the project.

!> **Prerequisites:**  
•	Initialized scene manager.

## Banner Ads

```csharp
//Returns a boolean of banner ads state in the project.
bool bannerAdsActive = AdKitGeneral.AreBannerAdsRemoved();

//Remove banner ads from the project.
AdKitGeneral.RemoveBannerAds();

//Activate banner ads in the project.
AdKitGeneral.ActivateBannerAds();
```

## Interstitial Ads

```csharp
//Returns a boolean of interstitial ads state in the project.
bool interstitialAdsActive = AdKitGeneral.AreInterstitialAdsRemoved();

//Remove interstitial ads from the project.
AdKitGeneral.RemoveInterstitialAds();

//Activate interstitial ads in the project.
AdKitGeneral.ActivateInterstitialAds();
```

## Rewarded Ads

```csharp
//Returns a boolean of rewarded ads state in the project.
bool rewardedAdsActive = AdKitGeneral.AreRewardedAdsRemoved();

//Remove rewarded ads from the project.
AdKitGeneral.RemoveRewardedAds();

//Activate rewarded ads in the project.
AdKitGeneral.ActivateRewardedAds();
```