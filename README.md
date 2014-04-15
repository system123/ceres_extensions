ceres_extensions
================

Some extensions to make ceres solver work a little better with Eigen.

This includes:
  * Eigen Quaternion parameterizations
  * Eigen Quaternion rotations
  * Eigen Quaternion multiplications

To use the extensions just reference ceres_ext namespace and append the normal name with Eigen.

ie: 

ceres::QuaternionParameterization becomes ceres_ext::EigenQuaternionParameterization

I might consider creating a pull request against ceres solver but I am too lazy to do it now.
