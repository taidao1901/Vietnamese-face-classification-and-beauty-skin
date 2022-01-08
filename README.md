# Vietnamese-face-classification-and-beauty-skin
## Overview
- In this project, we implement classification and beauty skin in Vietnamese face.
- Vietnamese face dataset: https://drive.google.com/drive/folders/1axQd3eCvLjuApq5ldGgkQZuvqnqJ8mA9?usp=sharing
- Foreigner face dataset: https://wywu.github.io/projects/LAB/WFLW.html
- Using [OpenFace](https://cmusatyalab.github.io/openface/) pretrained model to extract feature embedding vector.
- Using SVM, KNN, Custom simple neural network with 2 hidden layers to classification
- Using sobel edge detection, color threshold in HSV space to detect face skin. After that, smoothing face skin.
- Simple vitual makeup.
## Example.
![Example](https://github.com/taidao1901/Vietnamese-face-recognition-and-beauty-skin-/blob/main/example.png?raw=true)
