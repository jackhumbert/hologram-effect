# Hologram effect using Blender's geometry nodes and Record3D RGBD videos

Things you'll need to create your own:

* [Blender 2.93](https://www.blender.org/download/)
* iPhone/iPad with FaceID (no LIDAR necessary)
* [Record3D](https://record3d.app/index), [App Store Link](https://apps.apple.com/us/app/record3d-3d-videos/id1477716895?ls=1) (paid upgrade to be able to export videos is $3)

Some other technical details for those that are interested:
* [RGBD video format](https://github.com/marek-simonik/record3d-simple-wifi-streaming-demo#22-rgbd-video-format)
* [Some math I used to project the points](https://github.com/marek-simonik/record3d-wifi-streaming-and-rgbd-mp4-3d-video-demo/blob/master/js/app/pointcloud-material.js#L88)
* [Intrinsic matrix calculations](https://github.com/marek-simonik/record3d-wifi-streaming-and-rgbd-mp4-3d-video-demo/blob/master/js/app/Record3DVideo.js#L53)
* [More info on intrinsic matrices](http://ksimek.github.io/2013/08/13/intrinsic/)
