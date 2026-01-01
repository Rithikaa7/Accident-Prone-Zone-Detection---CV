# Accident-Prone Zone Detection using Computer Vision

A computer vision–based project that analyzes traffic video frames to identify potential accident-prone zones using object detection and explainable risk analysis.  
Designed as an offline, ethical, and non-real-time public safety analysis tool for academic and research purposes.

---

## Project Description
This project presents an **Accident-Prone Zone Detection System** built using **Computer Vision techniques** and **rule-based risk analysis**.  
The system focuses on identifying traffic risk patterns by analyzing vehicle and pedestrian density from traffic video frames.

The project is designed strictly as an **offline, non-real-time, and non-surveillance analytical tool**.  
It demonstrates how object detection models can support **preventive traffic safety assessment** without making deployment or enforcement claims.

---

## Problem Statement
Road traffic accidents remain a major public safety challenge, often influenced by high vehicle congestion and pedestrian movement.  
While large-scale traffic monitoring systems exist, there is a need for **explainable and interpretable analysis frameworks** that can highlight accident-prone scenarios from visual data.

This project explores how computer vision can be used to:
- Analyze traffic density patterns
- Identify potential high-risk traffic conditions
- Provide interpretable and visual risk indicators
- Support traffic safety research and planning

---

## Key Features
- YOLO-based vehicle and pedestrian detection
- Frame-wise traffic risk computation
- Explainable rule-based risk scoring mechanism
- Risk classification into Low, Medium, and High categories
- Trend analysis of traffic risk across frames
- Risk score distribution and heatmap visualization
- Annotated traffic frames with color-coded risk overlays
- Clear separation between analysis and visualization pipelines

---

## System Workflow
1. Traffic video is provided as offline input
2. Frames are extracted at fixed intervals
3. Object detection is applied to identify vehicles and pedestrians
4. Traffic density is computed for each frame
5. An explainable risk scoring logic classifies accident risk
6. Risk trends and distributions are analyzed
7. Annotated frames provide qualitative verification

---

## Technologies Used
- Python
- Ultralytics YOLO
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run the Project
1. Clone or download the repository
2. Install the required dependencies:
3. Open the notebook in Jupyter Notebook or JupyterLab
4. Run all cells sequentially from top to bottom

---

## Ethical Considerations
This project is developed strictly for **academic and research purposes**.

- Uses only offline, pre-recorded traffic videos
- Does not perform real-time surveillance or tracking
- Does not store personal or identifiable information
- Avoids claims related to enforcement or live deployment

---

## Limitations
- Risk scoring is rule-based and may require domain calibration
- Detection performance depends on video quality and lighting
- The system does not predict accidents or outcomes

---

## Future Scope
- Incorporate time-series modeling for temporal risk trends
- Integrate weather or environmental data
- Extend to multi-camera traffic analysis
- Explore supervised learning for adaptive risk scoring
- Develop controlled dashboard-based visualization

---

## Author
**Rithikaa V**  
B.Tech – Information Technology
