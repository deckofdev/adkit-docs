# COPPA Compliance

Our plugin does not collect any personal information. However, ad networks, which are available in this plugin does. Because of this, you need to provide more information for the user about available ad networks and what personal information they can collect. In this section we will explain all the steps that are needed to make your project COPPA compliant. 

?> **Quick Tip:**  
•	COPPA is valid only for ad networks that are available in this plugin. If you still not sure if your app is COPPA compliant make sure to council with your lawyer.

## Enable COPPA Compliant

In this section we will explain how to enable COPPA compliant in the project.

?> **Quick Tip:**  
•	You can also enable COPPA compliant via code. It is useful if you are planning to check whether the user is younger than 13 years old. In that case you will be able to enable COPPA compliant only for young users. 

1. Navigate to “SDK” menu and enable “COPPA Compliant” field.

![Compliance Section](../images/coppa/1.png ":size=400 :class=center")

## Setup Unity Ads

1.	After enabling COPPA in SDK section, navigate to “Unity Ads” section and open dashboard by pressing “Dashboard” button.

![Unity Ads Section](../images/coppa/2.png ":size=400 :class=center")

2.	Navigate to the project and select “Project settings” field.

![Project Settings](../images/coppa/3.png ":size=200 :class=center")

3.	Find “Age designation” field and select edit button.

![Age Destination](../images/coppa/4.png ":size=400 :class=center")

4.	In new window select “This app is directed to children under the age of 13” and click “Save” button.

![App Is Directed To Children Under The Age Of 13](../images/coppa/5.png ":size=400 :class=center")

## Setup IronSource

1.	After enabling COPPA in SDK section, navigate to “IronSource” section and open dashboard by pressing “Dashboard” button.

![IronSource Section](../images/coppa/6.png ":size=400 :class=center")

1.	At the bottom of the dashboard find your project and select edit button.

![Project](../images/coppa/7.png ":size=300 :class=center")

2.	Enable “COPPA” field and click “Save” button.

![App Details](../images/coppa/8.png ":size=400 :class=center")

## API

In this section we will provide all the function that are available for setting up COPPA.

### Get COPPA compliant state in the project

!> **Prerequisites:**  
•	Initialized scene manager.

```csharp
AdKitGeneral.IsCOPPACompliantEnabled();
```

Check if COPPA compliant is enabled in the project.
 
### Manually set COPPA compliant state in the project

Set COPPA compliant state via code.

?> **Quick Tip:**  
•	This is useful if you are planning to enable COPPA compliant only for specific users.

!> **Prerequisites:**  
•	Initialized scene manager.

```csharp
//Enable COPPA compliant in the project.
AdKitGeneral.SetCOPPACompliant(true);

//Disable COPPA compliant in the project.
AdKitGeneral.SetCOPPACompliant(false);
```