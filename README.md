# CFS-Crafter Citation
Wang, G., Alais, D., Blake, R. et al. CFS-crafter: An open-source tool for creating and analyzing images for continuous flash suppression experiments. Behav Res (2022). https://doi.org/10.3758/s13428-022-01903-7

# CFS-Crafter Help Information

**CFS-Crafter** is an open-source MATLAB application designed for fine control manipulation and analyses of CFS stimuli. As the application does not require prior expertise in image processing and analysis, it provides an accessible platform for improving stimulus control, increasing comprehension of CFS findings, and generating more effective CFS animations.

## 1. Screen Information

Information of the screen at which the user intends to show the stimuli needs to be manually entered, which would provide the basis for calculating certain basic parameters. The user can only proceed to the next step after filling in all the required screen information.

### 1.1. Screen Refresh Rate (Hz)

*Screen Refresh Rate* should be set to the refresh rate of the screen on which the stimulus will be presented. Incorrect screen refresh rate will lead to errors in the frame rate of created stimuli and other temporal features.

### 1.2. Viewing Distance (cm)

*Viewing Distance* is the distance between the participants' eyes and the screen during the experiment. Incorrect viewing distance will lead to errors in the calculation of parameters related to the degree of visual angle.

### 1.3. Screen Resolutions (pixels) & Screen Dimensions (cm)

**CFS-Crafter** reads the *resolution* and *dimension* of the current screen and inputs them as the default values. If the user intends to use the stimuli on a different screen, these values must be changed manually. Errors in this information will result in errors in spatial frequency and other spatial features.

## 2. Choose Function

### 2.1. [Creation](./Creation.html)

![Grayscale CFS stimuli created by CFS Crafter](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/gray_mondrain.gif)

**Creation** allows the user to create various types of *CFS-Crafter-Mask*, which can be saved as a .mat file with related information or as a .mp4 video file.

- [2.1.1. Traced Pattern](./Trace.html)

  ![Traced Face Mondrain Pattern](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/traced_items/face.gif)
  
  Details about *traced item patterned masks* in **Creation**.

- [2.1.2. Stimuli Preview](./Preview.html)

  ![Preview Interface](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/preview.png)
  
  Details about previewing & saving *CFS-Crafter-Masks* & *Images*.

### 2.2. [Conversion](./Conversion.html)

![Stimuli Created using Conversion](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Conversion/image_sequence.gif)

**Conversion** allows the user to convert a set of images into a *CFS-Crafter-Mask*, so that it can be modified or analyzed using **CFS-Crafter**.

### 2.3. [Modification](./Modification.html)

![RGB stimuli created and modified by CFS Crafter](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Modification/after_termporal_filtering.gif)

**Modification** allows the user to apply spatial/temporal/orientation filtering and phase scrambling to *CFS-Crafter-Masks* or *Images*.

### 2.4. [Analysis](./Analysis.html)

![Analysis results](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Analysis/analysis_results.png)

**Analysis** allows the user to analyze and compare the descriptive statistics, spatiotemporal frequencies, and color contents of multiple stimuli (*CFS-Crafter-Masks* or *Images*).

- [2.4.1. Edge Detection](./Edge_preview.html)

  ![Edge Detection](https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Analysis/edge_detection.png)
  
  Details about edge detection in **Analysis**.

