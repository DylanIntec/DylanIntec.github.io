---
layout: landing
title:  AR in Consulting
permalink: 2020-09-03-AR-for-consulting.html
---

# 5 uses for AR in consulting 

<model-viewer width="auto"
    src="/models/boatWave.glb"
    ios-src="/models/boatWave.usdz"
    style="width: 60%; height: 300px; margin-left: auto; margin-right: auto;"
    ar camera-controls background-color="#2CCC">
</model-viewer>

Along with 3D printing, AI, digital twins and cloud computing, AR/VR is a crucial facet of the 4th industrial revolution. As stated by KPMG Digital Delta Partner Piers Hogarth-Scott, [It is critical that business leaders understand these technologies and how to harness them to remain locally and globally competitive](https://home.kpmg/au/en/home/insights/2020/02/2020-fourth-industrial-revolution-benchmark.html).

This article explores some of the practical use cases for AR to deliver value at a low cost.

## Traditional AR/VR

When AR or VR is mentioned, an image such as below probably comes to mind. These purpose build headsets are powerful and deliver an immersive experience. This comes at a high cost, with one of the headsets retailing at AU$5,599.00. Fortunately, due to the decreasing cost of computing power, we can now experience AR right from our mobile phones. First, some terminology needs to be cleaned up.

![alt text](images/hololens.jpeg)
Microsoft Hololens Credit: [Microsoft](https://www.microsoft.com/en-us/hololens)

## Terminology

As the technology is new, there are different terminologies that can mean the same thing. 

### Virtual Reality (VR)
All of your surroundings are rendered. Think of putting on a headset that takes you to a different world. This requires a powerful GPU and expensive gear which is a full headset.

### Augmented Reality (AR)
Objects are rendered in the real world. AR takes less computing power and the gear can take the form of glasses or a phone.

#### Also known as:
*Windows Mixed Reality* - **Microsoft** \
*XR* - **Apple**

## How to view AR models

### iOS

iOS has a built-in AR feature called Quick Look on all phones newer than iPhone 6S. If a user opens either a usdz or reality file, the Quick Look feature will automatically be triggered. Models can then be viewed in object mode or placed in AR. The .usdz file can be created from the most common mesh file types, such as .obj and .glb.

### MacOS

macOS can display .usdz and .reality files, the same as iOS with no AR capability.

### Android 

Support for AR is a bit flaky on Android. This is generally due to devices not having the latest version of Android. A list of phones that support GoogleAR viewer can be found [Here](https://developers.google.com/ar/discover/supported-devices). Android phones display the .glb file type which, when opened, will trigger the GoogleAR viewer.

### Windows

Windows has support for .glb files built-in through the 3D Viewer app. The 3D Viewer app will also show any animations in the .glb file. Windows Mixed Reality compatible hardware is required to view in AR.

# Uses for AR in Consulting
Using any of the methods described above, 
### 1. Design

Reviewing structures can be much quicker and more intuitive using VR rather than using Navisworks or similar. No specialist viewing software is required and the models are easily shared. Models can be placed on the table in a meeting room for everyone to see, scale and move around. Different models can be overlapped to easily display the differences between versions.

<model-viewer width="100%"
    src="/models/props.glb"
    ios-src="/models/props.usdz"
    style="width: 80%; height: 300px; display: flex; justify-content: center;"
    ar autoplay camera-controls background-color="#2CCC">
</model-viewer>
Credits: \
[Nirav Joshi](https://grabcad.com/library/propeller-412) \
[Kumresh](https://grabcad.com/library/propeller-423)


### 2. Operations

As the models can be animated, entire operations can be modeled and animated by accurately constraining the model. The animation could also be connected to simulation data to show realistic  motions such as a ship's responses in waves. 

<model-viewer width="100%"
    src="/models/spoolLift.glb"
    ios-src="/models/spoolLift.usdz"
    style="width: 80%; height: 300px; display: flex; justify-content: center;"
    ar autoplay camera-controls background-color="#2CCC">
</model-viewer>

### 3. Interactive Deliverables

Using Reality Composer software by Apple, AR can be made fully interactive while also simulating gravity and object interactions. This could be used to make interactive deliverables to display results of a calculation. If you are on an iPhone 6S or above, click the  view in AR button on the below image for an interactive AR game.

<a href="file.usdz" rel="ar">
	<img src="file.jpg" alt="Object XYZ">
</a>

### 4. Surveys 

Using either photogrammetry or a laser scanning device, a model could be quickly built then viewed in VR in the office to help identify any anomalies or damage. The model below was created from 12 photographs and processed in [RealityCapture](https://www.capturingreality.com). The great accuracy of the mesh comes at a cost as the file size is large, originally 100Mb. This is at the limit for what phones can currently display in AR thus only the newest 2019 and 2020 phones will be able to display models this large.

<model-viewer width="100%"
    src="/models/statue.glb"
    ios-src="/models/statue.usdz"
    style="width: 80%; height: 300px; display: flex; justify-content: center;"
    ar autoplay camera-controls background-color="#2CCC">
</model-viewer>

### 5. Education

With the current travel limitations due to covid and budget constraints, it may be difficult for graduates to get valuable on-site experience. An alternative to this could be a creating an AR portal into an operations center or a model of a jacket.

### 6. Hot Desking

Using object detection, the global coordinates in the VR space can be locked to a fixed object in space. This allows tags or information to be connected to desks. The tags can be connected to a database and allow for dynamic updating of the office layout.
Photo of bubbles above desks.

![alt text](images/hotdesks.jpg)


### 7. Orientation 

Some office layout can be very complex and maps can be confusing. VR could provide easy directions to any meeting rooms, toilets or the kitchen.

![alt text](images/arrows.jpg)


