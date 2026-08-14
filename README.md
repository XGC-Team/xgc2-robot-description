# XGC2 Robot Description

Public aggregator for XGC2 visual robot descriptions. Each robot stays in its
own repository; this tree only pins the ROS 1 and ROS 2 checkouts used by the
main product catalog.

Visual assets are the same across ROS 1 distros. There is no second Scout tree
for Melodic. The Melodic Debian package is still built from the source
repository's `melodic` branch (catkin / Bionic), not from a duplicate checkout
here.

| Path | Repository | Branch |
| --- | --- | --- |
| `ros1/scout_description` | [xgc2-scout-description](https://github.com/XGC-Team/xgc2-scout-description) | `noetic` |
| `ros1/fs150_description` | [xgc2-fs150-description](https://github.com/XGC-Team/xgc2-fs150-description) | `noetic` |
| `ros1/mecanum_description` | [xgc2-mecanum-description](https://github.com/XGC-Team/xgc2-mecanum-description) | `noetic` |
| `ros1/b2arx_description` | [xgc2-b2arx-description](https://github.com/XGC-Team/xgc2-b2arx-description) | `noetic` |
| `ros2/scout_description` | xgc2-scout-description | `jazzy` |
| `ros2/fs150_description` | xgc2-fs150-description | `jazzy` |
| `ros2/mecanum_description` | xgc2-mecanum-description | `jazzy` |
| `ros2/b2arx_description` | xgc2-b2arx-description | `jazzy` |

Clone recursively:

```bash
git clone --recurse-submodules git@github.com:XGC-Team/xgc2-robot-description.git
```

The main catalog mounts this repository at
`products/robotics/robot-description`.
