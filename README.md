# HDL Localization ROS2 (Jazzy)

This project is an updated version of the HDL localization package to be compatible with ROS2 Jazzy. The original code was based on the repository [hdl-localization](https://github.com/koide3/hdl_localization), and this version includes modifications to ensure it works smoothly with ROS2 Jazzy.


## Changes from Humble to Jazzy

1. Obtain the ndt_omp package from koide3's [ndt_omp](https://github.com/koide3/ndt_omp)
2. Change `<tf2_eigen/tf2_eigen.h>` to `<tf2_eigen/tf2_eigen.hpp>` in `hdl_localization/apps/hdl_localization_nodelet.cpp`.
3. Replace Boost functions with `std` declarations in `hdl_localization/apps/globalmap_server_nodelet.cpp`.

## Acknowledgment

Original code from [hdl-localization](https://github.com/koide3/hdl_localization).

ROS2 code from [Hdl-Localization-ROS2-Humble](https://github.com/dawan0111/Hdl-Localization-ROS2-Humble.git).
