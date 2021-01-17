project(eigen)

cmake_minimum_required(VERSION 3.0)
## Find catkin macros and lib
find_package(catkin REQUIRED)
find_package(Eigen3 REQUIRED)

catkin_package(
  INCLUDE_DIRS "${EIGEN3_INCLUDE_DIR}"
)
