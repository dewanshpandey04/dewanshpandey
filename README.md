# Dewansh Pandey

**AI/ML Engineer | Computer Vision | Autonomous Systems | Edge AI**

I build real-time computer-vision software for aerial perception and embedded AI systems, with hands-on work in **YOLO object detection, ByteTrack multi-object tracking, target-state handling, selected-track lock state, RTSP/video pipelines, CUDA, NVIDIA Jetson, and Raspberry Pi**.

## Engineering focus

- Real-time object detection and multi-object tracking
- Aerial perception and autonomous-system software interfaces
- Edge-AI deployment on NVIDIA Jetson and Raspberry Pi
- Low-latency video / RTSP processing
- Runtime metrics, benchmarking, diagnostics, and metadata pipelines
- Modular Python software with unit tests, linting, CLI smoke tests, and multi-version CI

## Selected engineering repositories

### Automated Interceptor Drone Guidance & Perception System

[![CI](https://github.com/dewanshpandey04/automated-interceptor-drone-guidance-system/actions/workflows/ci.yml/badge.svg)](https://github.com/dewanshpandey04/automated-interceptor-drone-guidance-system/actions)

[Repository](https://github.com/dewanshpandey04/automated-interceptor-drone-guidance-system)

Real-time perception software built around **YOLO + ByteTrack** with typed target state, explicit perception-layer selected-track / lock-state handling, JSON telemetry output, runtime health monitoring, YAML/CLI configuration, benchmarking, and automated quality checks.

**Implemented engineering components**
- YOLO object-detection entry point
- ByteTrack persistent multi-object tracking
- `TrackState` normalization layer
- explicit selected-track state management
- serializable `PerceptionSnapshot` interface
- rolling FPS / frame-time metrics
- runtime health-state evaluation
- YAML runtime configuration
- text + JSON benchmark reporting
- syntax, lint, CLI-smoke, and unit-test CI on Python 3.10 / 3.11 / 3.12

**Original project results:** ~18,000 aerial training images, custom detector mAP50 > 0.92, 70+ FPS on Jetson Orin NX, and 50+ FPS optimized live-camera inference.

### AI-Powered Aerial Surveillance & Multi-Object Tracking System

[![CI](https://github.com/dewanshpandey04/aerial-surveillance-multi-object-tracking/actions/workflows/ci.yml/badge.svg)](https://github.com/dewanshpandey04/aerial-surveillance-multi-object-tracking/actions)

[Repository](https://github.com/dewanshpandey04/aerial-surveillance-multi-object-tracking)

Real-time aerial detection and tracking software for webcam, recorded-video, and network-stream inputs with normalized track metadata, filtering, buffered JSONL export, offline summaries, frame-time/FPS metrics, and edge-deployment documentation.

**Implemented engineering components**
- YOLO + ByteTrack surveillance pipeline
- persistent track IDs and normalized `TrackRecord` objects
- credential-safe RTSP/network-stream labeling
- class/confidence metadata filtering
- active-track and class summaries
- buffered JSONL metadata export
- offline tracking-data summarization
- YAML/CLI runtime configuration
- frame-time / approximate FPS metrics
- text + JSON inference benchmarking
- syntax, lint, CLI-smoke, and unit-test CI on Python 3.10 / 3.11 / 3.12

**Original project results:** custom aerial detector mAP50 > 0.92 and optimized live UAV-camera inference at 50+ FPS.

## Technical stack

**Languages:** Python, C++, Java, SQL  
**Computer Vision:** YOLO, OpenCV, Object Detection, Multi-Object Tracking, ByteTrack  
**AI / ML:** PyTorch, TensorFlow, Scikit-learn, NumPy, Pandas  
**Edge AI:** NVIDIA Jetson Orin NX / Nano, Raspberry Pi 5, CUDA  
**Video / Streaming:** RTSP, live camera pipelines, OpenCV  
**Engineering:** Git, GitHub Actions, Docker, Pytest, Ruff, YAML configuration, benchmarking  
**Data / Annotation:** CVAT, Label Studio

## Engineering practices

I prefer small modules with clear responsibilities, framework-independent data models, explicit configuration, automated tests, reproducible benchmarks, CI quality gates, and documented separation between reusable source code and private deployment artifacts.

## Contact

**LinkedIn:** [Dewansh Pandey](https://www.linkedin.com/in/dewansh-pandey-9b564a317)  
**GitHub:** [dewanshpandey04](https://github.com/dewanshpandey04)  
**Email:** d.pandey1294@gmail.com
