```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/christianrauch/camera-ros-deb-builder/noble-jazzy-arm64-package-xml-0.5-meson_wrap_mode/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_camera-ros-deb-builder-noble-jazzy-arm64-package-xml-0.5-meson_wrap_mode.list
echo "yaml https://github.com/christianrauch/camera-ros-deb-builder/raw/noble-jazzy-arm64-package-xml-0.5-meson_wrap_mode/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_camera-ros-deb-builder-noble-jazzy-arm64-package-xml-0.5-meson_wrap_mode.list
```
