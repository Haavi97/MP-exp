# MediaPipe experimentation
> Experimenting with MediaPipe using Rui Santos

# Installation
Download this [model](https://storage.googleapis.com/mediapipe-models/gesture_recognizer/gesture_recognizer/float16/1/gesture_recognizer.task).

Then create a virtual environment: `python -m venv myenv`

And install the needed libraries: `pip install -r requirements.txt`

# Running
`python main.py --cameraId 0 --model gesture_recognizer.task --numHands 2`