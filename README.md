## Robot_Teleop
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
---

## Contributors
[Rajan Pande: ](https://github.com/rpande1996)
Graduate Student of M.Eng Robotics at University of Maryland.

## Overview

This goal of this code is to create custom robot in SolidWorks and operate it ROS via a keyboard

## Softwares

* Recommended IDE: Visual Studio Code 1.63.2
* Required OS: Linux Ubuntu 18.06
* SolidWorks 2020

## Libraries

* ROS Melodic

## Programming Languages

* Python 3.7

## License 

```
MIT License

Copyright (c) 2021 Rajan Pande, Douglas Summerlin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
SOFTWARE.
```

## Demo

Teleoperation:

![teleop](media/teleop.gif)


```
cd ros_ws/src
git clone https://github.com/rpande1996/Autonomous_World_Navigation
catkin_make
source ~/ros_ws/devel/setup.bash
roslaunch vehicle_urdf_updated template_launch.launch
```
Open new terminal
```
cd ros_ws/src/vehicle_urdf_updated/src
python teleop_template.py
```