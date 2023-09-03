# surgical-seltzer
OpenCV LED display fill factor calculator

Note that panel and camera settings have a fairly significant effect on final
percentage calculation.
This panel captured on my phone measures out at 18.1% fill factor, whereas
captured via a full frame mirrorless with 45mm lens results in 12.4% fill
factor. Will have to experiment with luminance and camera settings to get a
repeatable and realistic amount of bloom out of each pixel.

## Keypoint detection
![keypoint detection](output_1_keypoints.png)

## Grid detection
![grid detection](output_2_corners.png)

## Grid warp correction
![grid warping](output_3_warp_corners.png)

## Warped grid thresholding and area calculation
![warped grid thresholding and area calculation](output_4_warp_thresh.png)