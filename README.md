# Adaptive-Iris-Threshold-Detection

#### 1- Extract the Eye Frame

#### 2- Iris Isolation via Thresholding

#### 3- Find Optimal Threshold for Iris Binarization

#### The code iterates through a range of threshold values to find the best one for isolating the iris. 
#### Each thresholded image is displayed in a grid, showing the iris size detected for each threshold. The best threshold is selected based on how close the detected iris size is to the target size. The target size in this context refers to the ideal proportion of black pixels in the binarized eye region, representing the iris and the selected threshold is the one where the calculated iris occupancy is closest to this 48% target, making it optimal for isolating the iris across various lighting conditions and eye appearances.


### Optimal Threshold: 85 
![1](https://github.com/user-attachments/assets/d353377a-44fa-4212-b5f4-7282c4e5cc51)

![2](https://github.com/user-attachments/assets/a22064a9-035b-40c1-9910-7591ff3a2475)

### Optimal Threshold for eye frame: 85
