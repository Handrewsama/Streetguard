# SpeedGuard V44 — Vision Prototype

- Added an experimental camera panel using the rear-facing camera when supported.
- Added explicit camera permission/error states and manual start/stop controls.
- Stops capture when the page becomes hidden because iOS PWA background camera operation is not guaranteed.
- No object detection or hazard alerts are enabled in this version; existing radar/GPS logic is unchanged.
- Bumped service-worker cache to V44.
