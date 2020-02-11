## Hazus Questions and Error Messages: A Problem-Solving Forum     
A place for people trying to learn FEMA's HAZUS-MH program. Fork the repository and submit a pull request if you have a question or answer to add. Simple as dat.
<img src="https://drive.google.com/uc?export=view&id=1qRz4ZuR_3h4upaNWByW2fnBNLLv15GOY">     

HAZUS Tsunami
---
<img src="https://drive.google.com/uc?export=view&id=1hsN_W2--RS2fuQWuV2Ll1AjtF5XPly_5">

After getting this message, when trying to create a region in the Tsunami model for Puerto Rico, I figured out that I had never enabled the "tsunami" modeler when I first downloaded Hazus MH 4.2. So in this case it wasn't a problem of not being able to aggregate the region, but that I couldn't model any tsunamis because I excluded the tsunami option entirely during the initial installation process. 

To solve this I went to Start menu > programs > Hazus 4.2 , right clicked on the program, selected "Change" and then added the tsunami modeler.

