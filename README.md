# Google Cardboard VR with Unity Navigation / Pathfinding
Simple scripts for adding Unity Navigation and Pathfinding to Google Cardboard VR. (from [Studio Pepwuper](http://www.pepwuper.com/portfolio/google-cardboard-vr-with-unity-navigation-pathfinding/))

- Video Demo: https://www.youtube.com/watch?v=k9ee3hakMLk
- Video How-to: https://www.youtube.com/watch?v=9w5WdImac2M

Direct Download Link to Unity Package (.unitypackage): https://github.com/pepwuper/Google-Cardboard-VR-Navigation/raw/master/GoogleCardboardVRNavigationForUnity.unitypackage

This works with [Google Cardboard Unity SDK](https://developers.google.com/cardboard/unity/). Import the SDK into your project before using this. 

To Set Up NavMesh for Google Cardboard VR:

1. Make sure the *GazePointer* control is set up. (See Google Cardboard Demo scene for more info)
2. Add **FollowPlayer** to **CardboardMain** prefab
3. Add a player game object to the scene. Assign the player game object to the *Player* variable on **FollowPlayer**
4. (optional) Also add **FollowPlayer** to the **Canvas** object in the Cardboard VR demo scene and assign the player gameobject to the Player variable if you want the menu to be at the player's feet at all times
5. Add **PlayerMotor** to player
6. Assign the **GazePointer** gameobject to the *Cursor* variable 
7. Set up nevmesh on the floor
8. Add an Event Trigger to the floor object
9. Add a "Pointer Click" event
10. Assign *Player* to the Object field, Select "Runtime Only", then Select "PlayerMotor" -> "SetDestinationToCursor"
11. Done!

- Google Cardboard Unity SDK: https://developers.google.com/cardboard/unity/
- Google Cardboard Unity SDK and Demo Download Link: https://developers.google.com/cardboard/unity/download
- Unity Navigation and Pathfinding: http://docs.unity3d.com/Manual/Navigation.html

---
© 2015 Studio Pepwuper http://www.pepwuper.com/