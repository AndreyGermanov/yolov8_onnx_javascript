# YOLOv8 inference using Javascript

This is a web interface to [YOLOv8 object detection neural network](https://ultralytics.com/yolov8)
implemented that allows to run object detection right in a web browser without any backend using [ONNX runtime](https://onnxruntime.ai/).

# Install

Clone this repository: `git clone git@github.com:AndreyGermanov/yolov8_onnx_javascript.git`

# Run

You need to run `index.html` using any local webserver, for example internal webserver of Visual Studio Code. Ensure that 
the model file `yolov8m.onnx` exists in the same folder with `index.html`.

Using the interface in `index.html` you can upload the image to the object detector and see bounding boxes of all  objects detected on it.
