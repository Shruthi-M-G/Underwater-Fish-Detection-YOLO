Underwater Fish Detection using Custom YOLOv8

Project Overview
  This project detects fish in underwater marine videos using a custom-trained YOLOv8 model.
  The model is trained on enhanced frames extracted from a known underwater video.

Workflow
1. Extract frames from underwater video
2. Enhance frames (low light, blur correction)
3. Annotate and prepare dataset
4. Train custom YOLOv8 model
5. Detect fish in the input video

Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- PyTorch

Dataset
- Frames extracted from underwater marine video
- Enhanced using image preprocessing techniques
- Custom annotations in YOLO format

Setup Instructions
```bash
git clone https://github.com/yourusername/Underwater-Fish-Detection-YOLO.git
cd Underwater-Fish-Detection-YOLO
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
