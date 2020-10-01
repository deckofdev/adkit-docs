# Event Manager

In this section we will explain how to setup event manager into the project and what events are available for each ad format.

## Initialize Event Manager

In this section we will initialize event manager into the project. For different scenes you will have to initialize event manager separately.

1. Navigate to ad format and select ad profile on which events will be added. If the message with warning pop up, then it means that the event manager is not attached to the current scene. 

![Missing Event Manager](/images/event-manager/1.png ":size=400 :class=center")

2.	Open AdKit manager and select “Settings” tab.

![Settings](/images/settings/2.png ":size=400 :class=center")
 
3.	Find “Event Manager” section and select “Add Event Manager” to add event manager to current scene.

![Add Event Manager](/images/event-manager/2.png ":size=400 :class=center")
 
4.	Message with successfully loaded event manager will be shown.

![Event Manager Is Loaded](/images/event-manager/3.png ":size=400 :class=center") 

5.	Navigate to ad format field and select profile on which event must be added. At the bottom of ad profile “Events” section will appear.

![Events Section](/images/event-manager/4.png ":size=400 :class=center")

## Banner Ad Events

In this section we will provide information about all the events that are available for banner ads and explain when they are called.

?> **Quick Tip:**  
•	Unity Ads does not support banner ad events.

![Banner Events](/images/event-manager/5.png ":size=200 :class=center")

|           |     Event                     |     When it is called?                         |
|-----------|-------------------------------|------------------------------------------------|
|     1.    |     On Banner Create          |     When banner profile is created.            |
|     2.    |     On Banner Load            |     When banner request finished.              |
|     3.    |     On Banner Fail to Load    |     When banner request failed to   finish.    |
|     4.    |     On Banner Show            |     When banner is shown.                      |
|     5.    |     On Banner Open            |     When banner is clicked and   opened.       |
|     6.    |     On Banner Hide            |     When banner is hidden.                     |
|     7.    |     On Banner Destroy         |     When banner profile is   destroyed.        |

## Interstitial Ad Events

In this section we will provide information about all the events that are available for interstitial ads and explain when they are called.

![Interstitial Events](/images/event-manager/6.png ":size=200 :class=center")

|           |     Event                           |     When it is called?                               |
|-----------|-------------------------------------|------------------------------------------------------|
|     1.    |     On Interstitial Create          |     When interstitial profile is   created.          |
|     2.    |     On Interstitial Load            |     When interstitial request finished.              |
|     3.    |     On Interstitial Fail to Load    |     When interstitial request failed   to finish.    |
|     4.    |     On Interstitial Show            |     When interstitial is shown.                      |
|     5.    |     On Interstitial Close           |     When interstitial is closed.                     |
|     6.    |     On Interstitial Destroy         |     When interstitial profile is   destroyed.        |

## Rewarded Ad Events

![Rewarded Events](/images/event-manager/7.png ":size=200 :class=center")

In this section we will provide information about all the events that are available for rewarded ads and explain when they are called.

|           |     Event                       |     When it is called?                           |
|-----------|---------------------------------|--------------------------------------------------|
|     1.    |     On Rewarded Create          |     When rewarded profile is   created.          |
|     2.    |     On Rewarded Load            |     When rewarded request finished.              |
|     3.    |     On Rewarded Fail to Load    |     When rewarded request failed to   finish.    |
|     4.    |     On Rewarded Show            |     When rewarded is shown.                      |
|     5.    |     On Rewarded Finish          |     When rewarded is finished.                   |
|     6.    |     On Rewarded Destroy         |     When rewarded profile is   destroyed.        |
|     6.    |     On Interstitial Destroy     |     When interstitial profile is   destroyed.    |