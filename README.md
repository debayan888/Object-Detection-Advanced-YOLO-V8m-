# Object-Detection-Advanced-YOLO-V8m-

A real-time object detection system built with YOLOv8 and OpenCV, trained to detect common classroom and daily-use objects like bottles, chairs, books, laptops, cups, and more.

| Field | Details |
|-------|---------|
| **Name** | Debayan Mitra |
| **Registration No.** | 25BCE10801 |
| **Branch** | B.Tech – Computer Science (SCOPE) |
| **Semester** | Second Semester |
| **Course Code** | CSA2001 |
| **Course Title** | Fundamentals of AI & ML |
| **Faculty** | Rakesh Srivastava |


## What it does
- Detects objects in real-time via webcam
- Trained on a custom YOLO-formatted dataset
- Supports both CPU and CUDA GPU inference

## Files
- `train.py` — fine-tune the model on the dataset
- `detect.py` — run real-time webcam detection
- `dataset.yaml` — dataset config with class names

## Trained Model
The trained `best.pt` model is available in the folders uploaded. 
Download and place it at `runs/detect/train/weights/best.pt` before running `detect.py`.

## Requirements
```
pip install ultralytics opencv-python torch torchvision
# or for CUDA gpu version
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
```

## Usage
```python
# Real-time detection
python detect.py

# Training
python train.py
```

---
Made with Dataset from Kaggle | Dataset from Kaggle
