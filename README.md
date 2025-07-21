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

vehicle-detection/
├── videos/ # Sample input videos
├── output/ # Processed video outputs
├── haarcascades/ # Detection model files (if using Haar)
├── vehicle_counter.py # Main Python script
├── requirements.txt # Python dependencies
└── README.md # Project documentation
