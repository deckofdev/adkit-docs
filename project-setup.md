# Project Setup

In this part we will cover all the initial steps that needs to be taken before importing AdKit package. These steps are necessary for new or already existing projects. 

## Update Unity Editor

In this step we will check whether our Unity Editor is up to date. Our package always will be updated to support the newest Unity Editor version. To get constant updates from our package, Unity Editor always needs to be up to date.

1. Open Unity editor. Select “Help” button from the top toolbar and click “Check for Updates” button.

![Help Section](/images/project-setup/1.png ":size=200 :class=center")

2.	Unity Editor will check for any updates that are available. For this documentation we will be using Unity Editor 2019.3.5f1.

![Check For Updates](/images/project-setup/2.png ":size=400 :class=center")

## Add Modules

Now we will check if Unity Editor has all the modules which are required for mobile platforms (Android or iOS).

1.	Open Unity Hub. Select “Install” tab and press “Add Modules” button. 

![Unity Hub](/images/project-setup/3.png ":size=600 :class=center")

2.	In the new window, depending on which platform project is developed, select and install following modules:

?> **Quick Tip:**  
•	If project is developed on both platforms, then make sure that all displayed modules are selected.

  1.	**Android** – “Android Build Support” with “Android SDK & NDK Tools” and “OpenJDK”.
  2.	**iOS** – “iOS Build Support”.

![Modules](/images/project-setup/4.png ":size=500 :class=center")

## Select Mobile Platform

In this step we will select mobile platform on which we are going to deploy our project.

?> **Quick Tip:**  
•	In this documentation we will be using Android platform. Do not worry, we still going to process all the steps that are necessary for iOS platform.

1.	Go to “File” and select “Build Settings”. 

![File Section](/images/project-setup/5.png ":size=200 :class=center")

2.	Switch to iOS or Android platform. 

![Build Settings](/images/project-setup/6.png ":size=400 :class=center")

3.	After switching platform, navigate to “Player Settings” and change package name field.

![Player Settings](/images/project-setup/7.png ":size=400 :class=center")

## ~(Android)~ Enable Development Kits

This step is required to check whether all development kits are enabled for Android platform.

1.	Navigate to “Edit” and select “Preferences” 

![Edit Section](/images/project-setup/8.png ":size=200 :class=center")

2.	In the new window select “External Tools” and scroll to the bottom where Android development tools will be displayed. Make sure that they all are enabled.

?> **Quick Tip:**  
•	Sometimes Unity Editor cannot automatically set SDKs, thus error about missing SDKs may appear. In this case, copy SDKs path, disable recommended set and insert them manually.

![External Tools](/images/project-setup/9.png ":size=400 :class=center")