# PET data from a Siemens mMR scanner

This data was acquired at the Institute of Nuclear Medicine, University
College London Hospital by Ben Thomas and Tom Sanderson.

It is part of the PET data of a NEMA phantom acquisition for about 60s.
The reconstructed image would therefore be very noisy. We do this to 
reduce data size of the listmode file. The mu-map is was obtained
by scanning the phantom on a GE Discovery 710 PET/CT scanner,
registering the CT to an MR acquisition, and converting it to
linear attenuation coefficients (mu-values) and down-sampling it.

## Files
- list.l, list.l.hdr: listmode file and its header
- norm.n, norm.n.hdr: file with normalisation info and its header
- mu_map.v, mu_map.hv: file with the attenuation image and its header (in STIR Interfile format)