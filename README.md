# 🧳 Suitcase Detection and Tracking using YOLOv11
This project implements **real-time object detection and tracking** to count suitcases on a conveyor belt using **YOLOv11** and **DeepSORT tracking**. The system ensures accurate **baggage tracking**, helping improve **airport security, logistics automation, and warehouse management**.  

## **How It Works**  
🔹 **Object Detection:** YOLOv11 detects suitcases in video frames  
🔹 **Tracking:** DeepSORT assigns unique IDs to track movement  
🔹 **Line Crossing Detection:** Counts suitcases crossing a predefined line  
🔹 **Confidence Filtering:** Filters out detections below **0.8 confidence**  
🔹 **Output:** Annotated video with **bounding boxes, object IDs, and real-time counts**  

## **Why It Matters**  
✅ **Optimizes airport baggage handling** and reduces human errors  
✅ **Enhances security screenings** by tracking luggage movement  
✅ **Improves logistics automation** in warehouses and transport hubs  
✅ **Reduces lost luggage incidents** by providing real-time tracking  

## **Technologies Used**  
🔹 **YOLOv11 (Ultralytics)** – Object detection  
🔹 **DeepSORT** – Multi-object tracking  
🔹 **Python & OpenCV** – Video processing  
🔹 **Torch** – Deep learning framework  
🔹 **CV2 (OpenCV)** – Image manipulation  
