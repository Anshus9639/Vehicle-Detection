# General Vehicle Detection using YOLOv8

> **Status:** 🚧 Work in Progress 🚧
>
> This project is a functional YOLOv8 model trained to detect and classify multiple classes of vehicles. The model's performance is currently being analyzed and improved.

## Overview
This project is a deep learning model capable of detecting several classes of vehicles in various road conditions. The model was trained on a **general-purpose dataset of over 4,000 images** using the YOLOv8 architecture, making it adaptable to different traffic environments.

## Features
- Detects multiple vehicle classes: **[List your new classes here, e.g., car, bus, truck, small-truck, etc.]**
- Built with PyTorch and the `ultralytics` YOLOv8 library.
- Trained on a diverse dataset of over 4,000 images for robustness.
- Achieved a mean Average Precision (mAP) of [**find this value in your training results**] on the validation set.

## Current Performance & Known Issues
*(This section is likely still true, but you can update it based on the new model's performance.)*

This model performs well in clear, daylight conditions but has some known limitations:
* It sometimes fails to detect vehicles that are very **small or distant**.
* Detection accuracy **decreases in low-light** or night-time scenes.
* **Partially occluded vehicles** are often missed.

## Future Improvements
*(This plan is still excellent and shows you know how to move forward.)*

1.  **Targeted Data Curation:** Add more images focusing on the specific failure cases noted above.
2.  **Hyperparameter Tuning:** Experiment with different confidence thresholds.
3.  **Model Scaling:** Train a larger version of the YOLOv8 model.

## Tech Stack
- Python
- YOLOv8 (Ultralytics)
- PyTorch
- OpenCV
- Roboflow
- Google Colab

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.

3. Run inference using the `best.pt` model.
