# vehicle-_track

## 📌 Project Overview

- **Model:** YOLOv8s (from Ultralytics)
- **Objective:** Track and label objects in 4 categories:
  - Person
  - 2-Wheeler (e.g., bicycle, motorcycle)
  - 4-Wheeler (e.g., car)
  - Heavy Vehicle (e.g., truck, bus)
- **Tracking Type:** Centroid-based tracker (no direction counting)
- **Input Video:** Sherbrooke dataset traffic scene
- **Output:** Annotated video with object IDs and class labels

---

## 🛠️ Tools & Libraries

- Python 3.8+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- Pandas
- Google Colab (recommended for GPU support)
