# SPA-fNIRS_group-level_test-retest_reliability
Code for Block-Averaged Waveforms and GLM analyses presented in the following manuscript: *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*

## Requirements:
This script was executed with **Python 3.12** in **Jupyter Notebook**. All necessary libraries and packages are imported within the script, including MNE and MNE-NIRS.

## Scripts:
Each analysis script is titled for its given purpose. The first script titled "BlockAvg-Waveforms" is used to generate the waveforms associated with the dataset. The second script titled "NoCorrection-ShortChanCorrection-Script" is used to run the GLM process for both the no short channel correction denoising model and the short channel correction denoising model. The third script titled "tCCA-Script" is used to run the GLM process for the short chanel correction + tCCA denoising model. 

To run each analysis:
  1. Open the notebook
  2. Run each cell in sequential order 

## Data format:
Each script expects fNIRS data in formats such as `.snirf`. Make sure your data is correctly preprocessed and formatted as described in the manuscript before running the notebook.

## Citation:
If you use this code in your research, please cite the manuscript: *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*


