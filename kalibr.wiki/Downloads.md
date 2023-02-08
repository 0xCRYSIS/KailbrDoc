
## Sample datasets

| Bag File | Configs | Description |   
|:-:|:-:|:--|
| [Multi-CAM](https://drive.google.com/file/d/1rRRSoaCUQC8Jz4vCgNhmtzn3f3urqb9e/view?usp=sharing) | [april_6x6.yaml](https://drive.google.com/file/d/10zw3LvCDvXYyTQje4Gt4vzJMMYOuGsma/view?usp=sharing) | Sample calibration bag from the EuRoC MAV dataset and configurations for the multiple-camera calibrator |
| [IMU-CAM](https://drive.google.com/file/d/1dHkfsPBzUbnoyXpmiGxSQiqt4hrPXF2z/view?usp=sharing) | [imu_adis16448.yaml](https://drive.google.com/file/d/1Q4GKJGzE5A3n3FaOaP2GPLIP7B4mrnn6/view?usp=sharing)<br/>[cam_april-camchain.yaml](https://drive.google.com/file/d/1b69v4UHVHmiNiU8J8T0oKZmle8eYSYVv/view?usp=sharing) | Sample calibration bag from the EuRoC MAV dataset and configurations for the imu-camera calibrator |
| [Multi-IMU](https://drive.google.com/file/d/1dHkfsPBzUbnoyXpmiGxSQiqt4hrPXF2z/view?usp=sharing) | [april_6x6_80x80cm.yaml](https://drive.google.com/file/d/1TCZJ1KPJrsj3ffCNnj001ege54jffc19/view?usp=sharing)<br/> [imu_adis16448.yaml](https://drive.google.com/file/d/1F9e9I1Xdm14nJw_E1j06HyinlBxRp3yu/view?usp=sharing)<br/>[imu_mti100.yaml](https://drive.google.com/file/d/1P_9KUigmLXPPIrWMFlxxImrrilAzcpvX/view?usp=sharing)<br/>[imu_mtig710.yaml](https://drive.google.com/file/d/1ZH_2n-fpFWphQ0GC7JVwaKWrLsGXZxTP/view?usp=sharing)| Three IMU and stereo camera recording. Can be used to test the multi-IMU calibration ability. A picture of the rig can be found in [this](https://pgeneva.com/downloads/papers/Eckenhoff2019ICRAb.pdf) paper for those interested. |
| [Rolling Shutter](https://drive.google.com/file/d/1Vrys2qsqO5BS_wZuyikyBuglZikloPGJ/view?usp=sharing) | [april_6x6_80x80cm.yaml](https://drive.google.com/file/d/1Cb5fBX2Zvgshw4oAa_wxVpuo7vGLQuEp/view?usp=sharing) | Recording of a ELP-960P2CAM-V90-VC USB 2.0 rolling shutter stereo pair recorded using [this](https://github.com/mdkennedy3/elp-synchronized-stereo-camera-ros-pkg) ROS package. There is no IMU data. |


## Calibration targets

| Name | Target | Config |
|:-|:-:|:-:|
| Aprilgrid 6x6 0.8x0.8 m (A0 page) | [pdf](https://drive.google.com/file/d/1DqKWgePodCpAKJCd_Bz-hfiEQOSnn_k0/view?usp=sharing) | [yaml](https://drive.google.com/file/d/1rAe_O8eFD3nR06SzhoGIUrq4BUhuaekn/view?usp=sharing) |
| Aprilgrid 6x6 & Checkerboard 7x6 0.5x0.5 m (A0 page) | ~~[pdf]()~~ |  ~~[checker-yaml]()<br> [april-yaml]()~~ |
| Aprilgrid 6x6 0.8x0.8 m (unscaled) | ~~[pdf]()~~ | ~~[yaml]()~~ |
| Aprilgrid 6x6 0.5x0.5 m (unscaled) | ~~[pdf]()~~ | ~~[yaml]()~~ |
| Checkerboard 7x6 0.5x0.5 m (unscaled) | ~~[pdf]()~~ | ~~[yaml]()~~ |

Kalibr provides a [script](calibration-targets) to generate custom targets.

## IMU configurations

| Name | Description |   
|:-:|:--|
| [ADIS 16448](https://drive.google.com/file/d/1z3GvVpzsbu8qnwTpC_YxWTCVD3snUzJX/view?usp=sharing) | IMU configuration for the  Analog Devices ADIS16448 IMU |

