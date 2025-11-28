# YOLOv11 Visual Search Application

A fast and intelligent computer vision search system built using YOLOv11 and Streamlit.
The application performs object detection, generates metadata, and enables smart searching across image collections based on classes and count thresholds.

## Features

⚡ YOLOv11 Object Detection

🔍 Smart Search with AND / OR logic

🖼️ Bounding Box Visualization

📦 Metadata Storage for Fast Reload

🎯 Class & Count-Based Filtering

🧹 Clean Streamlit Interface

```
Project Structure
Yolo_11/
├── app.py
├── configs/
│   └── default.yaml
├── src/
│   ├── inference.py
│   ├── config.py
│   └── utils.py
├── data/
│   ├── raw/
│   └── processed/
└── test/
```
## Application Snapshots

### Main Screen
<img width="1786" height="637" alt="image" src="https://github.com/user-attachments/assets/5e34a57b-2663-4698-9ede-43b0d5079bb3" />

### Processing Images
<img width="1825" height="734" alt="image" src="https://github.com/user-attachments/assets/bd6ac76e-ae50-4355-a596-795a7d0482e7" />

### Search Interface
<img width="1813" height="611" alt="image" src="https://github.com/user-attachments/assets/97feb2fc-175d-49b1-963d-5cbf11fb7bff" />

### Search Results
<img width="1810" height="613" alt="image" src="https://github.com/user-attachments/assets/5ecd7e43-8ef0-4f5f-be6f-b27260f5557f" />
<img width="1780" height="816" alt="image" src="https://github.com/user-attachments/assets/3b306145-d8f5-4261-9a1c-94d23505ed39" />
<img width="1868" height="903" alt="image" src="https://github.com/user-attachments/assets/fc50fd58-a75c-4505-8e45-07532031196a" />

## How It Works
1. Object Detection :-
   Processes images and runs YOLOv11 inference
   Extracts classes, confidence scores, and bounding boxes
   Counts objects per class

2. Metadata Creation :-
   Saves results in data/processed/.../metadata.json
   Enables very fast future searches

3. Smart Search System
   
   Supports:
   Class-based search,
   Count thresholds (1, 2, 5, or any),
   AND / OR logic.

5. Visual Output :-
  
3-column image grid,
Class labels + confidence,
Color-coded bounding boxes,
List of detected objects,

## Technologies Used

YOLOv11 (Ultralytics)

Streamlit

OpenCV

Pillow

PyYAML

## Dataset
The dataset used in this project is not included in the repository due to size limitations.  
You can access all raw images and processed metadata from the link below:

👉 **[Click Here to View/Download the Dataset](https://drive.google.com/drive/folders/1Q2x7sDBjj1cfqVx9DakbuRDo0TaDATTR?usp=drive_link)**

This folder contains:

- Raw Images (used for detection)  
- Processed Metadata (JSON files generated after YOLOv11 inference)  
- Sample Outputs  

Sample Outputs
## License

All Rights Reserved
Unauthorized copying, modification, or redistribution of this project is prohibited.
