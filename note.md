# mid360 fastlivo2

# record data
rosbag record -O LVIO_inlab /camera/color/image_raw /livox/imu /livox/lidar
# play bag


# camera info
height: 720
width: 1280
distortion_model: "plumb_bob"
D: [-0.055450838059186935, 0.06841126084327698, -3.5516146454028785e-05, -0.00010084670066135004, -0.02119487151503563]
K: [632.0479125976562, 0.0, 628.8812255859375, 0.0, 631.2682495117188, 371.5096435546875, 0.0, 0.0, 1.0]
R: [1.0, 0.0, 0.0, 0.0, 1.0, 0.0, 0.0, 0.0, 1.0]
P: [632.0479125976562, 0.0, 628.8812255859375, 0.0, 0.0, 631.2682495117188, 371.5096435546875, 0.0, 0.0, 0.0, 1.0, 0.0]
binning_x: 0
binning_y: 0
roi: 
  x_offset: 0
  y_offset: 0
  height: 0
  width: 0
  do_rectify: False