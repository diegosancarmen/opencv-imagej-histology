# opencv-imagej-histology

## About 

The software creates a border around the population of tyrosine hydroxylase (TH+) positive dopaminergic cells within the substantia nigra pars compacta (SNpc) and ventral tegmental area (VTA) region by running the image through a series of dilations and erosions to produce a contour map. This is converted into a bitwise mask function which is used to extract the region of interest (ROI) from each fluorescence channel. A manuscript is under preparation that describes the details of the software development. Using Image-J software, mean, area and integrated density fluorescence intensity was determined for each fluorescence channel e.g., green channel for p62, within the ROI (Dela Cruz, et al. 2023).

## References

This work is used in the following paper:

Dela Cruz, H. L., Dela Cruz, E. L., Zurhellen, C. J., York, H. T., Baun, J. A., Dela Cruz, J. L., & Dela Cruz, J. S. (2020). New insights
underlying the early events of dopaminergic dysfunction in Parkinson’s Disease. In *bioRxiv (Cold Spring Harbor Laboratory).
Cold Spring Harbor Laboratory*. https://doi.org/10.1101/2020.09.27.313957
