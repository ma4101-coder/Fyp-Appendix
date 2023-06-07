# Fyp-Appendix
To execute the code from Appendix A to Appendix G using Google Colab and Roboflow, follow these steps:

Open Google Colab: Go to https://colab.research.google.com/ and create a new Python 3 notebook.

Data Collection (Appendix A):

Copy and paste the code from Appendix A into a code cell in the Colab notebook.
Run the code cell to clone the YOLOv5 repository, install dependencies, download the dataset, and set up the required configurations.
Error Handling 1 - Frames overlapping (Appendix B):

Copy and paste the code from Appendix B into a new code cell.
Replace 'path/to/yolov5s.pt' with the actual path to your YOLOv5 weights file.
Replace 'path/to/image.jpg' with the path to the image file you want to detect fire in.
Run the code cell to load the YOLOv5 model, detect fire in the image, and display the results with bounding boxes and labels.
Frames overlapping 2 (Appendix C):

Copy and paste the code from Appendix C into a new code cell.
Replace 'path/to/yolov5s.pt' with the actual path to your YOLOv5 weights file.
Replace 'path/to/frame1.jpg' and 'path/to/frame2.jpg' with the paths to the first and second frame images.
Run the code cell to load the YOLOv5 model, perform frame differencing, and detect fire in the new frame.
Frames overlapping 3 (Appendix D):

Copy and paste the code from Appendix D into a new code cell.
Replace 'path/to/yolov5s.pt' with the actual path to your YOLOv5 weights file.
Replace 'path/to/frame1.jpg' and 'path/to/frame2.jpg' with the paths to the first and second frame images.
Run the code cell to load the YOLOv5 model, perform frame differencing, and detect changes between the frames.
Note: For Appendices B, C, and D, make sure you have the YOLOv5 weights file (yolov5s.pt) and the frame images (image.jpg, frame1.jpg, frame2.jpg) available in the specified paths.

These steps will allow you to execute the code from Appendix A to Appendix D using Google Colab and Roboflow. You can follow a similar approach for executing the code from Appendices E, F, and G.