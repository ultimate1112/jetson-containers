# jetson-containers

This repo aims to build ROS-based containers for the NVIDIA Jetson platform.

Unlike the [standard ROS containers provided by OSRF](https://hub.docker.com/r/osrf/ros/), these are built on the [l4t-base container](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/l4t-base), allowing Jetson-specific features to be used, ie. CUDA, and thus accelerated performance.

The original source for this project is [dusty-nv/jetson-containers](https://github.com/dusty-nv/jetson-containers). However, we are to target the different metapackages (ie. ros_base, desktop) for a specific version, being JetPack 4.6 (based on L4T 32.6.1). 

Our targeted devices are:
- Jetson TX2 (standard 8GB)
- Jetson Nano 4GB
- Jetson Nano 2GB

## Usage

Each branch represents a different image. Unless specified in the README.md file, all branches are production-ready.

## License

[MIT](https://choosealicense.com/licenses/mit/)

