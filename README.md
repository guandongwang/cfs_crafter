# CFS-Crafter Citation
Wang, G., Alais, D., Blake, R. et al. CFS-crafter: An open-source tool for creating and analyzing images for continuous flash suppression experiments. Behav Res (2022). https://doi.org/10.3758/s13428-022-01903-7

# CFS-Crafter Help Information  

**CFS-Crafter** is an open-source MATLAB application designed for precise control, manipulation, and analysis of CFS stimuli. The application does not require prior expertise in image processing and analysis, making it an accessible tool for improving stimulus control, enhancing comprehension of CFS findings, and generating more effective CFS animations.  

---

## 1. Screen Information  

Users must manually enter the screen details for stimulus presentation. This information is essential for calculating key parameters. The user cannot proceed to the next step without completing all required fields.  

### 1.1. Screen Refresh Rate (Hz)  

The *screen refresh rate* should match the refresh rate of the display used for stimulus presentation. An incorrect value may cause errors in frame rate and other temporal properties.  

### 1.2. Viewing Distance (cm)  

The *viewing distance* is the distance between the participant’s eyes and the screen during the experiment. Incorrect values may lead to errors in calculations related to the degree of visual angle.  

### 1.3. Screen Resolution (pixels) & Screen Dimensions (cm)  

**CFS-Crafter** automatically detects the *screen resolution* and *dimensions* of the current display and sets them as default values. If the stimuli will be used on a different screen, these values must be updated manually. Incorrect information may cause errors in spatial frequency and other spatial properties.  

---

## 2. Choose Function  

### 2.1. [Creation](./Creation.html)  

<img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/gray_mondrain.gif" width="250" height="250">  

The **Creation** function allows users to generate various types of *CFS-Crafter Masks*, which can be saved as `.mat` files with metadata or exported as `.mp4` video files.  

- **[Traced Pattern](./Trace.html)**  

  <img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/traced_items/face.gif" width="250" height="250">  

  Details about *traced item patterned masks* in **Creation**.  

- **[Stimuli Preview](./Preview.html)**  

  <img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Creation/preview.png" width="250" height="250">  

  Details about previewing & saving *CFS-Crafter Masks* & *Images*.  

### 2.2. [Conversion](./Conversion.html)  

<img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Conversion/image_sequence.gif" width="250" height="250">  

The **Conversion** function allows users to transform a set of images into a *CFS-Crafter Mask*, enabling further modification or analysis.  

### 2.3. [Modification](./Modification.html)  

<img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Modification/after_termporal_filtering.gif" width="250" height="250">  

The **Modification** function applies spatial, temporal, and orientation filtering, as well as phase scrambling, to *CFS-Crafter Masks* or *Images*.  

### 2.4. [Analysis](./Analysis.html)  

<img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Analysis/analysis_results.png" width="250" height="250">  

The **Analysis** function provides tools for analyzing and comparing descriptive statistics, spatiotemporal frequencies, and color content of multiple stimuli (*CFS-Crafter Masks* or *Images*).  

- **[Edge Detection](./Edge_preview.html)**  

  <img src="https://raw.githubusercontent.com/guandongwang/cfs_crafter/main/CFS-Crafter%20Help%20Information/Images/Analysis/edge_detection.png" width="250" height="250">  

  Details about edge detection in **Analysis**.  


