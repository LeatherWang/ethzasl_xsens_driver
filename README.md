Thanks to all predecessors' work, I add hareware time synchronization with a IDS UI-1221LE camera.

In my project, I only use a camera and a Xsens without any extra sampling device, such as, a Single chip microcomputer.
As for the camera driver demo, I put it in this project: [LeatherWang/ueye_cam](https://github.com/LeatherWang/ueye_cam/tree/extrigger_software).

For detail, you can see `MT Manager User Manual`, `MT Low-Level Communication Protocol Documentation` and `MTw SDK User Manual`.


Firstly, use the `SyncOut`, make Xsens send a extrigger singal.
![A3](https://github.com/LeatherWang/ethzasl_xsens_driver/raw/master/screenshots/A3.jpg)

This is the camera and IMU and they communicate only use one cable. 
![A2](https://github.com/LeatherWang/ethzasl_xsens_driver/raw/master/screenshots/A2.jpg)

This is the result.
![A1](https://github.com/LeatherWang/ethzasl_xsens_driver/raw/master/screenshots/A1.png)

---

ROS Driver for XSens MT/MTi/MTi-G devices.

See: http://ros.org/wiki/ethzasl_xsens_driver
