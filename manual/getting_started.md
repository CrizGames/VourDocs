Getting Started with Vour
=========================

## 1. What is Vour
 If you don't know already, [Vour](https://assetstore.unity.com/) (stands for **V**irtual T**our**) is a asset for the [Unity Game Engine](https://unity.com/). It helps you making virtual tours in 3D scenes and/or with images/videos in 2D, 360°, 3D, and 3D 360°. There is also Oculus VR support.

## 2. Installation
 1. Import the [Oculus Integration Package](https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022).

 2. Setup project for VR with XR Plugin Framework like it is described [here](https://developer.oculus.com/documentation/unity/unity-conf-settings/).

 3. Make sure TextMesh Pro is installed.
 
 4. Install the [Vour Package](https://assetstore.unity.com/).

## 2. Create a Basic Tour
 First, we need to setup the scene.
 1. Create a new scene.

 2. Delete Main Camera.

 3. Create a Location Manager via **Tools** > **Vour** > **Add Location Manager**.

 4. Create a Player via **Tools** > **Vour** > **Add Player**.

 Now we are ready to create a small tour.

 1. Create a location of your choice via **Tools** > **Vour** > **Add Location** > * **Location**.

 2. Assign the texture/video to it and change the other settings as you need them.

 3. With the location game object selected, click "Add Teleport Point" in the inspector and position it where you want your next location to be.

 4. Create another location and set it up.

 5. Now go back to the Teleport Point and drag the newly created location into "Target Location". Now you can teleport from the first location to the second. If you want to teleport back, create a Teleport Point at the second location and assign the first location as its target location.

 6. Drag the first location into the "Start Location" field of the Location Manager.

 7. Done! If you did everything correct, you should now be able to explore the locations in play mode.