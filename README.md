# Camera Calibration and Stereo Vision 

## **Camera Calibration for a Single Camera**

### Overview 

This project is designed to calibrate a single camera using a calibration board, and it’s structured into four primary stages: image collection, calibration processing, reprojection error analysis, and result visualization. By leveraging established OpenCV functions, the pipeline efficiently computes the camera’s intrinsic parameters (such as focal length, principal point, and distortion coefficients) as well as its extrinsic parameters (rotation and translation vectors). The end goal is to undistort images and quantify calibration accuracy through reprojection error analysis while providing visual confirmation of the calibration quality.

