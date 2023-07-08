# Person-Counter

- Detects person and keeps tracking them in the frame. It uses centroid tracking assigns a unique ID to each detected person.
- Monitors social distance between the persons. If it is less than a threshold value, we display bounding box in red otherwise green.
- Gives the overall (OPC) and live person count (LPC).
- Displays the fps we are getting while inferencing on a video file or frame from live usb webcam.
- Non-max-suppression to remove noises