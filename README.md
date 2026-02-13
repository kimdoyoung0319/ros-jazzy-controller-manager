# ROS2 Jazzy ros-jazzy-controller-manager patch

A quick fix for build failure of `ros-jazzy-controller-manager`, enabling
software implementations for unsupported atomic operations.

- Only targets for `riscv64`.
- Contains Debian package metadata to that it can be built via 
  `dpkg-buildpackage`
