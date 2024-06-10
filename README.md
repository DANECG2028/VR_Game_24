# VR_Game_24
Date: April 14, 2024  
Features Added/Updated Since Last Update
- Downloaded Final IK
- Added Full VR Body Integration with Ready Player Me and Final IK

Issues Encountered
- Minor texture problem/rendering pipeline issue *not big deal for now*

Lessons Learned
- Learned about rendering pipeline in Unity

Date: May 13, 2024
Features Added/Updated Since Last Update
- Created an entirely new scene
- Added a laser gun and a few interactables
- Tested game events with interactables
- Added game objects and decorative objects

Issues Encountered
- The laser gun is supposed to make one of the intractables turn into smaller pieces of itself to simulate the item breaking from the gun, but the item is just falling from the world instead, might not fix and just scrap as it is not important to my gameplay concepts.

Lessons Learned
- It is now easier for me to set up a VR game project scene in Unity with all the necessary default settings and steps required. I can do it more efficiently now.

Date: May 26, 2024
Features Added/Updated Since Last Update
- Added a working door to the game environment
- Added a working button that triggers an in-game door
- Fixed bug from last update with breakable interactable object
- Interactable object now works properly when interacted with by the ray gun
- Added basic VR locomotion and teleportation movement
- The player can now explore the entire ship via default controller movement or teleportation
- Added a working wheel and lever
- Added a working ladder that the player can use

Issues Encountered
- I found that testing the game using Quest Link is getting too laggy, it may be because I have not optimized the game and my computer's age is showing.
- I found a minor bug that is allowing me to float in mid-air after I use the ladder provided by XRIT, seems like an easy fix. 

Lessons Learned
- The reason the breakable interactable was not working properly was that all the meshes of the smaller objects were enabled and that was messing with the the big parent object.
- Learned that making the ship fly might not be possible due to gameplay issues/limitations. Will continue to research.

Date: June 9, 2024
Features Added/Updated Since Last Update
- Added more asteroids to the game scene, making the game look more alive and big. 
- Added a custom audio that plays when the game loads. This will be the foundation of the story of the game.
- Added a full-size "planet"
- Added timeline to a game object that will allow me to create a story and will trigger specific audios to help guide the player and to drive the story forward when the player does something unexpected and or expected.

Issues Encountered
- I don't know why the sphere game object that is supposed to represent the planet won't render, my guess is that I am putting it too far away from the XR Origin.

Lessons Learned
- I learned about how complex it can actually be to create an engaging story that moves forward as the player interacts during gameplay. 
