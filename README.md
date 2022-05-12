# movement_clarification
using python MediaPipe and others library, this program able to classify movement

### Requirements
*cords.csv for the dataset coordinates

### Features
* Uses OpenCV, mediapipe, CSV, pickle and pandas.
* Able to customizes and detect movement with high accuracy.
* Able to convert the video stream to a short 2 second video.
* Able to save the image of the object capture and store them.


### Customizable
* confThreshold = 0.65 "The object confidence level."
* cv2.FONT_HERSHEY_PLAIN "the font type can be change to others type to be more suitable"
* color=(160, 32, 240) "the box and fond color"
* if he == "jumping": customize what kind of motion to be capture
* count == 11 edit the cooldown timer

### Example
* One of the movement that can detected is jumping 

https://user-images.githubusercontent.com/80488842/168018649-5808498d-e08b-4da3-9447-7b3c8baeedb0.mp4

