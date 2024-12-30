# Object Detection on Images Using Pretrained YOLOv8 Model YOLOv8


This project provides a user-friendly GUI application for performing object detection on images using the YOLOv8 model. It allows users to upload images, detect objects, and save the annotated results. The application supports multiple YOLOv8 model sizes, making it flexible for different use cases.

# Features
Multiple YOLOv8 Models: Choose from different YOLOv8 model sizes (yolov8n.pt, yolov8s.pt, yolov8m.pt, yolov8l.pt, yolov8x.pt) for varying levels of accuracy and speed.

Image Upload: Upload images in common formats (JPG, JPEG, PNG) for object detection.

Real-Time Object Detection: Detect objects in the uploaded image and display the results with bounding boxes and labels.

Object Counting: Count the number of detected objects and display the count on the annotated image.

Save Results: Save the annotated image to your local machine.

User-Friendly GUI: Built with tkinter, the interface is intuitive and easy to use.

# Use Cases
Object Detection: Identify and locate objects in images.

Image Annotation: Automatically annotate images with bounding boxes and labels.

Object Counting: Count the number of specific objects in an image (e.g., people, cars, animals).

Education and Research: Learn and experiment with YOLOv8 and object detection techniques.

# Getting Started
## Prerequisites
Before running the project, ensure you have the following installed:

Python 3.7 or higher

torch (PyTorch)

ultralytics (YOLOv8)

opencv-python (OpenCV)

Pillow (PIL)

tkinter (usually comes pre-installed with Python)

# Installation
Clone the repository:

bash
Copy
git clone https://github.com/alirzx/Object-Detection-on-image-using-pretrained-YOLOv8-Model.git
cd Object-Detection-on-image-using-pretrained-YOLOv8-Model
Install the required Python packages:

bash
Copy
pip install torch ultralytics opencv-python Pillow
Usage
Run the application:

bash
Copy
python object_detection_gui.py
Upload an Image:

Click the "Upload Image" button to select an image from your local machine.

Select a Model:

Use the dropdown menu to choose a YOLOv8 model (default is yolov8n.pt).

Detect Objects:

Click the "Detect Objects" button to perform object detection on the uploaded image.

The annotated image with bounding boxes, labels, and object count will be displayed.

Save the Result:

Click the "Save Result" button to save the annotated image to your local machine.


Upload Image
Upload an image for object detection.

Detect Objects
Detect objects and view the annotated image.

Save Result
Save the annotated image to your local machine.

Supported Models
The application supports the following YOLOv8 models:

Model	Description
yolov8n.pt	Nano (fastest, lowest accuracy)
yolov8s.pt	Small
yolov8m.pt	Medium
yolov8l.pt	Large
yolov8x.pt	Extra Large (slowest, highest accuracy)

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Push your branch and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Ultralytics for the YOLOv8 model.

OpenCV for image processing.

Tkinter for the GUI.

Contact
For questions or feedback, feel free to reach out:

Name: Alira hshmi

Email: alirahshmi@gmail.com

GitHub: alirzx

Enjoy using the Object Detection on Images Using Pretrained YOLOv8 Model application! 🚀

This README is designed to be professional, user-friendly, and informative, making it easy for users and contributors to understand and use your project. Let me know if you’d like to add or modify anything! 😊

