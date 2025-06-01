# RealTime-Object-Detection-Tracking

A real-time object detection and tracking system using YOLOv3 and Flask.

## 📌 Features
- Real-time object detection using YOLOv3
- Object tracking with adaptive logic
- Web-based interface using Flask
- Supports both live webcam feed and uploaded video
- Tracks multiple object types: vehicles, pedestrians, traffic signals, etc.

## 🗂️ Project Structure
```
├── app.py                 # Main Flask app
├── vechile.py             # Object detection and tracking logic
├── coco.names             # COCO class labels
├── yolov3.cfg             # YOLOv3 configuration
├── yolov3.weights         # YOLOv3 pre-trained weights (not uploaded due to size)
├── static/                # Static assets (images, CSS if needed)
├── templates/             # HTML templates for Flask (e.g., index.html)
├── videos/                # (Optional) Folder for video files used
├── README.md              # Project description
└── .gitignore             # Files to ignore in Git
```

## ▶️ How to Run
1. Install dependencies:
   ```
   pip install flask opencv-python
   ```

2. Make sure `yolov3.weights` is present in the project folder (download from [KAGGLE website](https://www.kaggle.com/datasets/shivam316/yolov3-weights?resource=download)).

3. Run the app:
   ```
   python app.py
   ```

4. Open your browser and go to `http://127.0.0.1:5000`

## 📽️ Sample Use Cases
- Real-time traffic monitoring
- Pedestrian tracking for autonomous vehicles
- Object detection in surveillance videos

## 📄 License
This project is licensed under the MIT License.

---
Feel free to fork and contribute! 🔧
