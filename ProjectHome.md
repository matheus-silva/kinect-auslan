# Auslan Recognition Software for Kinect #

The purpose of this project is to provide a set of software modules that will be useful for the development of applications that implement sign language recognition using the Microsoft Kinect. The intended use is for Australian Sign Language (Auslan), however modules may be easily adaptable for other sign languages or visual communication.

We plan to include four different modules that work on top of the OpenNI framework to extract information about a user's hands. This information will be structured in a way that is relevant to the gestures that make up Auslan. The four modules include:
  * position of the hand relative to the user,
  * direction of movement of the hand,
  * orientation of the palm and fingers,
  * and hand shape.
Once this information is obtained about the hand, recognition of gestures can be achieved through comparison of this data to a database of signs that have been classified according to the same criteria. We hope to make this method able to be scaled for a large amount of gestures.

This project was undertaken as part of course work at the Queensland University of Technology, September - October 2012.


---


**Current Progress:**

The work currently implemented is a proof of concept of our idea. Methods to obtain useful data about the position and movement of the hands has been successfully implemented. While this is not exhaustive or highly robust, it provides a good skeleton for further development of both of these. Work on hand shape and orientation still needs to be implemented. Using this information, recognition of a small set of signs has been achieved.

Last updated: 24 October, 2012


---
