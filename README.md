# Cloud_vs_Radiance_GOES16

This repository includes the code used to produce the figures in article "Using Multi-Linear Regression to Understand Cloud
Properties’ Impact on Solar Radiance" by Grant Parker.

The file "Cloud_vs_Radiance_GOES16" is a jupyter notebook that uses a python kernel. To properly use the file, all datasets should be MAT files. For a specific day, the mat file should include the following variables: cloud optical depth (cod), cloud top temperature (ctt), solar zenith angle (sza), look zenith angle (lza), and the Textured Cloud Mask (tcm). Each dataset (MAT File) should include these properties for a single day (days we used were 4,5,6th of January, May, July, and September of 2020; 3,4,5 March 2020; and 15 May 2020). 

To download the data, you can go to https://www.avl.class.noaa.gov/saa/products/search?sub_id=0&datatype_family=GRABIPRD&submit.x=24&submit.y=6. In the drop-down menu, select "GOES-R Series ABI Products (GRABIPRD) (partially restricted L1b and L2+ Data Products)." You can then select the dates and desired properties. For this project, all datasets were captured with a start time of ~1740 UTC, so for replication purposes, datasets should be downloaded with this start time. For the radiance data, make sure you selected "C02" for the ABI Channel and "Full Disk" for the ABI scan sector.

After downloading the data and processing it through MATLAB, the MAT files can be used in the Jupyter notebook to conduct the statistical analysis (SEE "CLoud_vs_Radiance_GOES16.jp
