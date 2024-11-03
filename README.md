# FFmpeg-Static-Builds

These builds are downloaded via our [batch](https://github.com/smartpostapp/batch/actions) pipeline before compiling and uploading to AWS Lambda.

### Instructions
1. Create empty folder called `bin` on system
2. Download new build from [here](https://johnvansickle.com/ffmpeg/)
   - Select `ffmpeg-release-amd64-static.tar.xz` of the latest released build
3. Unzip `.tar` file
4. Copy `ffmpeg`, `ffprobe` and `readme.txt` to `bin` folder
5. Zip `bin` folder
6. Create new release [here](https://github.com/smartpostapp/FFmpeg-Static-Builds/releases)
   - Create new tag matching build version

### Source
This is a clone of the static builds from https://johnvansickle.com/ffmpeg/

