# Coding1

Coding One Project Description 

This project is called ‘Rocks in a Washing Machine’ and has nauseating animations to accompany it. It uses variation in rotational speed and depth of field to transition between fast and slow motion, creating a disorientating experience if it were viewed through a VR headset. 

The washing machine ‘world’ is created using rotating box and plane geometry with contrasting smooth and angular textures. The world also has three off centre rotating rings, which dip in and out of view as the box rotates creating a lack of uniformity.  One of the rings frames the viewing window and gives the rings something to disappear behind as they rotate towards the foreground.

The rocks are made from two deformed spheres joined by the same axis but with slightly out of sync rotational speeds on the y axis to create a fluttering effect. Four of the rocks have one segment of the rock moving along the z axis, it travels from the background to the foreground so fast it appears like multiple rocks shooting forward. These four rock formations also follow the mouse movement with two moving away from the mouse’s x,y coordinates in a negative direction and the other two in a positive direction. The fifth rock rotates and flutters in the centre of the scene.

There are three lights in the scene. Two directional lights, one aimed at the right hand side of the world to light half the back wall and left side of the rocks. The second directional light shines down from above to highlight the top of the rocks. Lastly an ambient light is used to illuminate the scene in general and MeshLambertMaterials are used to capture the light. 

The audio used for the project is a combination of oscillators and a crumbing rock audio. The four oscillators use sine waves, and Clock.playhead is used to trigger and stop the oscillators and crumbling audio at different times to create an ever-changing 40 second sound scape. 

Clock.playhead is used again to time the rotational speed of the world ‘box’ to correspond to the speed of the audio which speeds up and slows down throughout the sound scape. It is hard to recognise the crumbling rock sound while the oscillators are playing but as they dip off towards the end of the 40 seconds the rock sounds come through.

To improve the project I would add more rocks in varying size, rotation and movement patterns as well as timing the release of the rocks to make it a more dynamic experience.
 
