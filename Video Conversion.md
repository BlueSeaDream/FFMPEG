## FFMPEG Usage
. **Crop a video clip based on the time

ffmpeg -i example.mp4 -ss 00:00:00 -t 00:01:51 -async 1 -c copy example_cut.mp4

. **Resize a batch of images**

ffmpeg –i D:\Temp\spark_%04d.png –vf scale=960x540 .\res\spark_ss_%04d.png
