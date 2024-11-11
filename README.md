
## Commands

Downscale resolution of a video 4x: 

```
ffmpeg -i tigerwoods_01_b.mp4 -vf "scale=iw/4:ih/4" -c:a copy tigerwoods_01_b_downscaled.mp4
```

