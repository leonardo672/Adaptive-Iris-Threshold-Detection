# Adaptive-Iris-Threshold-Detection


#### The results:
shows that at a threshold of 85, approximately 47% of the eye frame is black, which aligns well with the target for isolating the iris area. While the result isn’t a perfect isolation of the iris (since other dark areas are included), this threshold provides a reasonable balance for eye-tracking purposes using threshold-based segmentation.

#### Purpose:
The code aims to determine a binarization threshold that isolates the iris region as accurately as possible. By targeting a black pixel occupancy around 48%, the code finds a balance that generally includes the iris and excludes other regions in the eye frame. This is an approximate method for iris isolation based on simple thresholding, suitable for cases where precision isn’t paramount but general detection is sufficient. 

#### Key Observations:
Black Pixel Occupancy: The 48% target isn't absolute but offers a good starting point to isolate the iris in most cases.

Thresholding Limitations: Without further segmentation, surrounding dark areas (eyelashes, shadows) might still be included at this threshold, which is an expected limitation of this approach.


### Optimal Threshold: 85 
![1](https://github.com/user-attachments/assets/d353377a-44fa-4212-b5f4-7282c4e5cc51)
![3](https://github.com/user-attachments/assets/6a794a18-c6e3-493e-9055-49cf5e92d6f3)


### Optimal Threshold for eye frame: 85
