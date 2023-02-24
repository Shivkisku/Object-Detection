# Object-Detection

This is a Python code that uses the ImageAI library to perform object detection on an input image. The code imports the necessary modules, sets the execution path, and loads a pre-trained RetinaNet model (resnet50_coco_best_v2.1.0.h5) for object detection.

Next, the detectObjectsFromImage method is called on the loaded model to detect objects in the input image (image.jpg). The detected objects are saved in the detections variable.

The objects detected in the input image are then printed along with their percentage probability of occurrence. The minimum_percentage_probability parameter is set to 30, meaning that objects with a probability lower than 30% will not be considered.

Finally, the output image with the detected objects is saved as imagenew.jpg and displayed using the IPython Image modul
