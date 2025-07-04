# mid360 fastlivo2

# record data
rosbag record -O LVIO_inlab /camera/color/image_raw /livox/imu /livox/lidar /synced_image /synced_lidar /camera/depth/color/points
# play bag


# camera info
{
  "camera": {
    "camera_model": "plumb_bob",
    "distortion_coeffs": [
      -0.055450838059186935,
      0.06841126084327698,
      -3.5516146454028785e-05,
      -0.00010084670066135004,
      -0.02119487151503563
    ],
    "intrinsics": [
      631.1903076171875,
      630.41162109375,
      628.8812255859375,
      371.5096435546875
    ]
  },
  "meta": {
    "bag_names": [
      "livox_data_20250703_cali_0.db3"
    ],
    "camera_info_topic": "/camera/camera/color/camera_info",
    "data_path": "/tmp/input_bags",
    "image_topic": "/camera/camera/color/image_raw",
    "intensity_channel": "intensity",
    "points_topic": "/livox/lidar"
  },
  "results": {
    "T_lidar_camera": [
      0.03842141220053184,
      -0.01910240283287441,
      -0.07586569777611907,
      -0.5004375069928715,
      0.49727401587174835,
      -0.5011884722776524,
      0.5010897823639363
    ],
    "init_T_lidar_camera": [
      -0.01,
      -0.03,
      -0.09,
      -0.4999999999999999,
      0.5,
      -0.5,
      0.5000000000000001
    ]
  }
}

