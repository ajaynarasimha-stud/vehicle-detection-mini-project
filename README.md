# Vehicle Detection Using YOLOv8

## Overview
This project explores object detection for vehicle images using a pretrained YOLOv8 model. The notebook demonstrates model inference and visualization of detections.

## Objectives
- Experiment with a pretrained object-detection model.
- Run inference on input images.
- Inspect detection outputs, including bounding boxes and class labels.
- Explore a basic computer-vision workflow.

## Technologies
- Python
- YOLOv8
- Ultralytics
- Jupyter Notebook / Google Colab
- Roboflow, if used in the notebook

## Repository Contents
- `ObjectDetectionMini.ipynb` — the project notebook.
- `image_2026-10-09_153307398.png` — an image included with the project. Replace or supplement it with a clearly labelled detection output if appropriate.

## Getting Started

### Option 1: Google Colab
1. Open the notebook from the repository.
2. Choose **Open in Colab** if available, or download the notebook and upload it to Google Colab.
3. Run the notebook cells in order.
4. Provide the input image(s) expected by the notebook.

### Option 2: Run locally
Create and activate a virtual environment.

```bash
python -m venv .venv
```

**Windows (PowerShell):**
```powershell
.venv\Scripts\Activate.ps1
```

**macOS/Linux:**
```bash
source .venv/bin/activate
```

Install the dependencies required by the notebook, then launch Jupyter:
```bash
pip install jupyter
jupyter notebook
```

Open `ObjectDetectionMini.ipynb` and run the cells in order. Check the notebook imports to identify the exact dependencies; setup can vary by Python version and GPU availability.

## Method
1. Load the required libraries and pretrained YOLOv8 model.
2. Supply an input image.
3. Run object-detection inference.
4. Visualize detections using the model output.

The detected classes and results depend on the model weights and input image used by the notebook.

## Results
Add a screenshot of the actual notebook output showing detections and bounding boxes. Only describe an image as a project result if it was produced by this project.

## Limitations
This project uses a pretrained model and is a basic exploration of object detection. Do not describe it as a model trained from scratch unless training or fine-tuning was actually performed.

## Author
Ajay Narasimha Vijay
