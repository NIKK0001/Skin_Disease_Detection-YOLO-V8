

---

# Skin Disease Detection using YOLOv8

![](https://github.com/NIKK0001/Skin_Disease_Detection-YOLO-V8/blob/main/yoloultra.png)

## Description
This project implements a YOLOv8 model to detect and classify various skin diseases from images. The model is trained on a dataset of labeled images and can identify different types of skin conditions in real-time.

## Dataset
The dataset used is from [Roboflow](https://app.roboflow.com/data-science-tnitc/skin-diseases-i30ay-cpycv/visualize/1) and includes images of different skin diseases with annotations.

## How to Use
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Skin-Disease-Detection-YOLOv8.git
    cd Skin-Disease-Detection-YOLOv8
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Train the model:**
    ```bash
    python train.py --data data/skin_disease.yaml --img 640 --batch 16 --epochs 100 --weights yolov8s.pt
    ```

4. **Run detection on new images:**
    ```bash
    python detect.py --weights runs/train/exp/weights/best.pt --source path/to/your/image_or_video
    ```

## Results
The model outputs detection results with bounding boxes and class labels, helping in the identification of skin diseases.

## License
This project is licensed under the MIT License.

---
