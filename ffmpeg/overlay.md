# 将图片逐帧作为水印

看到有个需要，将一些图片作为水印，逐帧到视频：
```
ffmpeg -i %d.png -i video.mp4 -filter_complex "[1:v][0:v]overlay=x=0:y=0" out.mp4
```

##另外一个需求，这些图片可能会变动位置
```
ffmpeg -i %d.png -f lavfi -i nullsrc=s=1920x1080 -filter_complex "[1:v][0:v]overlay=x='if(gte(t,2), -w+(t-2)*20, NAN)':y=0" -vcodec h264_videotoolbox -b:v 2000k a.ts
```

来自大师兄的命令，后续研究透了再补充
