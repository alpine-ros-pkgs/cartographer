.. Copyright 2016 The Cartographer Authors

.. Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

..      http://www.apache.org/licenses/LICENSE-2.0

.. Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

============
Cartographer
============

|license|

Purpose
=======

`Cartographer`_ is a system that provides real-time simultaneous localization
and mapping (`SLAM`_) in 2D and 3D across multiple platforms and sensor
configurations.

|video|

.. _Cartographer: https://github.com/cartographer-project/cartographer
.. _SLAM: https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping

A Note for ROS Users
====================

**Cartographer is no longer actively maintained.**
On rare occasions critical pull requests may be merged, but no new development is currently taking place, including issue response.
If you are installing Cartographer in ROS 1 / ROS 2 using a binary package that package is a fork of this repository.
The ROS fork of Cartographer is only maintained in a limited capacity.
No new development takes place on this fork, but pull requests may be merged at the maintainers' discretion.    

The ROS fork of Cartographer, and the ROS wrapper library, can be found at these locations:

- `Cartographer Fork <https://github.com/ros2/cartographer>`_
- `Cartographer ROS  <https://github.com/ros2/cartographer_ros>`_

Additional discussion can be found in `this ROS Discourse thread<https://discourse.ros.org/t/rolling-and-soon-humble-release-of-both-cartographer-and-cartographer-ros-v2-and-call-for-testing/25137>`_.  


Getting started
===============

* Learn to use Cartographer at `our Read the Docs site`_.
* You can ask a question by `creating an issue`_.

.. _our Read the Docs site: https://google-cartographer.readthedocs.io
.. _creating an issue: https://github.com/cartographer-project/cartographer_ros/issues/new?labels=question

Contributing
============

You can find information about contributing to Cartographer at `our Contribution
page`_.

.. _our Contribution page: https://github.com/cartographer-project/cartographer/blob/master/CONTRIBUTING.md

Open house slide archive
========================

In the past there had been regular open-for-all meetings to discuss progress and plans for Cartographer.
Slides of these Cartographer Open House meetings are listed below.

- March 14, 2019: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/190314/slides.pdf>`_
- February 21, 2019: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/190221/slides.pdf>`_
- January 17, 2019: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/190117/slides.pdf>`_
- November 22, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/181122/slides.pdf>`_
- October 25, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/181025/slides.pdf>`_
- September 13, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180913/slides.pdf>`_
- August 16, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180816/slides.pdf>`_
- August 2, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180802/slides.pdf>`_
- July 5, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180705/slides.pdf>`_
- June 21, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180621/slides.pdf>`_
- June 7, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180607/slides.pdf>`_
- May 24, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180524/slides.pdf>`_
- May 3, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180503/slides.pdf>`_
- March 29, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180329/slides.pdf>`_
- February 22, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180222/slides.pdf>`_
- February 8, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180208/slides.pdf>`_
- January 18, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180125/slides.pdf>`_
- January 11, 2018: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/180111/slides.pdf>`_
- December 7, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/171207/slides.pdf>`_
- November 23, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/171123/slides.pdf>`_
- November 9, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/171109/slides.pdf>`_
- October 26, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/171026/slides.pdf>`_
- October 12, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/171012/slides.pdf>`_
- September 14, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170914/slides.pdf>`_
- August 17, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170817/slides.pdf>`_
- July 20, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170720/slides.pdf>`_
- July 6, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170706/slides.pdf>`_
- June 22, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170622/sildes.pdf>`_
- June 8, 2017: `Slides <https://storage.googleapis.com/cartographer-public-data/cartographer-open-house/170608/slides.pdf>`_

.. |license| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
     :alt: Apache 2 license.
     :scale: 100%
     :target: https://github.com/cartographer-project/cartographer/blob/master/LICENSE
.. |video| image:: https://j.gifs.com/wp3BJM.gif
    :alt: Cartographer 3D SLAM Demo
    :scale: 100%
    :target: https://youtu.be/DM0dpHLhtX0
