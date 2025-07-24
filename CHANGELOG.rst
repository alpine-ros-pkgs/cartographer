^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cartographer
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.1000 (2025-07-24)
---------------------
* Fix base branch of release candidate workflow (`#6 <https://github.com/alpine-ros-pkgs/cartographer/issues/6>`_)
* Fix CI target branch (`#4 <https://github.com/alpine-ros-pkgs/cartographer/issues/4>`_)
* Migrate to Alpine ROS 1 (`#1 <https://github.com/alpine-ros-pkgs/cartographer/issues/1>`_)
* Drop CI for debian buster
* Make sure the cartographer CMake config finds boost. (`ros2/cartographer#26 <https://github.com/ros2/cartographer/issues/26>`_)
* Update cartographer to deal with newer ceres (`ros2/cartographer#24 <https://github.com/ros2/cartographer/issues/24>`_)
* Remove CERES_INCLUDE_DIRS.
* Fix compile warnings
* Workaround warning about not finding GOOGLETEST_VERSION.
* restrict boost dependencies to the ones used (`ros2/cartographer#14 <https://github.com/ros2/cartographer/issues/14>`_)
* Update the package.xml dependencies.
* Add note for ROS users. (`#1941 <https://github.com/alpine-ros-pkgs/cartographer/issues/1941>`_)
* update rules_boost to latest version (`#1898 <https://github.com/alpine-ros-pkgs/cartographer/issues/1898>`_)
* Add Debian Bullseye to the install scripts, CI, docs. (`#1897 <https://github.com/alpine-ros-pkgs/cartographer/issues/1897>`_)
* removed unused param from cmake macro (`#1847 <https://github.com/alpine-ros-pkgs/cartographer/issues/1847>`_)
* Fix crash caused by setting gravity lower bound (`#1893 <https://github.com/alpine-ros-pkgs/cartographer/issues/1893>`_)
* Remove Debian Stretch from CI. (`#1895 <https://github.com/alpine-ros-pkgs/cartographer/issues/1895>`_)
* Fix CI for Ubuntu 18.04 by disabling gRPC test build for now. (`#1891 <https://github.com/alpine-ros-pkgs/cartographer/issues/1891>`_)
* Fix typo in trajectory_builder_3d.lua (`#1870 <https://github.com/alpine-ros-pkgs/cartographer/issues/1870>`_)
* Add Ubuntu 22.04 to the install scripts, CI, docs. (`#1888 <https://github.com/alpine-ros-pkgs/cartographer/issues/1888>`_)
* Add libabsl-dev to the package.xml dependencies. (`#1875 <https://github.com/alpine-ros-pkgs/cartographer/issues/1875>`_)
* Move to GitHub Actions for CI. (`#1884 <https://github.com/alpine-ros-pkgs/cartographer/issues/1884>`_)
* Remove Ubuntu Xenial from CI. (`#1833 <https://github.com/alpine-ros-pkgs/cartographer/issues/1833>`_)
* Contributors: Atsushi Watanabe, Chris Lalancette, Katherine Scott, Linh Nguyen, Mikael Arguedas, Takashi Ogura, Wolfgang Hess, XiaotaoGuo, Xùdōng Yáng

2.0.0 (2021-03-09)
------------------
https://github.com/cartographer-project/cartographer/compare/1.0.0...2.0.0

1.0.0 (2018-06-01)
------------------
https://github.com/googlecartographer/cartographer/compare/0.3.0...1.0.0

0.3.0 (2017-11-23)
------------------
https://github.com/googlecartographer/cartographer/compare/0.2.0...0.3.0

0.2.0 (2017-06-19)
------------------
https://github.com/googlecartographer/cartographer/compare/0.1.0...0.2.0

0.1.0 (2017-05-18)
------------------
* First unstable development release
