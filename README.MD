# Object Detection
This project detects objcts including car detection, person detection, bicycle detection by using Intel(R) OpenVINO toolkits.
**Input:** the video with objects.

**Output:** the video of objects detected surronding by bounding boxes.

**Setup and installation:**

1. Openvino toolkit setup in Ubuntu 18.04
2. ffmpeg setup
3. Create virtual environment and activate it
4. run the command: python3 app.py --model --i
The output images were sent to ffmpeg server for streaming.

**Use casses:** can be traffic monitoring, bicycle tracking, bottle tracking.
