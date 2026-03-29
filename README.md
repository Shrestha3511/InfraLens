# InfraLens

AI-powered infrastructure defect detection and analysis system.

## What it does
- Classifies infrastructure type (road, bridge, building)
- Detects defects with bounding boxes (crack, pothole, spalling, etc.)
- Applies context-aware filtering to prevent wrong predictions
- Generates structured inspection reports

## Architecture
3-stage pipeline:
1. Scene Classifier
2. Defect Detector (separate model per scene)
3. Context-aware Filter

## Tech Stack
- Python
- PyTorch
- YOLOv8
- OpenCV
- Streamlit

## Status
Under active development.

## Team
Shrestha Mal and team.
