# Download your spotify playlist or just spesific tracks as a mp3 file without any API key or token requirements

## Console look

![console look](https://i.ibb.co/znCymsc/Ekran-g-r-nt-s-2021-12-26-140751.png)

## Requirements

### Pip's

    pip install selenium colored pytube yt-dlp

### Chrome Driver

 Current Chrome Driver version: 105

 Download the latest [Chrome Driver](https://chromedriver.chromium.org/downloads). It must be the same version of Chrome with in your computer.
 Add chromedriver.exe in to "driver" folder.

### FFmpeg (Higher download speed)
  
 There are 2 download options for downloading playlist. If you like to use "yt-dlp" you need to install FFmpeg.

#### Installing FFmpeg

Download Link: <https://www.ffmpeg.org/download.html>

#### Installation for Windows

 Watch this video: <https://youtu.be/r1AtmY-RMyQ>

## Usage

Run the "downloader.py", choose prefered download option and paste your spotify playlist/song link. Yeah, that's all.

## Notes

- The names of the tracks and youtube links are will be collected in a text file.
- Downloaded tracks will be appear in downloads folder.
- If you want to change the folder paths, you have to define your own paths in _paths file

***
    self.savePath = 'Downloads'
    self.textPath = Texts/downloaded-links.txt'
    nTextPath = 'Texts/skipped-links.txt'
    self.driverPath = 'driver/chromedriver.exe'
***
