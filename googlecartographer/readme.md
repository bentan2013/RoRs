### What is Cartographer?

Cartographer is a system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations.

### ROS (Robot Operating System)

ROS (Robot Operating System) provides libraries and tools to help software developers create robot applications. It provides hardware abstraction, device drivers, libraries, visualizers, message-passing, package management, and more. ROS is licensed under an open source, BSD license.

Node: An agent communicating with ROS and other nodes via

- Messages: Nodes communicate with each other by publishing messages.
- Topics (publish / subscribe) using typed messages
- Services: Request / Response paradigm (think of method or operation) via typed messages
- Master: The Master provides name registration and lookup to the rest of the Computation Graph.
- Package: A virtual directory holding one or more executables (nodes)
- Bags: Bags are a format for saving and playing back ROS message data.

![](http://i2.muimg.com/567571/839ce3081de21f92.png)

### Cartographer ROS

- Configuration –launch file

- Configuration –URDF

![](http://i2.muimg.com/567571/f64e8974792540d2.png)

- Configuration –Lua

- Configuration –Workflow

![](http://i1.piimg.com/567571/c1c86173a5139a4a.png)


### Algorithm

![](http://i2.muimg.com/567571/24f993b23e2e2289.png)

### Code Analysis

![](http://i1.piimg.com/567571/1a1ca8ae01afe794.png)

### Characteristics

- ROS integration, support multi sensors
- Support 2D and 3D SLAM
- Efficient, Real-time
- Not high precision (5 cm resolution)
- Not Support visual SLAM

### References

- ROS wiki: http://www.ros.org/wiki
- Cartographer ROS: https://google-cartographer-ros.readthedocs.io/en/latest/
- Cartographer: https://google-cartographer.readthedocs.io/en/latest/
- http://mp.weixin.qq.com/s/LdbFp-Zvkr02-_25ILb16g
- http://www.itdadao.com/articles/c15a743034p0.html
- http://www.voidcn.com/blog/hjwang1/article/p-6512568.html