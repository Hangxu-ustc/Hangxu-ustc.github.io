---
layout: page
title: IoT Smart Parking System
permalink: /en/projects/2_project/
nav: false
---

B.Sc. thesis project combining deep-learning vision with IoT to close the loop of vehicle parking.

- **Architecture**: Raspberry Pi 5 (ARM) as the edge computing hub for plate recognition and vehicle detection; ESP32 as the lower-level controller for slot sensing and gate control.
- **Deployment**: YOLOv8 trained with PyTorch for plate detection, OpenCV preprocessing, and a CNN for character recognition.
- **Features**: accurate plate recognition and intelligent parking-slot monitoring and control.