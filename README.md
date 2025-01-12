Folder providing scripts to reproduce results and anlaysis of the MD Simulations part of the work:  A-to-I hyper-editing of dsRNA confers unique conformational dynamics and protein interactions.

Two main folder are present:
A_dsRNA correspond to the simulations performed for the adenosines dsRNA
I_dsRNA correspond to the simulations performed for the inosines dsRNA

Both folder contains all input parameters used for MD, and a jupyter notebook called generting ensembles.ipynb where weights are calculated by using WHAN and Max Ent to generate the ensembles

The subfolder I_dsRNA/ME_bias+RECT_MD also contains a jupyter notebook PCA.ipynb where PCA analysis and clustering is performed.

Input data to be download from Zenodo: 10.5281/zenodo.13886761
- 4 dump.xtc trjectories (1000 frames etc) for the 4 ensembles:
- all the bias energy files, needed to comoute weights -> Bias_and_ensembles_data.zip
- 2 full trajectories 
