# j264chunk
Tool for splitting RTSP stream on fixed time h264 mkv files

This tool receive h264 stream from source, extract frames from network packages and muxing it to mkv-container. All actions executed wihtout reencoding of h264 format. The source is a network resource which generates a stream of frames in h.264. It can be both the network video camera, and the application.
