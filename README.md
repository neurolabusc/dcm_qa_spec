
## About

This repository provides DICOM Magnetic Resonance Spectroscopy to illustrate conversion to the [BIDS standard](https://bids-specification.readthedocs.io/en/stable/modality-specific-files/magnetic-resonance-spectroscopy.html). At the moment, only Siemens XA60 DICOMs with single-voxel spectroscopy (svs) are provided.

## Running

Run `batch.sh`. It converts `In/` → `Out/` and diffs against `Ref/`.
Requires dcm2niix v1.0.20260605 or later.

## Links

 - [spec2nii](https://github.com/wtclarke/spec2nii) handles a broader range of MR spectroscopy than dcm2niix, and can also process this example dataset.
