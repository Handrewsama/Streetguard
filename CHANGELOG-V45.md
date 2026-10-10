# SpeedGuard V45 — Vision Object Detection Prototype

- Added experimental in-browser object detection using TensorFlow.js and COCO-SSD Lite MobileNet V2, loaded from a CDN.
- Draws confidence-labelled bounding boxes for common objects and shows detected class labels.
- Detection is visual-only: no collision-risk inference, voice alerts, braking advice, or hazard warnings are enabled.
- Model requires internet access on first load; model/library are not bundled for offline use.
- Kept camera permission handling and manual start/stop; capture and detection stop when the page becomes hidden.
- Existing radar/GPS/halo logic remains unchanged.
- Bumped service-worker cache to V45.
- Safety: test while parked or using recorded footage; this prototype is not a driver-assistance or collision-avoidance system.
