# Real-Time Face Detection with OpenCV
This project demonstrates real-time face detection using a pre-trained deep learning model and OpenCV in Python. It detects human faces from a webcam or video feed and highlights them with bounding boxes.

# Features
- Real-time face detection using a deep learning-based detector
- Accurate and fast detection even with multiple faces
- Uses MobileNet-based SSD model (trained on face data)

# Files in This Repository
File                             - Description 

`CV.ipynb`                       - Jupyter Notebook containing the full face detection code |
`MobileNetSSD_deploy.prototxt`   - Network configuration file |
`MobileNetSSD_deploy.caffemodel` - Pre-trained model weights for face detection |

# How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. Install the required Python package
   pip install opencv-python
3. Launch Jupyter Notebook
   jupyter notebook CV.ipynb
4. Run all cells in the notebook
   It will open your webcam.
   Faces will be detected and highlighted with bounding boxes.
   
# Output:
https://github.com/saniyadsilva/cvProject/blob/main/image_2025-04-24_100757271.png
   
# Model Used
Name: MobileNet SSD (Single Shot Detector)
Trained on: Face detection dataset
Framework: Caffe (loaded via OpenCV’s cv2.dnn module)

# Author
Saniya Dsilva
https://github.com/saniyadsilva

# License
This project is open-source and available for learning and experimentation.

























