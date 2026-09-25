# Assignment 3 — Object Detection with YOLOv7, YOLOv8, and YOLOv9

**Student:** Zehra Nisar  
**Course:** Computer Vision CA1-363  
**Assignment:** 3 — Object Detection

## Objective

The objective of this assignment is to run pretrained **YOLOv7, YOLOv8, and YOLOv9** on the same real-world images and compare their detection quality, bounding-box localization, and inference speed.

## Models Used

- **YOLOv7** — official YOLOv7 repository and detection pipeline
- **YOLOv8n** — Ultralytics pretrained model
- **YOLOv9c** — Ultralytics pretrained model

## Dataset / Input

The notebook is designed for **10 real-world images** (or a short video). It creates an `input_images/` folder and also contains a small sample-image fallback for testing the pipeline. For the final submission, the sample URLs should be replaced with the student's 10 selected images.

## Methodology

1. Install Ultralytics for YOLOv8 and YOLOv9.
2. Clone the official YOLOv7 repository and install its requirements.
3. Prepare the input images.
4. Run YOLOv8 detection and save annotated images.
5. Run YOLOv9 detection and save annotated images.
6. Run YOLOv7 detection and save annotated images.
7. Compare the original image with the outputs from all three models.
8. Measure total and average inference time per image.
9. Interpret detection quality, bounding-box localization, and speed.

## Outputs

The notebook generates the following outputs when it is executed:

```text
outputs/
├── yolov7/
├── yolov8/
└── yolov9/
```

It also generates:

- `detection_comparison.png` — side-by-side visual comparison
- Speed/performance summary — total time and average time per image
- Written comparison and interpretation in the final notebook section

## Important Note

The supplied assignment package did not contain generated detection images or benchmark screenshots. Therefore, no result images or numerical benchmark values have been fabricated. After running the notebook, place the final `detection_comparison.png` inside the `results/` folder before committing the assignment to GitHub.

## Conclusion

This assignment provides a practical comparison of three YOLO versions using the same input images. The final comparison considers both visual detection quality and inference speed, allowing the models to be evaluated using the outputs produced by the student's run.
