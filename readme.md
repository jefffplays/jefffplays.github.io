Here's a command to convert videos to be uploaded to this website:
```
ffmpeg -i input.mp4 -vf "scale=720:-1" -c:v libx264 -preset slow -crf 23 -c:a aac -b:a 128k -movflags +faststart output.mp4
```
