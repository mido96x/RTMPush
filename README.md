# RTMPush

RTMPush is a simple script that captures video from a webcam and streams it to an RTMP server in real time.

## Features

- Real-time video streaming
- Customizable output URL
- User-friendly command line interface
- Built-in error handling

## Usage

To stream video, run the script with the following command:

./stream_camera.sh <output_url> <video_device>


**Example**:


./stream_camera.sh rtmp://localhost/live /dev/video0


## Requirements

- FFmpeg installed on your system.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
