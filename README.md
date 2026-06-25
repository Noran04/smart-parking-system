## Smart Parking Detection System

An AI-based Smart Parking System that detects parking space occupancy using **YOLOv8** and recommends the nearest available parking space using the **A*** pathfinding algorithm.

---

## Overview

Finding an available parking space in crowded areas is time-consuming and contributes to traffic congestion. This project uses Computer Vision and Pathfinding algorithms to automatically detect available parking spaces and guide users to the nearest vacant spot.

---

## Features

- Detect parking spaces using YOLOv8.
- Classify each parking space as:
  - 🟢 Empty
  - 🔴 Occupied
- Recommend the nearest available parking space.
- Generate the shortest route using the A* algorithm.
- Interactive web interface built with Gradio.
- Deployable on Hugging Face Spaces.

---

## Technologies

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Gradio
- Hugging Face Spaces
- A* Pathfinding Algorithm

---

## Dataset

- **PKLot Dataset**
- Images collected under different weather and lighting conditions.
- Parking spaces labeled as **Empty** and **Occupied**.

---

## Model Performance

| Metric | Score |
|--------|-------|
| Precision | 99.7% |
| Recall | 99.7% |
| mAP@50 | 99.4% |
| mAP@50-95 | 95.1% |

---

## Workflow

1. Load parking image.
2. Detect parking spaces using YOLOv8.
3. Classify parking spaces as occupied or empty.
4. Filter available parking spaces.
5. Apply the A* algorithm.
6. Recommend the nearest parking space.
7. Display the shortest path through the user interface.

---

## Repository Structure

```
├── README.md
└── report.pdf
```

---

## Future Improvements

- Live camera support.
- Mobile application.
- GPS integration.
- Google Maps integration.
- Multi-camera parking management.
- Real-time parking analytics.

---

##  Team

- Noran Aljodi
- Rema Althaqfi
- Enas Althyabi
- Asail Al-Osaimi
- Reema Alharbi
  
Artificial Intelligence Students

Umm Al-Qura University

