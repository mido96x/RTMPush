#!/bin/bash

# Define the output streaming link (modify with your streaming service info)
OUTPUT_URL="rtmp://localhost/live"  # Replace with your RTMP or HTTP link

# Start streaming from the webcam (adjust /dev/video0 if needed)
ffmpeg -f v4l2 -i /dev/video0 -f flv "$OUTPUT_URL"
