# Hazus_Questions_and_Error_Messages
A place for questions and error messages for people trying to learn FEMA's HAZUS-MH 

HAZUS Tsunami
---
<img src="https://drive.google.com/uc?export=view&id=18TWsVwmr1fYk6kUmgQ0871tP_CIbu5vU">

After getting this message, when trying to create a region in the Tsunami model for Puerto Rico, I figured out that I had never enabled the "tsunami" modeler when I first downloaded Hazus MH 4.2. So in this case it wasn't a problem of not being able to aggregate the region, but that I couldn't model any tsunamis because I excluded the tsunami option entirely during the initial installation process. 

To solve this I went to Start menu > programs > Hazus 4.2 , right clicked on the program, selected "Change" and then added the tsunami modeler.

