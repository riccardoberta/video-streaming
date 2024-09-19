#Design and development of an embedded system for video streaming
This thesis project proposes the development and design of an embedded IoT system for a remote-controlled car called Traxxas, operated remotely via a mobile application. The work focused on adding a new feature: the acquisition, transmission, and reception on a mobile device of a video stream showing the vehicle's front view. To achieve this, a camera mounted on an ESP-EYE board, a microcontroller based on an ESP32 chip, was placed on the front fender to provide a real-time view of the road ahead of the car.

The image sequences that make up the video are transmitted by the ESP-EYE via WebSocket over a LAN WiFi network and then received by the mobile device running the application. The app displays the video stream on the screen, with the controls for operating the Traxxas car overlaid on the video. In this way, the user can maneuver the vehicle remotely, taking advantage of the real-time view of the driving environment.
