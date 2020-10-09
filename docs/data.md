# Data

**Data** – it is another innovative part of the plugin which allows developers to save project data with all ad profiles and settings. Developers then can reuse the same data in other projects saving a lot of time as it is no longer needed to setup new project ads from scratch.

In this section we will explain how to save project data and import it to another project with all the same ad profiles and settings.

# Save Data

In this section we will explain how to save project data.

1.	Open AdKit manager and select “Settings” tab.

![Settings](/images/settings/2.png ":size=400 :class=center")
 
2.	Navigate to “Data” section and select “Save Manager Data”.

![Data Section](/images/data/1.png ":size=400 :class=center")
 
3.	Select location where to save data and click “Save”.

![Save Location](/images/data/2.png ":size=400 :class=center")

# Load Data

In this section we will provide information on how to load data from another project.

1.	Open AdKit manager and select “Settings” tab. 

![Settings](/images/settings/2.png ":size=400 :class=center")

2.	Navigate to “Data” section and select “Settings Data File” field.

![Data Section](/images/data/1.png ":size=400 :class=center")

3.	In the opened window select new data file.
 
![Data Location](/images/data/3.png ":size=200 :class=center")

4.	If current scene contains event manager, then an action will pop up asking to delete existing events from scene or leave them.
  1.	Yes, delete – deletes old events from the scene.
  1.	No, leave – leaves old events in the scene.
  3.	Cancel, revert data – resets to previous selected data.

?> **Quick Tip:**  
•	If the selected data has been used in the scene or old data events will be useful in the future, then it is recommended to leave old events. 

![Delete Current Scene Events](/images/data/4.png ":size=400 :class=center")

 
5.	If the new data file will contain network SDK(s) which are not installed in the current project, then error will pop up explaining which network SDK(s) are not installed. There are two actions that can be made:
  1.	Install/Enable Missing SDK(s) – opens SDK menu to install and enable all missing SDK(s). After installing all missing SDK(s) error will disappear.
  2.	Discard Missing Ad Networks from Mediation – manager will delete all networks, that are missing in the project, from each profile mediation 

![Missing Ad Networks](/images/data/5.png ":size=400 :class=center")