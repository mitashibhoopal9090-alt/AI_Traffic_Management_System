# AI Traffic Management System

Production-ready web application for vehicle detection and intelligent traffic light timing using YOLOv8.

## Features

- 🚗 Vehicle detection (cars and trucks) using YOLOv8
- 📊 Real-time vehicle counting and statistics
- 🚦 Intelligent traffic light timing recommendations
- 🎨 Modern web interface with drag-and-drop upload
- 📦 Production-ready FastAPI backend
- ⚡ Fast inference with model loaded at startup

## Project Structure

```text
ai-traffic-management/
├── backend/
│   ├── main.py              # FastAPI application
│   ├── config.py            # Configuration settings
│   ├── models.py            # Pydantic models
│   ├── detector.py          # YOLO detection logic
│   ├── traffic_logic.py     # Traffic timing logic
│   └── requirements.txt     # Python dependencies
├── frontend/
│   ├── index.html           # Main HTML page
│   ├── styles.css           # CSS styling
│   └── app.js               # JavaScript logic
├── models/
│   └── best.pt              # YOLOv8 trained model
└── uploads/                 # Temporary uploads
