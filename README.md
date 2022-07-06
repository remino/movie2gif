movie2gif
=========

```
Usage: movie2gif [options] input [output]

Convert a video file into an animated GIF file.

Available options:

	-a   Time scale. Less than 1 to speed up, more to slow down. (Default: 1)
	-c   Number of colours in palette. (Default: 32)
	-d   Duration in seconds. (Default: all)
	-f   Override all filters with specified ffmpeg filters.
	-h   Show this help screen.
	-m   Append specified ffmpeg filters.
	-n   Dry run. Don't write to any file.
	-o   Crop image (out_w:out_h:x:y). (Default: no crop)
	-r   Number of frames per second (FPS). (Default: 10)
	-s   Start time in seconds. (Default: 0)
	-t   Image height of output. (Default: -1, keeping ratio with width)
	-v   Make console output verbose.
	-w   Image width of output. (Default: 720)
```

