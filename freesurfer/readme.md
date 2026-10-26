Provenance:

- [ds004230 v2.3.1](https://openneuro.org/datasets/ds004230/versions/2.3.1)
- From the `derivatives/freesurfer/sub-PS11` folder
- Ran through [mgz-optimize](http://github.com/pwighton/mgz-optimize)
- Converted to nii.gz using [`mri_convert`](https://surfer.nmr.mgh.harvard.edu/fswiki/mri_convert)
- `.annot` files were convert to gifti using `mris_convert` in FreeSurfer 8.2.0
  - `mris_convert --annot ./label/lh.aparc.annot ./surfaces/lh.white ./label/lh.aparc.annot.gii`
  - `mris_convert --annot ./label/rh.aparc.annot ./surfaces/rh.white ./label/rh.aparc.annot.gii`
