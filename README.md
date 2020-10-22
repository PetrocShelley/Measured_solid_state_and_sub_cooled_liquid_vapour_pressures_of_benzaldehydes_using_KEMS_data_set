# Measured_solid_state_and_sub_cooled_liquid_vapour_pressures_of_benzaldehydes_using_KEMS_data_set
Data set for Measured solid state and sub-cooled liquid vapour pressures using KEMS

This repository contains the raw data used to calculate the saturation vapour pressures of various benzaldehyde compounds.

This is the corrosponding data set to Measured solid state and sub-cooled liquid vapour pressures of benzaldehydes using Knudsen effusion mass spectrometry...

This project is licensed under the terms of the GNU General Public License v3.0, as provided with this repository.

The KEMS_data_files folder contains the files for all of the raw mass spectra used in the calculations. The format for the file names follows: date of experiment, electron impact multiplication factor, compound name (followed by _run2 if multiple measurements of the same compound were done on the same day), the pinhole size of the Knudsen cell, the background pressure of the mass spec chamber of the KEMS, and the temperature at which the measurement was taken. Gate closed was when the mass spectrometer was isolated from all sample and used to check the mass spectrometer chamber was clean. Gate open was used as the background measurement for the further calculations.

The KEMS_python_scripts show how the solid state saturation vapour pressure  at 298 K was calculated using Jupyter notebooks. The folders are named reference compound sample compound with the dates corrosponding to the raw files the from KEMS_data_files. There is also a brief example script available.

TA_DSC_2500_data_files contains the raw DSC data that is used in the sub-cooled correction calculations.

KEMS_MOPAC2016_files contains MOPAC files that were used to estimate the partial charges of the atoms within the molecules of the studied compounds as well as the polarisability of the molecules.

The Excel spreadsheet contains all calculated solid state and sub-cooled saturation vapour pressures.

[![DOI](https://zenodo.org/badge/306290521.svg)](https://zenodo.org/badge/latestdoi/306290521) Citation: Shelley et al., (2020) Measured_solid_state_and_sub_cooled_liquid_vapour_pressures_of_benzaldehydes_using_KEMS_data_set, Zenodo,  https://doi.org/10.5281/zenodo.4117801
