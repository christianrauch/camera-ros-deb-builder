```bash
echo "deb [trusted=yes] https://github.com/christianrauch/camera-ros-deb-builder/raw/jammy-humble-arm64-package-xml-0.2-meson-strip-arm64/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_camera-ros-deb-builder.list
echo "yaml https://github.com/christianrauch/camera-ros-deb-builder/raw/jammy-humble-arm64-package-xml-0.2-meson-strip-arm64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_camera-ros-deb-builder.list
```
