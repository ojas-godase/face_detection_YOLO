This notebook leverages the YOLOv5 object detection model in conjunction with the WIDER FACE dataset to accurately detect faces in both images and videos. YOLOv5 is well-known for its real-time object detection capabilities and its speed-performance balance, making it ideal for face detection tasks. The WIDER FACE dataset, a popular large-scale benchmark dataset for face detection, provides a diverse range of faces under various conditions such as scale, pose, and occlusion.

In this notebook, the detected faces are highlighted by drawing green bounding boxes around them. The model processes images and frames from videos efficiently, ensuring that even small and partially occluded faces are recognized with high precision. Additionally, the implementation can be adapted for real-time face detection using webcam input or pre-recorded videos, providing flexibility for various applications such as surveillance, attendance systems, and human-computer interaction.

The notebook includes step-by-step instructions for data preprocessing, model training, inference, and visualization of results, making it a comprehensive guide for users looking to implement face detection systems.

Dateset for face detection: https://www.kaggle.com/datasets/iamprateek/wider-face-a-face-detection-dataset
