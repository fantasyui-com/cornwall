# cornwall
Electron-based PixiJS Video Recording Environment

![](out.gif)

## Notes

You will need ffmpeg to convert frames to video, for example:
ffmpeg -i img%03d.png -c:v libx264  -pix_fmt yuv420p out.mp4
