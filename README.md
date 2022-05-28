# CT_MR_2D_Dataset_DA

The dataset contains selected slices from multi-center, used in paper (1-3). It contains five zipped files of CT and MR images as described below:
1. X. Zhuang et al., “Evaluation of algorithms for multi-modality whole heart segmentation: An open-access grand challenge,” Med. Image Anal.,
vol. 58, pp. 101537–101550, Dec. 2019.
2. X. Zhuang and J. Shen, “Multi-scale patch and multi-modality atlases
for whole heart segmentation of MRI,” Med. Image Anal., vol. 31,
pp. 77–87, Jul. 2016.
3. M. Schaap et al., “Standardized evaluation methodology and reference
database for evaluating coronary artery centerline extraction
algorithms,” Med. Image Anal., vol. 13, no. 5, pp. 701–714,
Oct. 2009.
# CT with ground truth

The file `CT_withGT.zip' contains 20 cases of CT, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. We provided their ground truth for LV and Myocardium.


# CT without ground truth


The file `CT_woGT.zip' constains 32 cases of CT, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. They do not have the manual labeled ground truth. We use the automatic segmentation method, i.w., M3AS [1], to abtain their pseudo-lables. Noying that these pseudo-lables can not be used for testing or validation, as there exists error in them.

# MR with ground truth

The file ` MR_withGT.zip' contains 20 cases of MR, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. We provided their ground truth for LV and Myocardium.

# MR without ground truth

The file ` MR_woGT0/1.zip' contains 26 cases of MR, each case has 16 slices from the long-axis
view around the center of left ventricular cavity. They do not have the manual labeled ground truth. We use the automatic segmentation method, i.w., M3AS , to abtain their pseudo-lables. Noying that these pseudo-lables can not be used for testing or validation, as there exists error in them.


# Citation

If you found the repository useful, please cite our work as below:
```
@ARTICLE{9165963,

  author={F. {Wu} and X. {Zhuang}},

  journal={IEEE Transactions on Medical Imaging}, 

  title={CF Distance: A New Domain Discrepancy Metric and Application to Explicit Domain Adaptation for Cross-Modality Cardiac Image Segmentation}, 

  year={2020},

  volume={},

  number={},

  pages={1-1},}
```

and 

```
@article{Zhuang2016Multi,
  title={Multi-scale patch and multi-modality atlases for whole heart segmentation of MRI.},
  author={Zhuang, Xiahai and Shen, Juan},
  journal={Medical Image Analysis},
  pages={77-87},
  year={2016},
}

```

or
```
F. Wu and X. Zhuang, "CF Distance: A New Domain Discrepancy Metric and Application to Explicit Domain Adaptation for Cross-Modality Cardiac Image Segmentation," in IEEE Transactions on Medical Imaging, doi: 10.1109/TMI.2020.3016144.
```

# Reference
1. X. Zhuang and J. Shen, “Multi-scale patch and multi-modality atlases for whole heart segmentation of MRI,” Medical image analysis, vol. 31, pp. 77–87, 2016.
