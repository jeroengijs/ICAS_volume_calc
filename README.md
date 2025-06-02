Python version 3.12
Code snippet to calculate volume (mm³) of segmented intracranial carotid arteries. 
Segmented files are assumed to be structured as {patient_id}_{suffix}.nii. (suffix =l, r, vl, vr, b). NCCT files are assumed to be structured as {patient_id}.nii
Note: During manual segmentation, make sure bone is not included
Note: Cut-off is 130 HU. If this changes in the future, code needs to be changed.
Note: Make sure libraries are installed 
