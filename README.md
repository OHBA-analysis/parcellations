### Some parcellations

- `fmri_d100_parcellation_with_PCC_reduced_2mm_ss5mm_ds8mm.nii.gz` from Mark for the time embedded HMM, 38 ROIs
- The following is a set from Giles with 40 ROIs, non-binary parcellations
	
		fmri_d100_parcellation_with_PCC_biggerCoverageJul16.dtseries.nii
		fmri_d100_parcellation_with_PCC_tighterMay15_v2_2mm.nii.gz
		fmri_d100_parcellation_with_PCC_tighterMay15_v2_6mm_exclusive.nii.gz
		fmri_d100_parcellation_with_PCC_tighterMay15_v2_8mm.nii.gz

##### From Jeroen

2mm & 8mm, 4D-file vs Winner-Takes-All. These parcellations consist of 38 parcels

	fMRI_parcellation_ds2mm.nii.gz
	fMRI_parcellation_ds8mm.nii.gz
	WTA_fMRI_parcellation_ds2mm.nii.gz
	WTA_fMRI_parcellation_ds8mm.nii.gz
	
##### Desikan-Killiany

- `dk_cortical_network` and `dk_full_network` are originally from Stam, computing from the HCP using the Desikan-Killiany parcellation. These also have connectivity and distance matrices and are thus also used for biophysical model simulations
- `dk_cortical` and `dk_full` correspond to just the parcellation component of the above two networks, and are stored in standard `.nii` format for convenient use within OSL# parcellations
