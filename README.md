# Oneplanetassignment
Dataset: WESAD
(https://ubicomp.eti.uni-siegen.de/home/datasets/icmi18/)
Run scripts in the following order (can take a while) to prepare data and extract features 

Preprocess and merge subject data
Command:
python merge_data.py

Input data path: 'data/WESAD/'
Generates the following files in data folder:
subj_merged_acc_w.pkl
subj_merged_bvp_w.pkl
subj_merged_eda_temp_w.pkl
merged_chest_fltr.pkl
