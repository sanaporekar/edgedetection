# edgedetection

This Android project demonstrates real-time camera frame capture, C++ OpenCV-based edge detection (via JNI), and rendering the processed output using OpenGL ES 2.0.

It was created as part of an R&D Intern assessment requiring integration of:

Android Camera2 API

JNI & NDK

OpenCV (C++)

OpenGL ES 2.0

🚀 Features Implemented

Real-time camera feed using Camera2 API

Frame processing in native C++ using OpenCV

Canny edge detection

Processed frames rendered via OpenGL ES 2.0

Modular architecture with separation of camera, JNI, and renderer logic


project structure

/app
  ├── java/com/example/edgedetect
  │    ├── MainActivity.java
  │    ├── CameraHelper.java
  │    └── GLRenderer.java
  ├── cpp/
  │    ├── native-lib.cpp
  │    ├── OpenCVProcessor.cpp
  │    └── OpenCVProcessor.hpp
  ├── res/
  ├── AndroidManifest.xml
  └── build.gradle
