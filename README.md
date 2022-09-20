# amygdala_hippocampus_PE

Repository associated with the work on coupling of amygdala and hippocampus and its association with prediction error in aversive learning.
In the data folder you'll find the results of the selected RL model ('scr_clean2.csv'), the framewise displacement data per condition (for each subjects; fdData.csv);
The demographic data (demographic.csv).
You can also find the functional connectivity between the ROIs in the 'neuroSynth_connectivity.csv' file. 
Last - For anyone who would like to test the RL model, the SCR data can also be found in 'SCR3.csv'.

In the main folder you'll find the notebooks of relevant analysis:
- Bayesian RL model: scr_Pymc_noShock.ipynb
- Statistical models: models.py; notebook: finalStatAnalysis_WholeROIs.ipynb
- Group Comparison: groupComparison.ipynb
- Analysis of demographic data: demData.ipynb
- Creation of relevant figures: MainFiguresWholeROI.ipynb

If anyone wants to look at the simple MLE model, its under the MLE folder.

For any questions, please feel free to contact: 
or.duek at yale.edu



