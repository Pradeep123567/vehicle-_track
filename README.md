# vehicle-_track

## 📌 Project Overview

- **Model:** YOLOv8s (from Ultralytics)
- **Objective:** Track and label objects in 4 categories:
  - Person
  - 2-Wheeler (e.g., bicycle, motorcycle)
  - 4-Wheeler (e.g., car)
  - Heavy Vehicle (e.g., truck, bus)
- **Tracking Type:** Centroid-based tracker (no direction counting)
- **Input Video:** dataset traffic scene
- **Output:** Annotated video with object IDs and class labels

---
## Methodology 
Dataset Selection: A traffic video is used as input, containing pedestrians and different vehicle types.

Detection Model: YOLOv8s is applied frame by frame to detect objects with bounding boxes and confidence scores.

Category Grouping: Detected classes are grouped into four categories — Person, 2-Wheeler, 4-Wheeler, Heavy Vehicle.

Tracking: A centroid-based tracker assigns and maintains unique IDs across frames for consistency.

Output Generation: Each frame is annotated with bounding boxes, labels, and IDs, and an output video is produced.

## 🛠️ Tools & Libraries

- Python 3.8+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- Pandas
- Google Colab (recommended for GPU support)
