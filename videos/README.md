Video generated from tif files https://svs.gsfc.nasa.gov/4964 https://svs.gsfc.nasa.gov/vis/a000000/a004900/a004964/frames/2048x1024_2x1_30p/

```sh
ffmpeg -framerate 10 -pattern_type glob -i '*.tif' -c:v libx264 -crf 25 SOSGISS2021c-Rolling1peryear-RollingAverageperyear.mp4
```