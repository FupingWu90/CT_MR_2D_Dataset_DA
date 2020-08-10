# CT_MR_2D_Dataset_DA

It contains five zipped files of CT and MR images as described below:

# CT with ground truth

The file `CT_withGT.zip' contains 20 cases of CT, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. We provided their ground truth for LV and Myocardium.


# CT without ground truth


The file `CT_woGT.zip' constains 32 cases of MR, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. They do not have the manual labeled ground truth. We use the automatic segmentation method, i.w., M3AS , to abtain their pseudo-lables. Noying that these pseudo-lables can not be used for testing or validation, as there exists error in them.

# MR with ground truth

The file ` MR_withGT.zip' contains 20 cases of MR, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. We provided their ground truth for LV and Myocardium.

# MR without ground truth

The file ` MR_woGT.zip' contains 26 cases of MR, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. They do not have the manual labeled ground truth. We use the automatic segmentation method, i.w., M3AS , to abtain their pseudo-lables. Noying that these pseudo-lables can not be used for testing or validation, as there exists error in them.


# Citation

If you found the repository useful, please cite our work as below:
