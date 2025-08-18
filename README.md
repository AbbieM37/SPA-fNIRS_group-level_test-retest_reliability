# SPA-fNIRS_group-level_test-retest_reliability
Code for Block-Averaged Waveforms and GLM analyses presented in the following manuscript: *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*

## Requirements:
This script was executed with **Python 3.12** in **Jupyter Notebook**. All necessary libraries and packages are imported within the script, including MNE and MNE-NIRS.

## Scripts:
Each analysis script is titled for its given purpose. The first script titled 'NoCorrection-Script' is used to run the GLM process for the no short channel correction denoising model. The second script titled 'ShortChanCorrection-Script' is used to run the GLM process for the short channel correction denoising model. The third script titled 'tCCA-Script' is used to run the GLM process for the short chanel correction + tCCA denoising model. 

To run each analysis:
  1. Open the notebook
  2. Run each cell in sequential order

These scripts will: 
  1. Import necessary packages and libraries
  2. Define functions needed to run analyses
  3. Run the GLM for each model
  4. Format the results for plotting both region of interest (ROI)-level and channel-level data


## Data format:
Each script expects fNIRS data in formats such as `.snirf`. Make sure your data is correctly preprocessed and formatted as described in the manuscript before running the notebook. 

Data from the GLM processes are stored in .csv files for both ROI and channel-level data. These ROI-level hemodynamic response amplitudes were used for Figure 5 in the manuscript. Additionally, channel-level hemodynamic response amplitudes were used for Figure 6 in the manuscript.

## Citation:
If you use this code in your research, please cite the manuscript: *Group-level test-retest reliability assessment using systemic physiology augmented functional near-infrared spectroscopy during a passive-listening task*


