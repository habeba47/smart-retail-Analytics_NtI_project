# Smart Retail Analytics using YOLO and Object Tracking

## Overview

This project is a computer vision–based retail analytics system designed to monitor customer behavior inside a store using video footage. The system detects and tracks people in real time, analyzes customer movement across different store zones, generates heatmaps, measures dwell time, and provides performance evaluation metrics.

The solution uses the YOLO object detection model together with multi-object tracking techniques to maintain consistent customer identities throughout the video.

---

## Features

### Customer Detection

* Detects people in video streams using YOLO.
* Filters detections based on confidence thresholds.
* Supports real-time and recorded video analysis.

### Multi-Object Tracking

* Assigns unique IDs to detected customers.
* Maintains tracking history across frames.
* Visualizes movement trajectories.

### Zone-Based Analytics

* Divides the store into predefined sections.
* Identifies the current zone of each customer.
* Tracks customer transitions between zones.

### Dwell Time Analysis

* Measures how long customers stay in each zone.
* Records customer movement paths.
* Provides insights into customer engagement.

### Heatmap Generation

* Creates heatmaps showing high-traffic areas.
* Visualizes customer density across the store.
* Helps identify popular and underutilized sections.

### Queue and Crowd Monitoring

* Estimates crowd density over time.
* Tracks customer counts per frame.
* Supports queue analysis for operational optimization.

### Performance Evaluation

* Measures processing speed (FPS).
* Tracks system runtime.
* Collects evaluation metrics for analysis.

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Ultralytics YOLO
* Supervision Library
* BoT-SORT Tracker

---

## Project Structure

```text
├── Detection Module
│   ├── YOLO Person Detection
│   └── Confidence Filtering
│
├── Tracking Module
│   ├── ID Assignment
│   ├── Trajectory Tracking
│   └── Movement History
│
├── Zone Analytics
│   ├── Zone Detection
│   ├── Dwell Time Calculation
│   └── Customer Flow Analysis
│
├── Heatmap Analytics
│   ├── Density Mapping
│   └── Traffic Visualization
│
└── Evaluation Module
    ├── FPS Measurement
    ├── Runtime Analysis
    └── Performance Metrics
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/smart-retail-analytics.git
cd smart-retail-analytics
```

Install dependencies:

```bash
pip install ultralytics supervision opencv-python numpy
```

---

## Usage

1. Place the input video inside the project directory.
2. Update the video path in the notebook or script.
3. Run all notebook cells.
4. The system will:

   * Detect customers
   * Track movement
   * Generate analytics
   * Create visualized output videos

---

## Example Analytics Outputs

* Customer count over time
* Zone occupancy statistics
* Customer dwell time reports
* Store heatmaps
* Customer movement trajectories
* Queue monitoring statistics

---

## Applications

* Retail Store Analytics
* Customer Behavior Analysis
* Shopping Pattern Monitoring
* Store Layout Optimization
* Queue Management
* Footfall Analysis
* Business Intelligence Dashboards

---

## Future Improvements

* Product interaction tracking
* Employee vs customer classification
* Real-time dashboard integration
* Multi-camera support
* Customer re-identification across cameras
* Predictive customer behavior analysis

---

## Authors

Developed as a Computer Vision and Retail Analytics project using YOLO-based object detection and tracking techniques.
