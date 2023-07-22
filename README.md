# Real-time Object Tracking using YOLOv8

This script uses the YOLOv8 object detection model to track objects in real time. The script takes a video file as input and outputs a video file with the tracked objects annotated.

## Dependencies
* Python 3
* OpenCV
* Ultralytics YOLOv8
* Supervision
## Usage

To run the script, simply run the following command:
`python object_tracking.py`

The script will take a few seconds to load the YOLOv8 model and then start tracking objects in the video file. The tracked objects will be annotated with their ID, class, and confidence score.

## Example

The script will take a few seconds to load the YOLOv8 model and then start tracking objects in the video file. The tracked objects will be annotated with their ID, class, and confidence score.

`[ID] [Class] [Confidence]
<br>
1 Person 0.99
<br>
2 Car 0.98
<br>
3 Bicycle 0.95`


The `ID` of the object is a unique identifier that is assigned to the object when it is first detected. The class of the object is the type of object that has been detected. The confidence score is a measure of how confident the model is that the object has been correctly detected.

## License

This script is licensed under the MIT License.

