# Registration test data

This data is used to test the registration module of SIRF. Since the registration is currently limited to NiftyReg, `.nii` files are used.

The data come from Slicer's BRAINSTools Test Data, which can be found [here](http://midas.kitware.com/item/view/483). More information on the BRAINS can be found [here](https://www.slicer.org/wiki/Documentation/4.8/Modules/BRAINSFit). 

## The data1. `test.nii.gz` and `test2.nii.gz` are two T1-weighted MR brain scans taken one year apart. Since this is a longitudinal brain study, they are useful for rigid registration, such as Niftyreg's `Aladin`.
2. `test.nii.gz` and `standard.nii.gz` are two brain scans taken with different modalities (T1 & T2). Since this is a multimodal brain study, they are useful for rigid registration, such as Niftyreg's `Aladin`.

3. `mouseFixed.nii.gz` and `mouseMoving.nii.gz` are abdominal scans of two different mice. For this study non-rigid registration should be used, such as NiftyReg's `F3d`.4. Lastly, two example parameter files are given in the folder `paramFiles`. `niftyreg_aladin.par` and `niftyreg_f3d.par` correspond to parameter files for Niftyreg's `aladin` and `f3d` registration algorithms, respectively. They do not contain an exhaustive list of all parameters for these algorithms, so check the source code (SIRF or NiftyReg) for that.