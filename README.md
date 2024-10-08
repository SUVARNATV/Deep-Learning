#VEHICLE DETECTION AND COUNTING


The project involves vehicle detection and tracking using the YOLOv8 object detection model, with implementation facilitated through OpenCV, Ultralytics, and CVzone libraries. YOLOv8, a state-of-the-art deep learning model, is employed to accurately detect various vehicles such as cars, buses, and trucks in a traffic stream. The model is trained on the COCO dataset, which contains predefined classes listed in the coco.txt file. Once a vehicle is detected, the model draws bounding rectangles around each vehicle using the coordinates provided by YOLOv8.

The system is capable of distinguishing between vehicles moving in different directions—upwards and downwards—within the frame. By tracking the movement of these vehicles, the system not only identifies the type of vehicle but also counts the number of each type passing through the designated area. The combination of these technologies ensures real-time processing and accurate vehicle counting, which can be useful for traffic management and analysis. Additionally, the modular design of the code allows for flexibility and scalability in different traffic scenarios.
