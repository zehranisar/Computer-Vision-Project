# Computer Vision Project

A complete collection of four Computer Vision coursework assignments covering transfer learning, CNNs, data augmentation, object detection, and image transformation.

## Student Information

- **Student:** Zehra Nisar
- **Program:** BS Computer Science
- **Course:** Computer Vision
- **Repository:** Computer-Vision-Project

## Project Overview

This repository contains four Computer Vision assignments. Each assignment is organized separately with its own notebook, documentation, and result files.

| Assignment | Topic | Main Concepts |
|---|---|---|
| **Assignment 1** | VGG16 vs MobileNetV2 — Transfer Learning | Transfer Learning, CNNs, Image Classification, Model Comparison |
| **Assignment 2** | CNN with Data Augmentation | CNN, Augmentation, Scaling, Rotation, Translation |
| **Assignment 3** | YOLOv7 Object Detection | Object Detection, YOLOv7, PyTorch, Bounding Boxes |
| **Assignment 4** | CNN Data Transformation | Scaling, Rotation, Translation, CNN Preprocessing |

## Repository Structure

```text
Computer-Vision-Project/
├── Assignment-1/
│   ├── Assignment-1.ipynb
│   ├── README.md
│   └── results/
│       ├── training_curves.png
│       └── confusion_matrices.png
├── Assignment-2/
│   ├── Assignment-2.ipynb
│   ├── README.md
│   └── results/
│       ├── baseline_images.png
│       ├── augmented_samples.png
│       └── accuracy_loss_comparison.png
├── Assignment-3/
│   ├── Assignment-3.ipynb
│   ├── README.md
│   └── results/
│       ├── detection_result.png
│       └── performance_summary.png
├── Assignment-4/
│   ├── Assignment-4.ipynb
│   ├── README.md
│   └── results/
│       ├── transformed_samples.png
│       └── comparison_plots.png
└── README.md
```

## Assignment Details

### Assignment 1 — VGG16 vs MobileNetV2

This assignment focuses on transfer learning for image classification using two ImageNet-pretrained CNN architectures: **VGG16** and **MobileNetV2**.

The implementation covers image preprocessing, model configuration, training, evaluation, confusion matrices, training curves, and model comparison.

The available dataset used for the implementation is a small **Potato Leaf** dataset with two classes:

- Healthy
- Fungi

**Key concepts:** Transfer Learning, VGG16, MobileNetV2, Image Preprocessing, Binary Classification, Confusion Matrix, Training Curves, Model Comparison.

### Assignment 2 — CNN with Data Augmentation

This assignment demonstrates how image augmentation can increase training-data diversity for a CNN.

The implementation uses selected CIFAR-10 images and applies transformations including scaling/zoom, rotation, width shift, and height shift. The results are visualized using sample images and accuracy/loss comparison plots.

**Key concepts:** CNN, Data Augmentation, Scaling, Rotation, Translation, Training Curves, Accuracy and Loss.

### Assignment 3 — YOLOv7 Object Detection

This assignment focuses on object detection using **YOLOv7** with a PyTorch-based workflow.

The assignment demonstrates the YOLO object-detection workflow and includes detection visualization and a performance-summary result.

**Key concepts:** Object Detection, YOLOv7, PyTorch, Bounding Boxes, Detection Workflow.

### Assignment 4 — CNN Data Transformation

This assignment demonstrates common image transformations used in Computer Vision and CNN preprocessing.

The main transformations are:

- Scaling
- Rotation
- Translation

The transformed samples and comparison plots are included in the `results` folder.

**Key concepts:** Image Transformation, Scaling, Rotation, Translation, CNN Preprocessing, Visual Comparison.

## Technologies Used

- Python
- Jupyter Notebook
- TensorFlow / Keras
- PyTorch
- YOLOv7
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow

## How to Use

Clone the repository:

```bash
git clone https://github.com/zehranisar/Computer-Vision-Project.git
cd Computer-Vision-Project
```

Open the required assignment folder and launch its Jupyter Notebook using Jupyter Notebook, JupyterLab, or VS Code.

Install the dependencies required by the individual notebook and run its cells in order.

## Results

Each assignment keeps its results separately:

- **Assignment 1:** Training curves and confusion matrices
- **Assignment 2:** Baseline images, augmented samples, and accuracy/loss comparison
- **Assignment 3:** Object detection result and performance summary
- **Assignment 4:** Transformed samples and comparison plots

## Learning Outcomes

This project demonstrates practical understanding of:

- CNN-based image processing
- Transfer learning
- Image classification
- Data augmentation
- Image transformation
- Object detection
- Model evaluation and visualization
- Deep learning frameworks
- Computer Vision experimentation

## Notes

- Each assignment is maintained in its own folder.
- Assignment-specific documentation is available inside each assignment folder.
- Dataset files are not included in the repository where they are not required for submission.
- Result images are stored in the corresponding `results` directories.
- The individual notebooks contain the implementation workflow for each assignment.

## Author

**Zehra Nisar**  
BS Computer Science

## Repository

[Computer-Vision-Project](https://github.com/zehranisar/Computer-Vision-Project)
