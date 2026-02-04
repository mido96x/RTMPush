       /$$$$$$$  /$$$$$$$$ /$$      /$$ /$$$$$$$                      /$$      
      | $$__  $$|__  $$__/| $$$    /$$$| $$__  $$                    | $$      
      | $$  \ $$   | $$   | $$$$  /$$$$| $$  \ $$ /$$   /$$  /$$$$$$$| $$$$$$$ 
      | $$$$$$$/   | $$   | $$ $$/$$ $$| $$$$$$$/| $$  | $$ /$$_____/| $$__  $$
      | $$__  $$   | $$   | $$  $$$| $$| $$____/ | $$  | $$|  $$$$$$ | $$  \ $$
      | $$  \ $$   | $$   | $$\  $ | $$| $$      | $$  | $$ \____  $$| $$  | $$
      | $$  | $$   | $$   | $$ \/  | $$| $$      |  $$$$$$/ /$$$$$$$/| $$  | $$
      |__/  |__/   |__/   |__/     |__/|__/       \______/ |_______/ |__/  |__/
                                                                               
                                                                               
                                                                               
# RTMPush

RTMPush is a simple script that captures video from a webcam and streams it to an RTMP server in real time.

## Features

- Real-time video streaming
- Customizable output URL
- User-friendly command line interface
- Built-in error handling
##Make the Script Executable

```bash
chmod +x RTMPush.sh
```

## Usage

To stream video, run the script with the following command:

```bash
./stream_camera.sh <output_url> <video_device>
```


**Example**:


```bash
./stream_camera.sh rtmp://localhost/live /dev/video0
```

## Requirements

- FFmpeg installed on your system.

```bash
sudo apt update
sudo apt install ffmpeg
```
## License

This project is licensed under the MIT License - see the LICENSE file for details.
