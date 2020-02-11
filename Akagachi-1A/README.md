CAD data for DIY Akagachi type1 mode A
====
## Overview  

This data to develop your own Akagachi eye component.  
Type-1 is a small one (eye siza: 30mm) and a compact mode.
- Merit : Compact, easy to modify
- Demerit : Brush servo moters that connected directly will lower the robustness
3D printable data and 3D cad data are available.

|Overviews||  
|:---|:---|  
|<img src=https://github.com/Yasu31/robot-eyes/blob/master/cad/Akagachi-1A/images/DSC00029.JPG alt="Overview" width="320px">|<img src=https://github.com/Yasu31/robot-eyes/blob/master/cad/Akagachi-1A/images/DSC00030.JPG alt="Back" width="320px">|  
|<img src=https://github.com/Yasu31/robot-eyes/blob/master/cad/Akagachi-1A/images/DSC00031.JPG alt="Bottom" width="320px">|<img src=https://github.com/Yasu31/robot-eyes/blob/master/cad/Akagachi-1A/images/DSC00033.JPG alt="Yaw servo" width="320px">|  
|<img src=https://github.com/Yasu31/robot-eyes/blob/master/cad/Akagachi-1A/images/DSC00034.JPG alt="Side" width="320px">||  

## CAD data
We are assuming that these parts are 3D printed by the ABS or the Nylon.

|CAD name|Description|  
|:---|:---|  
|Eyeball-ASV|Eyeball parts for ASV-15-MG. A Pupil needs to be colored by your hand.|  
|Eyeball-ASV-clear|Eyeball parts for ASV-15-MG. A Pupil needs to be put a seal. After that, a crea cabochon ([e.g.](https://www.amazon.co.jp/dp/B01N9BWMKV)) is applied.|  
|Eyeball-GWS pico|Eyeball parts for PIC/STD/F. A Pupil need to be colored by your hand.|  
|Eyelid|Apparent eyelid for eyeballs. Please attach it to one another.|  
|Yaw-bracket-GWS pico|Bracket of two eye servos (PIC/STD/F) mounts on the pitch servo (H1700HS-HV).|  
|Yaw-bracket-ASV|Bracket of two eye servos (ASV-15-MG) mounts on the pitch servo (XQ-S3008D).|  
|Pitch-servo-mt-thread-XQ|Stand for the pitch servo (XQ-S3008D). Please make thread holes!|  
|Pitch-servo-mt-thread-HV|Stand for the pitch servo (H1700HS-HV). Please make thread holes!|  
|1-A-CameraStand|Stand for all parts and joint to camera stands such as Tripods.|  
|1-A-CameraStand-GoogleHome|Stand for all parts and joint to the Google home.|  
|1-A-CameraStand-AmazonEcho|Stand for all parts and joint to the Amazon echo.|  
|CameraHold|Stand for USB camera (ELP usb camera).|  

## Parts list
Parts ever used (5V)  
If you can't get follow parts, choose a close performance one and remake CAD data.
I would really appreciate your sharing of new appropriate parts.

### Servos
|Servo|Manufacturer|Stall current<br>(mA)|No load speed<br>(sec/60°)|Torque<br>(kgf-cm)|description|  
|:---|:---|:---:|:---:|:---:|:---|     
|PIC/STD/F|[GWS](https://gwsus.com/gws_com_tw_www/english/product/servo/sub%20micro.htm)||0.12|0.7|yaw servo|  
|ASV-15-MG|[Asakusa Gi Ken](http://www.robotsfx.com/robot/ASV-15.html)|300|0.125|1.6|yaw servo|  
|H1700HS-HV|[Blue Arrow](http://www.ltair.com/index.php?route=product/product&manufacturer_id=8&product_id=351)||0.068|2.7|pitch servo|  
|XQ-S3008D|[XQ Power](http://www.xq-power.com/XQ-S30P/show_64.html)|1750|0.09|7|pitch servo|  

### Other parts
|Parts name|Manufacturer|Description|  
|:---|:---|:---|  
|ELP-USB500W02M-AF170|[ELP](hhttp://www.webcamerausb.com/elp-wide-angle-5megapixels-high-resolution-ov5640-sensor-module-pcb-mini-auto-focus-camera-usb-with-170degree-fisheye-lens-p-64.html)|In this ROS package, we used 640x480 resolution.|  
|M2 x 8||Yaw-bracket-xx is fixed to Pitch servo horn (4 screws). 2 yaw Servos are fixed to Yaw-bracket-xx (4 screws). CELP-camera is fixed to CameraHold (4 screws & 4 nuts). Servo horn and Yaw-bracket-xx are need to be threaded screw hole|
|M3 x 8||Pitch-servo-mt-xx (4 screws) and CameraHold (2 screws & nuts) are fixed to 1-A-CameraStand. Pitch-servo-mt-xx is need to be threaded 4 screw hole|
|M3 x 15||Pitch servo is fixed to Pitch-servo-mt-xx (2 screws). Pitch-servo-mt-xx is need to be threaded 2 screw hole|


