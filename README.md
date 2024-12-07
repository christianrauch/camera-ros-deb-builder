```bash
echo "deb [trusted=yes] https://github.com/christianrauch/camera-ros-deb-builder/raw/noble-jazzy-amd64-package-xml-0.3-meson-strip-thread_fixes/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_camera-ros-deb-builder.list
echo "yaml https://github.com/christianrauch/camera-ros-deb-builder/raw/noble-jazzy-amd64-package-xml-0.3-meson-strip-thread_fixes/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_camera-ros-deb-builder.list
```
