# TrafficVision AI

### AI-Based Road Safety and Traffic Monitoring System Using Computer Vision

TrafficVision AI is a computer vision-based traffic monitoring system that analyses traffic videos using AI to detect, track, and analyse vehicles and pedestrians.

## Features

* Vehicle and pedestrian detection
* YOLO11 object detection
* ByteTrack object tracking
* Vehicle/object counting
* Traffic density analysis
* Traffic statistics
* Traffic movement analysis
* Traffic video upload
* Built-in demo traffic videos
* Web-based dashboard
* User authentication
* Admin dashboard

## Technologies Used

* Python
* Flask
* YOLO11
* ByteTrack
* OpenCV
* HTML
* CSS
* JavaScript
* Bootstrap
* Chart.js
* SQLite

## Project Structure

```text
AI-Road-Safety-Traffic-Monitoring/
│
├── app.py
├── config.py
├── auth.py
├── evaluate.py
├── requirements.txt
│
├── dashboard/
│   ├── static/
│   └── templates/
│
├── src/
│   └── Computer vision and traffic analysis modules
│
├── data/
│   └── videos/
│
├── database/
├── outputs/
├── uploads/
├── tests/
│
└── yolo11n.pt
```

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd AI-Road-Safety-Traffic-Monitoring
```

### 2. Create/activate the environment

```bash
conda activate roadsafety
```

Or create a new environment:

```bash
conda create -n roadsafety python=3.11
conda activate roadsafety
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

The application will run locally on:

```text
http://127.0.0.1:5001
```

## Usage

1. Open the application in a browser.
2. Sign in or create an account.
3. Open the dashboard.
4. Select a built-in traffic video or upload a video.
5. Start the analysis.
6. Wait for the video processing to complete.
7. View the traffic statistics and analysis results on the dashboard.

## Project Status

**Completed working prototype**

The current system implements the core traffic monitoring functionality including object detection, object tracking, traffic counting, density analysis, video processing, and dashboard visualisation.

## Academic Project

**Project:** AI-Based Road Safety and Traffic Monitoring System Using Computer Vision

**Type:** Computer Vision / Artificial Intelligence Project

**Platform:** Python Web Application

---

The detailed project report is submitted separately as required.
