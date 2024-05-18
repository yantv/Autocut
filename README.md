**Tool for Removing Silences from Videos**

This tool is designed for simplicity and efficiency, automatically cutting out all silences from your videos.
It's particularly useful for shortening lecture recordings or automating the initial editing process for your own videos.

**Dependencies**
(ffmpeg)
python3
ffmpeg
ffprobe

**Windows users**

Make sure, that the path to ffmpeg and ffprobe are inside the "path variable". I.e. you can run both commands from the command line like C:> ffmpeg

**How to use**
Easiest command:
Autocut.py [input_file]

Show help and more options:
Autocut.py -h

All options:
Autocut.py [-h] [-o OUTPUT_FILE] [-n NOISE_TOLERANCE] [-d MIN_DURATION] [-m MARGIN] input_file
