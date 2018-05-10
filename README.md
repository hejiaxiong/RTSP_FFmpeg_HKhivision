# RTSP_FFmpeg_HKhivision

本程序是在debug X86情况下建立的

配置环境vs2015+opencv2.4.10+ffmpeg

opencv配置成32位的

ffmpeg在官网下载32位配置好的
在c++目录加入lib，include
在程序的链接器的附加依赖项中加入
swscale.lib
avcodec.lib
avutil.lib
avformat.lib

SDL检查设置为否
不采用预编译头
