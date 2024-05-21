```bash
echo "deb [trusted=yes] https://github.com/christianrauch/camera-ros-deb-builder/raw/noble-jazzy-amd64-package-xml-0.2-meson-strip-amd64/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_camera-ros-deb-builder.list
echo "yaml https://github.com/christianrauch/camera-ros-deb-builder/raw/noble-jazzy-amd64-package-xml-0.2-meson-strip-amd64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_camera-ros-deb-builder.list
```
