# $Chessboard  \space  Model  \space Camera \space Calibration$ 
## $\space  Fisheye  \space V.S \space  Pinhole  \space Model  \space | \space OpenCv$

## Overview

This repository demonstrates the process of **camera calibration** using two popular models: the **Fisheye Camera Model** and the **Pinhole Camera Model**. The project uses a **chessboard pattern** to calibrate the camera and compare the accuracy of both models.

Camera calibration is essential for removing lens distortion and estimating the intrinsic and extrinsic parameters of the camera. This process is crucial for applications such as 3D reconstruction, object tracking, and visual odometry, where precise measurements are needed.

![](https://github.com/Nassimos07/Camera-Calibration-Camera-Undistortion-Fisheye-Camera-Pinhole-Python-OpenCV-/blob/main/Images/Brown%20Photo%20Centric%20Holi%20Festival%20Sale%20Website%20banner%20(2).png)

### Calibration Models

Two primary camera models are used in this project:

1. **Pinhole Camera Model**:
   - The **Pinhole Camera Model** assumes that light passes through a tiny "pinhole" and projects onto a 2D image plane. This simple model doesn't account for lens distortion, which is typically present in real-world cameras.
   - The Pinhole Camera Model is often used for cameras that have minimal lens distortion.

2. **Fisheye Camera Model**:
   - The **Fisheye Camera Model** accounts for the significant distortion caused by wide-angle lenses, commonly found in fisheye cameras.
   - Fisheye lenses introduce nonlinear distortions, especially towards the edges of the image. The Fisheye Camera Model is designed to correct these distortions and provide accurate calibration results for wide-angle lenses.

### Chessboard Calibration

The **chessboard pattern** is used as a calibration target because its grid structure makes it easy to detect precise 2D points in the image, which are then matched with the 3D world coordinates to estimate the camera's parameters.

This repository compares the effectiveness of both the Pinhole and Fisheye Camera Models in removing distortion and calibrating the camera using the chessboard images.

## Project Structure
