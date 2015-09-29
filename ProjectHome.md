ffcluster aims to provide a transcoding cluster system based on ffmpeg. It includes a web service, a basic dispatcher and a worker.

ffcluster 0.x (never released) was original written in C and rely on a shared file system and only support ffmpeg.

ffcluster 2.x will be completely rewritten in python, use the ftp protocol (and more) for file transfers and able to use more transcoding tools such as ffmpeg, mencoder, flvtool2, ...