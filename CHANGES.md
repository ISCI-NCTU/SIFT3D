# SIFT3D version history

## 1.0.0

* Initial release

## 1.1.0

* Added DICOM IO
* Wrapped DICOM and NIFTI IO in C functions im_read and im_write
* Added matlab wrappers keypoint3D, imRead3D and imWrite3D
* Changed C function SIFT3D_Extract_Descriptors to SIFT3D_Extract_Descriptors and SIFT3D_Extract_Raw_Descriptors
* Fixed various bugs, improving keypoint and descriptor accuracy

## 1.1.1 October 30, 2015

* Performance optimizations
* Fixes to DICOM slice ordering (im_read, imRead3D)
* Write more DICOM metadata (im_write, imWrite3D)
* Corrected Mac build instructions

## 1.2

* Write more NIFTI metadata (im_write, imWrite3D)
* Changed C interface for descriptor extraction to disallow providing a custom Gaussian scale-space pyramid (SIFT3D_Extract_Descriptors)
* Minor bug fixes