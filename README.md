# Cloud_vs_Radiance_GOES16

This repository includes the code used to produce the figures in article "Using Multi-Linear Regression to Understand Cloud1
Properties’ Impact on Solar Radiance" by Grant Parker.

The file "Cloud_vs_Radiance_GOES16" is a jupyter notebook that uses a python kernel. To properly use the file, all datasets should be MAT files. For a specific day, the mat file should include the following variables: cloud optical depth (cod), cloud top temperature (ctt), solar zenith angle (sza), look zenith angle (lza), and the Textured Cloud Mask (tcm). Each dataset (MAT File) should include these properties for a single day (days we used were 4,5,6th of January, May, July, and September of 2020; 3,4,5 March 2020; and 15 May 2020). 
