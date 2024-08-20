# VLC RTSP Streaming App

This is an android application for streaming RTSP using OpenGL and libVlc.

## Sample app

- **VlcDemo.apk**. Rtsp url of this app: *rtsp://192.168.240.110:8554/test*

## Features

- Stream RTSP video
- Automatically reconnect to RTSP server if the connection is lost

## Installation

1. Open this repo with android studio
2. Modify url link at **app\src\main\java\com\example\frank\vlcdemo\MainActivity.java**
3. Build -> Build App Bundle(s)/APK(s) -> Build APK(s)
4. Apk output at **app\build\outputs\apk\debug\app-debug.apk**