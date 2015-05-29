# Google Cardboard VR with Unity Navigation / Pathfinding
Simple scripts for adding Unity Navigation and Pathfinding to Google Cardboard VR. 

Video Demo: https://www.youtube.com/watch?v=k9ee3hakMLk

Direct Download Link to Unity Package (.unitypackage): https://github.com/pepwuper/Google-Cardboard-VR-Navigation/raw/master/GoogleCardboardVRNavigationForUnity.unitypackage

This works with [Google Cardboard Unity SDK](https://developers.google.com/cardboard/unity/). Import the SDK into your project before using this. 

To Set Up NavMesh for Google Cardboard VR:

1. Make sure the GazePointer control is set up. (See Google Cardboard Demo scene for more info)
2. Add FollowPlayer to CardboardMain prefab
3. Add a player game object to the scene. Assign the player game object to the Player variable
4. (optional) Also add FollowPlayer to the Canvas object in the demo scene and assign the player gameobject to the Player variable if you want the menu to be at the player's feet at all times
4. Add PlayerMotor to player
5. Assign the GazePointer gameobject to the Cursor variable 
6. Set up nevmesh on the floor
7. Add an Event Trigger to the floor object
8. Add a "Pointer Click" event
9. Assign Player to the Object field, Select "Runtime Only", then Select "PlayerMotor" -> "SetDestinationToCursor"
10. Done!

- Google Cardboard Unity SDK: https://developers.google.com/cardboard/unity/
- Google Cardboard Unity SDK and Demo Download Link: https://developers.google.com/cardboard/unity/download
- Unity Navigation and Pathfinding: http://docs.unity3d.com/Manual/Navigation.html

