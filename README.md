# Intrusion Detection System with Face Recognition and Email Alert

A Python-based, real-time Intrusion Detection System (IDS) that combines motion detection, face recognition, and automatic email alerts — all integrated within a Jupyter Notebook. This system uses a webcam to monitor activity, identify authorized users, and send alerts when unknown faces are detected.

---

## Features

-  **Motion Detection** using OpenCV's background subtraction
-  **Face Detection** via DNN (Caffe model: `res10_300x300_ssd_iter_140000.caffemodel`)
-  **Face Recognition** using OpenCV’s LBPH recognizer
-  **Dataset Creation** for training with new faces
-  **Email Alerts** with intruder snapshot
-  **Visualization** using live frame display in Jupyter Notebook
-  **Easy Training** over structured datasets

---

## Folder Structure

```text
├── Intrusion-Detection.ipynb 
├── dataset/ 
│   ├── 1/
│   │   ├── 1.jpg
│   │   └── ...
│   └── 2/
│       ├── 1.jpg
│       └── ...
├── deploy.prototxt                        
├── res10_300x300_ssd_iter_140000.caffemodel  
├── trainer.yml                           
└── README.md

---
```
## Requirements
Install the required dependencies:

bash
```
pip install opencv-python opencv-contrib-python numpy matplotlib
```
