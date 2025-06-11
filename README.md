# XR Unity

An Augmented Reality application built with Unity demonstrating AR functionality for iOS (ARKit) and Android (ARCore) platforms.

## Overview

This project showcases AR capabilities including point cloud visualization, camera tracking, and spatial understanding on mobile devices using Unity's AR Foundation framework.

## Features

- **Cross-Platform AR**: Supports both iOS (ARKit) and Android (ARCore)
- **Point Cloud Visualization**: Particle system rendering of 3D point clouds
- **AR Session Management**: Lifecycle control for AR experiences
- **AR Camera Integration**: Vision-based tracking

## Tech Stack

| Component | Technology |
|-----------|------------|
| Engine | Unity 2021.3.16f1 |
| AR Framework | AR Foundation 4.2.7 |
| iOS Support | ARKit 4.2.7 |
| Android Support | ARCore 4.2.7 |
| UI | TextMeshPro 3.0.6 |

## Project Structure

```
XR_Unity/
├── Assets/
│   ├── Scenes/
│   │   ├── SampleScene.unity    # Main AR scene
│   │   └── PCL_Prefab.prefab    # Point cloud prefab
│   └── XR/
│       └── Settings/            # Platform configurations
├── Packages/                    # Dependencies
└── ProjectSettings/             # Unity settings
```

## Scene Components

- **AR Session Origin**: Root transform for AR content
- **AR Session**: Manages AR lifecycle
- **AR Camera**: Provides tracking and camera feed
- **Directional Light**: Scene illumination
- **Sample Cube**: 3D reference object

## Building

### iOS (ARKit)
1. Switch to iOS in Build Settings
2. ARKit loader is pre-configured
3. Deploy to device with A9 chip or newer

### Android (ARCore)
1. Switch to Android in Build Settings
2. ARCore loader is pre-configured
3. Requires ARCore-supported device
4. Use included keystore for signing

## Requirements

- Unity 2021.3.16f1
- iOS 13.6+ or Android 7.0+ with ARCore
- Device with camera and motion sensors

## Getting Started

1. Clone the repository
2. Open with Unity Hub (2021.3.16f1)
3. Load `SampleScene.unity`
4. Configure build target (iOS/Android)
5. Build and deploy to device

---

## XR Unity Image Generation Prompt

An immersive augmented reality visualization showing a smartphone held up revealing digital content overlaid on the real world. Through the device screen, a 3D point cloud materializes as thousands of glowing particles mapping the physical environment—walls, floors, and surfaces detected and visualized in cyan and magenta dots. A virtual cube floats in AR space, anchored to a detected surface with shadow grounding it in reality. The AR camera feed shows a living room scene with the digital overlay seamlessly integrated. Platform icons for iOS (ARKit) and Android (ARCore) float as badges indicating cross-platform support. The AR Session indicator pulses green showing active tracking. Unity's AR Foundation logo appears subtly. Spatial mesh wireframes hint at environment understanding beneath the point cloud. The phone's camera captures real-world imagery while rendering virtual augmentations. The background blends physical room photography with digital particle effects at the boundaries. Style: AR technology demonstration, Unity showcase quality, mobile XR promotional material, emphasizing the magic of digital content anchored in physical reality through computer vision.
