# DICOM 2D

## Objectives

Given a dynamic renal study from a gamma camera in DICOM format (available from https://dynamicrenalstudy.org/browse#).

The files are:

* drsprg_114_ANT.dcm (anterior acquisition)
* drsprg_114_POST.dcm (posterior acquisition)

A) Calculate the following using appropriate tags from the file:
1. Pixel size
2. Date and time of the examination
3. Manufacturer of the imaging system
4. Number of frames
5. Radioisotope used
6. Permissible energy window (keV) (search for Tag '0054', '0012'). Comment on the window boundaries.
7. Exposure time
8. Maximum pixel value

B) Define a region of interest (ROI) for each of the 2 kidneys, as well as an ROI for the background.
Calculate and plot:
1. Activity curve for each kidney, before and after background correction, for both posterior and anterior acquisitions.
2. Propose a method for combining the 2 acquisitions into a single acquisition.
