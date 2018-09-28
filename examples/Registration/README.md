# Registration test data

This data is used to test the registration module of SIRF. Since the registration is currently limited to NiftyReg, `.nii` files are used.

The data come from Slicer's BRAINSTools Test Data, which can be found [here](http://midas.kitware.com/item/view/483). More information on the BRAINS can be found [here](https://www.slicer.org/wiki/Documentation/4.8/Modules/BRAINSFit). 

## The data


3. `mouseFixed.nii.gz` and `mouseMoving.nii.gz` are abdominal scans of two different mice. For this study non-rigid registration should be used, such as NiftyReg's `F3d`.