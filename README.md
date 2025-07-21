# vehicle-detection-counter
# 🚗 vehicle-detection-counter

**Vehicle Detection and Category-Wise Counting using OpenCV**

This project focuses on detecting and categorizing vehicles in real-time from video streams or camera feeds using OpenCV and Python. The system identifies vehicles such as cars, bikes, trucks, and buses, and keeps a live count of each category. It's designed for smart traffic management systems and can be integrated with traffic monitoring tools for better insights and control.

---

## 🔧 Features

- Real-time vehicle detection using Haar Cascades / pre-trained object detection models  
- Category-wise vehicle classification (Car, Bike, Bus, Truck)  
- Frame-by-frame object tracking for accurate counting  
- Dynamic region of interest (ROI) for optimized detection zones  
- Simple UI to visualize live counts and bounding boxes  
- Video file or webcam input support  

---

## 🛠 Technologies Used

- Python  
- OpenCV  
- NumPy  
- Pre-trained Haar Cascade / YOLO / SSD (based on your choice)  

---

## 📌 Applications

- Traffic flow analysis  
- Smart city surveillance systems  
- Highway and toll booth monitoring  
- Urban traffic management  

---

## 📁 Folder Structure

category-wise-vehicle-detection/
├── models/                          
│   ├── yolov3.cfg                   # YOLO configuration file
│   └── coco.names                   # COCO dataset class labels
│
├── static/
│   ├── style.css                    # CSS styling for web UI
│
├── templates/
│   └── index.html                   # HTML frontend template
│
├── videos/
│   └── video.mp4                    # Sample input video for testing
│
├── scripts/
│   ├── vehicle_detection.py         # Main vehicle detection script
│   ├── import_cv22.py              # Helper import or script module
│   └── your_detection_script.pyc    # Compiled python file (can be ignored or deleted)
│
├── app.py                           # Flask app if running as a web service
├── code.py                          # Possibly testing or demo code (rename meaningfully)
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies list
└── .gitignore                       # Git ignore file

