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
chmod +x RTMPush
```

## Usage

To stream video, run the script with the following command:

```bash
./RTMPush <output_url> <video_device>
```


**Example**:


```bash
./RTMPush rtmp://localhost/live /dev/video0
```

**Kill the Process Manually**:

If you need to stop the stream but can't access the terminal where the script was run:

*Find the Process ID (PID):*

```bash
ps aux | grep ffmpeg
```
*Kill the Process:*
```bash 
kill [PID]
```
Replace [PID] with the actual process ID you found.
## Requirements

- FFmpeg installed on your system.

```bash
sudo apt update
sudo apt install ffmpeg
```
## License

This project is licensed under the MIT License - see the LICENSE file for details.
