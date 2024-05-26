

This repository demonstrates the implementation of YOLOv5 and the export of YOLOv5 models to ONNX and TorchScript formats for mobile devices. It includes examples for four YOLOv5 versions and experimental conversion to CoreML.

### YOLOv5 Versions Included

- YOLOv5-small
- YOLOv5-medium
- YOLOv5-large
- YOLOv5-xlarge

**Note:** This repository primarily focuses on YOLOv5-xlarge. Feel free to experiment by modifying the configuration file.

### Usage

1. **Install the dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

2. **Generate the YOLOv5-xlarge model, convert the model to ONNX, and export the model using TorchScript:**
   ```sh
   python main_file.py
   ```

### References

The main credit goes to the original author of YOLOv5, Glenn Jocher. The original YOLOv5 repository can be found at [ultralytics/yolov5](https://github.com/ultralytics/yolov5).

---
