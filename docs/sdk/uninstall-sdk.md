# Uninstall SDK

In this section we will explain how to uninstall unwanted network SDK from the project.

##	Recommended

1.	Navigate to “SDK” menu.

![SDK Menu](../images/uninstall-sdk/1.png ":size=400 :class=center")

2.	Disable network, which you want to uninstall.

![Disable Network](../images/uninstall-sdk/2.png ":size=300 :class=center")

3.	Select “Uninstall SDK” button. Wait couple seconds for Unity to compile the project. After compile is completed network section will change with message that current network SDK is not installed in this project.

![Uninstalled Network](../images/uninstall-sdk/3.png ":size=300 :class=center")

##	Outsource

1.	Navigate to “SDK” menu

![SDK Menu](../images/uninstall-sdk/1.png ":size=400 :class=center")

2.	 Make sure that the network is disabled in the SDK menu.

![Disable Network](../images/uninstall-sdk/9.png ":size=300 :class=center")

3.	Delete network files from project.

![Delete Network Files](../images/uninstall-sdk/4.png ":size=400 :class=center")

4.	If you are getting errors, it means that scripting define symbols has not been removed correctly from the project.

![Errors](../images/uninstall-sdk/5.png ":size=400 :class=center")

5.	Navigate to File/Build Settings

![Open Build Settings](../images/uninstall-sdk/6.png ":size=200 :class=center")

6.	Select “Player Settings” button

![Open Player Settings](../images/uninstall-sdk/7.png ":size=400 :class=center")

7.  Scroll down and find “Scripting Define Symbols” field. Remove deleted network name from the list.

?> **Quick Tip:**  
•	Make sure that each network name is separated with semicolon ( ; )

![Remove Deleted Define](../images/uninstall-sdk/8.png ":size=400 :class=center")

8.  Wait couple seconds for Unity to compile the project. After compile is completed network section will change with message that current network SDK is not installed in this project.

![Uninstalled Network](../images/uninstall-sdk/3.png ":size=300 :class=center")