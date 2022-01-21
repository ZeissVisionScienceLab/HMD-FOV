---
layout: default
title: Methods
nav_order: 2
nav_exclude: false
---
## Methodology

A wide FoV fisheye camera for the Raspberry Pi was used to take images of VR headsets at typical eye positions. We varied the camera's position to check for the influence of interpupillary distance as well as eye relief on the visible FoV. The camera has been calibrated before to calculate FoV contour in visual angle from the extracted VR image contour. Horizontal and vertical FoVs are calculated from this contour and can be compared to the manufacturers' specifications. Only horizontal and vertical FoVs are often not enough to compare different headsets because the shape of the FoV can be quite different. Therefore, we additionally calculated the solid angle for each FoV contour, which is a direct measure for the area covered in angular space by the FoV contour.

<img src="https://github.com/ZeissVisionScienceLab/HMD-FOV/blob/main/figures/cam_procedure.svg?raw=true" alt="Camera calibration" width="800"/>

More details are given in [our paper](https://rdcu.be/cE7D2)

### > [Back to main page](https://zeissvisionsciencelab.github.io/HMD-FOV/)