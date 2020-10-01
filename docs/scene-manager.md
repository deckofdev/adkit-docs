# Scene Manager

In this section we will explain how to add scene manager to the project. This component is required to initialize the plugin and the networks which has been enabled in the manager. Scene manager must be initialized in the scene where ads will be shown. Scene manager only needs to be added into the one scene. Before showing ads, make sure that the current scene or the scene before has already initialized scene manager.

We recommend initializing scene manager at start because it will have more time for ad networks to finish initializing process. In this way there will be less waiting time when requesting ads.

## Initialization

### Editor

In this section we will explain how to initialize scene manager in editor.

1. Open AdKit manager and select “Settings” tab.

![AdKit Manager Settings Tab](/images/scene-manager/1.png ":size=400 :class=center")

2. Find scene manager section.

![Scene Manager Section](/images/scene-manager/2.png ":size=400 :class=center")

3. There are two ways to initialize scene manager in the editor:
  1. Initialize at Start - scene manager will be initialized when project starts.
  2. Manually add to the scene - manually add scene manager to the scene where you want to initialize the plugin.

4. After adding scene to the project, message with loaded scene manager should appear.

![Initialize at Start](/images/scene-manager/4.png ":size=400 :class=center")

![Manually add to the scene](/images/scene-manager/4.png ":size=400 :class=center")

### Code

Following code initializes scene manager. Call it when you want to initialize scene manager into the project.

?> **Quick Tip:**  
• Scene manager can be initialized only once.

```csharp
  AdKitGeneral.InitializeSceneManager();
```
## API

### Is Scene Manager Initialized

Check if scene manager is initialized in the project.

```csharp
  bool initialized = AdKitGeneral.IsSceneManagerInitialized();
```

### Destroy Scene Manager

Following code destroys active scene manager.

!> **Prerequisites:**  
• Already Initialized scene manager into the project.

```csharp
  AdKitGeneral.DestroySceneManager();
```

## Automatically Initialize Networks

In this section we will explain how networks can be automatically initialized when plugin is ready.

?> **Quick Tip:**  
• Using compliances, networks will not be initialized until user provides a consent for active compliant.

1. Open AdKit manager and select “Settings” tab.

![AdKit Manager Settings Tab](/images/scene-manager/1.png ":size=400 :class=center")

2. Find scene manager section and activate “Auto Initialize Networks” field.

![Scene Manager Section Auto Initialize Networks](/images/scene-manager/3.png ":size=400 :class=center")

## Are Networks Initialized

You can check if networks are already initialized in the project.

!> **Prerequisites:**  
•	Initialized scene manager.

```csharp
  bool initialized = AdKitGeneral.AreNetworksInitialized();
```

## Manually Initialize Networks

You can also initialize networks via code using following function.

!> **Prerequisites:**  
• Initialized scene manager.

```csharp
  AdKitGeneral.InitializeNetworks();
```