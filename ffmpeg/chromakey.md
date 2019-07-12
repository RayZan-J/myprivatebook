#ffmpeg日常命令--视频覆盖图片

##将一个视频覆盖在图片上
```
ffmpeg -loop 1 -i  bg.png -i front.mov -filter_complex "[1:v]chromakey=Black:0.01:0.2[ckout];[0:v][ckout]overlay[out]" -map "[out]" -t 10  -y out.mp4
```
chromakey是一种视频滤镜，可将对应的颜色设置为透明，实现抠图的功能；图片与视频均可操作；
具体应用：
1.可实现将带有背景颜色的logo，去掉背景色，作视频的水印
2.可将某个视频的背景色去掉，覆盖在其他视频(待验证)，或图片上，实现特效功能

语法：chromakey=color:similarity:blend
color:
```
指定要被替换为透明的颜色
```
similarity：
```
设置一个百分比，当像素的颜色与指定颜色的相似度达到该值时被替换,0.01为完全相同，为1时匹配任何颜色
```
blend
```
融合程度(百分比)0.0时完全不融合，很突兀，1时效果最淡
```
similarity == 1，blend == 0.2的效果：
![similarity == 1](/assets/Selection_003.png)
similarity == 0.01，blend == 0.2的效果：
![Selection_002](/assets/Selection_002.png)
blend == 0，similarity == 0.01的效果:
![Selection_004](/assets/Selection_004.png)
blend == 1，similarity == 0.01的效果:
![Selection_005](/assets/Selection_005_gpsbpnvvy.png)

最终选择similarity == 0.01 ，blend == 0.2的效果
